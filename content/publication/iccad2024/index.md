---
title: "Systematic Use of Random Self-Reducibility in Cryptographic Code against Physical Attacks"
authors:
- Ferhat Erata
- TingHung Chiu
- admin
- Srilalith Nampally
- Tejas Raju
- Rajashree Ramu
- Ruzica Piskac
- Timos Antonopoulos
- Wenjie Xiong
- Jakub Szefer

author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: '2024-10-09T00:00:00Z'
doi: 10.1145/3676536.3689920

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2024 ACM/IEEE International Conference on Computer-Aided Design (ICCAD)"
publication_short: 

abstract: 'This work presents a novel, black-box software-based countermeasure against physical attacks including power side-channel and fault-injection attacks. The approach uses the concept of random self-reducibility and self-correctness to add randomness and redundancy in the execution for protection. Our approach is at the operation level, is not algorithm-specific, and thus, can be applied for protecting a wide range of algorithms. The countermeasure isempirically evaluated against attacks over operations like modular exponentiation, modular multiplication, polynomial multiplication, and number theoretic transforms. An end-to-end implementation of this countermeasure is demonstrated for RSA-CRT signature algorithm and Kyber Key Generation public key cryptosystems. The countermeasure reduced the power side-channel leakage by two orders of magnitude, to an acceptably secure level in TVLA analysis. For fault injection, the countermeasure reduces the number of faults to 95.4% in average.'

# Summary. An optional shortened abstract.
# summary: 

tags: [Hardware Security, Hardware attacks and countermeasures]
# - Source Themes
featured: false

# links:
# - name: URL
#   url: ""
url_pdf: 'https://www.cs.yale.edu/homes/antonopoulos-timos/ICCAD-2024.pdf'
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
