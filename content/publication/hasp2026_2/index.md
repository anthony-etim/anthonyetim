---
title: "Power Side-Channel Attacks on Machine-Learning-based Quantum Error Correction Decoders"
authors:
- admin
- Jakub Szefer

author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: '2026-05-03T00:00:00Z'
doi: 10.1145/3857307.3857309

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: " International Workshop on Hardware and Architectural Support for Security and Privacy (HASP), 2026"
publication_short: 

abstract: 'Machine learning (ML) decoders are increasingly used in quantum error correction (QEC) to model noise, analyze imperfect syndrome measurements, and replace iterative matching algorithms with a learned inference pass, making them a critical component of the classical control stack of a fault-tolerant quantum computer. Prior security analysis of the ML decoders in the controller stack has addressed integrity and fault-injection attacks on the decoders. This work is the first to explore physical power side-channel attacks on ML decoders. In particular, it studies a convolutional Deep Q- Learning decoder for the distance-5 surface code. This work profiles the decoder to capture the power signatures generated during clas- sification tasks and trains a classifier to identify which qubit the decoder identified as having errors based on the power signatures. The trained classifier is then applied to test data, where it recovers the correct data qubit label from the decoder’s side-channel data with up to 83.2% accuracy across 25 classes, against 4% for random guessing. A second classifier is trained to identify the type of error labeled by the decoder, Pauli X or Z, and reaches 84.6% accuracy, against 50% for random guessing. This work further performs an initial study of a timing channel, which complements the power side channels, exploring how the duration of the decoder’s first convolutional layer can leak the code size for which the decoder is compiled. All the side-channel attacks demonstrated in this work motivate treating the embedded QEC decoder as a confidentiality-critical component of the quantum control stack.'

# Summary. An optional shortened abstract.
# summary: 

tags: [Power side-channels, Machine learning, Quantum error correction]
# - Source Themes
featured: false

# links:
# - name: URL
#   url: ""
url_pdf: 'https://dl.acm.org/doi/epdf/10.1145/3857307.3857309'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: '/publication/hasp2026_2/hasp_2026_2_slides.pptx'
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
