---
title: "Fault Attacks on ML-based Quantum Control and Error Correction"
authors:
- admin
- Jakub Szefer

author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: '2026-05-04T00:00:00Z'
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2026 IEEE International Conference on Quantum Computing and Engineering (QCE)"
publication_short: 

abstract: 'Machine-learning (ML) models are increasingly used in quantum computing systems to discriminate multi-qubit readouts, mitigate correlated readout errors, and decode quantum error-correcting codes, making them an integral component of today''s quantum computer control and readout stacks. This paper is the first to analyze the susceptibility of such ML models to physical fault injection, which can cause quantum computers to return incorrect results or perform wrong error correction operation. This work studies two representative architectures: (i) a fully connected neural network for 5-qubit (32-class) readout error correction (HERQULES), and (ii) a convolutional neural network used as a Deep Q-learning (Deep Q) decoder for the distance-5 Surface Code. Using the ChipWhisperer Husky for voltage glitching together with automated search over the fault parameter space, this work localizes successful fault settings to specific layers of each target model. On the HERQULES model, fault susceptibility is strongly layer-dependent: early layers exhibit higher misprediction rates than later layers. On the Deep Q decoder, a single trigger-aligned voltage glitch in either the first convolutional layer or the final fully connected output layer reduces decoding accuracy from 100% to as low as 21.57%. We further characterize the resulting failures at the bitstring level using Hamming-distance and per-bit flip statistics, showing that single-shot glitches can induce structured corruption rather than purely random noise. These results motivate treating ML-based quantum readout and error-correction decoding as security-critical components, and highlight the need for lightweight fault-detection and redundancy mechanisms in quantum computing pipelines.'

# Summary. An optional shortened abstract.
# summary: 

tags: [Fault Injection Attacks and Countermeasures, Machine Learning, TinyML]
# - Source Themes
featured: false

# links:
# - name: URL
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption:  ''
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
