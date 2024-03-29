---
title: "Covert-channels in FPGA-enabled SmartSSDs"
authors:
- Theodoros Trochatos
- admin
- Jakub Szefer

author_notes:
- "Equal contribution"
- "Equal contribution"
date: '2023-12-04T00:00:00Z'
doi: 10.1145/3635312

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Reconfigurable Technology and Systems (TRETS)"
publication_short: 

abstract: 'Cloud computing providers today offer access to a variety of devices, which users can rent and access remotely in a shared setting. Among these devices are SmartSSDs, which a solid-state disks (SSD) augmented with an FPGA, enabling users to instantiate custom circuits within the FPGA, including potentially malicious circuits for power and temperature measurement. Normally, cloud users have no remote access to power and temperature data, but with SmartSSDs they could abuse the FPGA component to instantiate circuits to learn this information. Additionally, custom power waster circuits can be instantiated within the FPGA. This paper shows for the first time that by leveraging ring oscillator sensors and power wasters, numerous covert-channels in FPGA-enabled SmartSSDs could be used to transmit information. This work presents two channels in single-tenant setting (SmartSSD is used by one user at a time) and two channels in multi-tenant setting (FPGA and SSD inside SmartSSD is shared by different users). The presented covert channels can reach close to 100% accuracy. Meanwhile, bandwidth of the channels can be easily scaled by cloud users renting more SmartSSDs as the bandwidth of the covert channels is proportional to number of SmartSSD used.'

# Summary. An optional shortened abstract.
# summary: 

tags: [FPGA Security]
# - Source Themes
featured: false

# links:
# - name: URL
#   url: ""
url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3635312'
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
