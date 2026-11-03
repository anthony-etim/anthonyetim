---
title: "Voltage Fault Injection Against On-Device Language Models"
authors:
- admin
- Jakub Szefer

author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: '2026-05-04T00:00:00Z'
doi: 10.1145/3857307.3857310

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

abstract: 'Small transformer language models are today able to run on microcontrollers, where an attacker with physical access can disturb the supply voltage during text generation. Fault injection studies of neural networks in the past have mostly targeted classifiers and modeled the attacker as flipping a chosen bit of a chosen parameter. A voltage fault injection is instead aimed at corrupting whatever the processor is executing and targets the execution of the model. This work characterizes voltage fault injection against a 4,192-parameter autoregressive transformer with a key–value (KV) cache on an Arm Cortex-M4. The language model is augmented with triggers that mark six stages of the forward pass, and the work searches each stage for timing offsets that cause faults. Every stage is found to have an offset at which 43.0% to 99.7% of voltage fault injection glitches produce an anomaly without a crash. The vulnerable offsets depend on the input: on one prompt an offset in the feed-forward network, or multilayer perceptron (MLP), faulted on 299 of 300 attempts, yet on a second prompt it produced no anomalies while other MLP offsets became vulnerable. A single glitch can also leave the current token unchanged and change a later one, consistent with corrupted state carried between tokens. Finally, this work evaluates temporal redundancy that recomputes each token and compares all logits, assuming the recomputation is not itself faulted. No glitch in 6,100 attempts changed the emitted token without an alarm, but at the MLP offset the check alarmed on 299 of 300 attempts that left the output unchanged. These results suggest that defenses for on-device language models should protect the computation in every stage and the state carried between tokens, not only the stored weights.'

# Summary. An optional shortened abstract.
# summary: 

tags: [Fault injection attacks, Embedded machine learning, LLMs]
# - Source Themes
featured: false

# links:
# - name: URL
#   url: ""
url_pdf: 'https://dl.acm.org/doi/epdf/10.1145/3857307.3857310'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: '/publication/hasp2026_1/hasp_2026_1_slides.pptx'
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
