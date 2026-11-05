---
title: Power Side-Channel Attacks on Machine-Learning-based Quantum Error Correction Decoders

event: 2026 International Workshop on Hardware and Architectural Support for Security and Privacy (HASP 2026)
event_url: https://www.haspworkshop.org/2026/index.html

location: 2026 International Workshop on Hardware and Architectural Support for Security and Privacy (HASP 2026)
address:
  street:
  city: Athens
  region: Attica
  postcode: ''
  country: Greece

summary:
abstract: Machine-learning (ML) decoders are increasingly used in quantum error correction (QEC) to process measured syndromes and determine corrective operations, making them a security-critical component of quantum computing control systems. This paper investigates physical power side-channel attacks against ML-based quantum error correction decoders. We study a Deep Q-learning convolutional neural network decoder for the distance-5 Surface Code running on an Arm Cortex-M4 microcontroller, instrumented with a ChipWhisperer Husky for power-trace acquisition. Using profiled power measurements associated with the first convolutional layer (CONV1) and the final fully connected layer (FC3), we evaluate whether an attacker can infer information about the errors processed by the decoder. Across three independent capture campaigns and five classifier seeds, the evaluated classifiers achieve up to 83.2% accuracy in identifying the faulty data-qubit label across 25 classes, compared with a 4% random-guessing baseline, and up to 84.6% accuracy in identifying the associated Pauli X or Z error type, compared with a 50% baseline. The FC3-associated power window provides higher qubit-localization accuracy than the CONV1-associated window under the evaluated protocol. We further investigate execution-time leakage across implementations configured for different Surface Code distances, demonstrating that timing characteristics can reveal information about decoder implementation parameters. These results highlight confidentiality risks in ML-based quantum error correction and motivate side-channel-resistant implementations of quantum computing control systems.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with #.
date: '2026-10-31T12:30:00Z'
date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2026-11-05T00:00:00Z'

authors: ['Anthony Etim', 'Jakub Szefer']
tags: ['Power Side-Channel Attacks', 'Machine Learning', 'Quantum Computing', 'Quantum Error Correction', 'Hardware Security']

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point:

# links:
#   - icon: link
#     icon_pack: fas
#     name: DOI
#     url: https://doi.org/10.1145/3857307.3857309

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
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
