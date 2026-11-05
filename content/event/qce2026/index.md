---
title: Fault Attacks on ML-based Quantum Control and Error Correction

event: 2026 IEEE International Conference on Quantum Computing and Engineering (QCE 2026)
event_url: https://qce.quantum.ieee.org/2026/

location: Metro Toronto Convention Centre
address:
  street:
  city: Toronto
  region: Ontario
  postcode: ''
  country: Canada

summary:
abstract: "Machine-learning (ML) models are increasingly used in quantum computing systems to discriminate multi-qubit readouts, mitigate correlated readout errors, and decode quantum error-correcting codes, making them an integral component of today’s quantum computer control and readout stacks. This paper is the first to analyze the susceptibility of such ML models to physical fault injection, which can cause quantum computers to return incorrect results or perform wrong error correction operation. This work studies two representative architectures: (i) a fully connected neural network for 5-qubit (32-class) readout error correction (HERQULES), and (ii) a convolutional neural network used as a Deep Q-learning (Deep Q) decoder for the distance-5 Surface Code. Using the ChipWhisperer Husky for voltage glitching together with automated search over the fault parameter space, this work localizes successful fault settings to specific layers of each target model. On the HERQULES model, fault susceptibility is strongly layer-dependent: early layers exhibit higher misprediction rates than later layers. On the Deep Q decoder, a single trigger-aligned voltage glitch in either the first convolutional layer or the final fully connected output layer reduces decoding accuracy from 100% to as low as 21.57%. We further characterize the resulting failures at the bitstring level using Hamming-distance and per-bit flip statistics, showing that single-shot glitches can induce structured corruption rather than purely random noise. These results motivate treating ML-based quantum readout and error-correction decoding as security-critical components, and highlight the need for lightweight fault-detection and redundancy mechanisms in quantum computing pipelines."

# Talk start and end times.
# End time can optionally be hidden by prefixing the line with #.
date: '2026-09-14T14:00:00Z'
date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2026-11-05T00:00:00Z'

authors: ['Anthony Etim', 'Jakub Szefer']
tags: ['Fault Injection Attacks', 'Machine Learning', 'Quantum Computing', 'Quantum Error Correction']

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point:

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
# Associate this talk with Markdown slides.
# Simply enter your slide deck's filename without extension.
# E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
# Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
# Associate this post with one or more of your projects.
# Simply enter your project's folder or file name without extension.
# E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
# Otherwise, set `projects = []`.
# projects:
#   - example

# <!--
# {{% callout note %}}
# Click on the **Slides** button above to view the built-in slides feature.
# {{% /callout %}}

# Slides can be added in a few ways:

# - **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
# - **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
# - **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

# Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
---
