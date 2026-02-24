---
title: Fault Injection Attacks and Countermeasures on TinyML Algorithms

event: 2026 IEEE International Symposium on Hardware Oriented Security and Trust (HOST 2026)
event_url: https://host.conferences.computer.org/2026/

location: 2026 IEEE International Symposium on Hardware Oriented Security and Trust (HOST 2026)
address:
  street: 
  city: 
  region: Washington DC
  postcode: ''
  country: United States

summary: 
abstract: "TinyML algorithms, designed to operate on constrained devices such as those found in Internet of Things (IoT) systems, are vulnerable to adversarial threats, including fault injection attacks. These attacks exploit physical means to induce errors in computation, compromising the reliability of the device and the TinyML models running on it. This work studies the operation of TinyML models under fault injection attacks. Through systematic experimentation with voltage glitching fault injection attacks and EM fault injection attacks on microcontrollers, this work explores attack configurations that attackers can exploit to induce faults without triggering a system reset, which could result in practical attacks. This study analyzes four types of TinyML models, and demonstrates that all four evaluated TinyML models will generate inference outputs with reduced accuracy under the two types of physical fault injection attacks. Further, in some instances, it may be feasible for the attackers to use the fault to cause inference operations to return a predictable malicious output, not just random incorrect inference results. This highlights the need for more robust fault injection protection mechanisms in TinyML implementations. In order to provide one such protection, this work demonstrates use of random self-reductions and majority voting for intermediate values as a means to protect TinyML models."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-05-05T11:15:00Z'
date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2026-02-02T11:15:00Z'

authors: ['Anthony Etim']
tags: ['Fault Injection Attacks and Countermeasures, Machine Learning, TinyML']

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
