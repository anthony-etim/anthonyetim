---
title: "Fault Injection Attacks and Countermeasures on TinyML Algorithms"
authors:
- admin
- Srilalith Nampally
- Aubtin Rasouli
- Dustin Mazza
- Krishna Chilakapati
- Tinghung Chiu
- Ferhat Erata
- Leyla Nazhandali
- Wenjie Xiong 
- Jakub Szefer

author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2026-05-04T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2026 IEEE International Symposium on Hardware Oriented Security and Trust (HOST)"
publication_short: 

abstract: 'TinyML algorithms, designed to operate on constrained devices such as those found in Internet of Things (IoT) systems, are vulnerable to adversarial threats, including fault injection attacks. These attacks exploit physical means to induce errors in computation, compromising the reliability of the device and the TinyML models running on it. This work studies the operation of TinyML models under fault injection attacks. Through systematic experimentation with voltage glitching fault injection attacks and EM fault injection attacks on microcontrollers, this work explores attack configurations that attackers can exploit to induce faults without triggering a system reset, which could result in practical attacks. This study analyzes four types of TinyML models, and demonstrates that all four evaluated TinyML models will generate inference outputs with reduced accuracy under the two types of physical fault injection attacks. Further, in some instances, it may be feasible for the attackers to use the fault to cause inference operations to return a predictable malicious output, not just random incorrect inference results. This highlights the need for more robust fault injection protection mechanisms in TinyML implementations. In order to provide one such protection, this work demonstrates use of random self-reductions and majority voting for intermediate values as a means to protect TinyML models.'

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
