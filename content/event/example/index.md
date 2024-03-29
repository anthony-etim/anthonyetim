---
title: Extending FPGA Information Leaks with Trojan Phantom Circuits

event: 2024 International Symposium on Secure and Private Execution Environment Design (SEED 2024)
event_url: https://seed-symposium.org/2024/

location: 2024 International Symposium on Secure and Private Execution Environment Design (SEED 2024)
address:
  street: 
  city: Orlando
  region: FL
  postcode: ''
  country: United States

summary: 
abstract: 'Field-Programmable Gate Arrays (FPGAs) are increasingly used in data centers and in cloud computing for acceleration of various applications. However, cloud-based FPGAs could be programmed with malicious circuits to leak information. For example, existing work has shown that long-wire crosstalk can be abused to leak information in cloud-based FPGAs. However, long-wire crosstalk is limited to very small spatial distances where the receiver needs to be located next to the transmitter or victim. This work shows how long-wire crosstalk can be extended to cross-FPGA information leakage with a novel Trojan phantom circuit. The phantom circuit is a self-contained circuit, isolated from other FPGA logic using a Ring Oscillator (RO) as a clock source. It uses crosstalk to spy on information and then amplifies the range of information leakage by triggering RO stressors for cross-FPGA information transmission with accuracy above 90%. In addition to demonstrating a new security threat, this work also presents the first set of active monitoring and defense mechanisms for protection from cross-FPGA information leakage.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-05-17T13:00:00Z'
date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-03-16T00:00:00Z'

authors: ['Anthony Etim']
tags: ['FPGA Security']

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
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
