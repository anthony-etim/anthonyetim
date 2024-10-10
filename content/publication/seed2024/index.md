---
title: "Extending FPGA Information Leaks with Trojan Phantom Circuits"
authors:
- admin
- Shanquan Tian
- Jakub Szefer

author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2023-12-15T00:00:00Z'
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Symposium on Secure and Private Execution Environment Design (SEED)"
publication_short: 

abstract: 'Field-Programmable Gate Arrays (FPGAs) are increasingly used in data centers and in cloud computing for acceleration of various applications. However, cloud-based FPGAs could be programmed with malicious circuits to leak information. For example, existing work has shown that long-wire crosstalk can be abused to leak information in cloud-based FPGAs. However, long-wire crosstalk is limited to very small spatial distances where the receiver needs to be located next to the transmitter or victim on the same FPGA. This work shows how long-wire crosstalk can be extended to cross-FPGA information leakage with a novel Trojan phantom circuit. The phantom circuit is a self-contained circuit, isolated from rest of the FPGA logic. It uses crosstalk to spy on information within an FPGA and then exfiltrates the information across FPGAs by triggering RO stressors for cross-FPGA information transmission. The tested accuracy of the phantom circuits cross-FPGA information leakage channel can reach 90%. In addition to demonstrating a new security threat, this work also presents the first set of active monitoring and defense mechanisms for protection from cross-FPGA information leakage.'

# Summary. An optional shortened abstract.
# summary: 

tags: [FPGA Security]
# - Source Themes
featured: false

# links:
# - name: URL
#   url: ""
url_pdf: 'https://caslab.io/publications/etim2024extending.pdf'
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
