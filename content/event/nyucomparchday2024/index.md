---
title: Covert-channels in FPGA-enabled SmartSSDs

event: NYU Computer Architecture Day 2024
event_url: https://baahl-nyu.github.io/nyucomparchday2024/

location: NYU Computer Architecture Day 2024
address:
  street: 
  city: Brooklyn
  region: New York
  postcode: ''
  country: United States

summary: 
abstract: 'Cloud computing providers today offer access to a variety of devices, which users can rent and access remotely in a shared setting. Among these devices are SmartSSDs, which a solid-state disks (SSD) augmented with an FPGA, enabling users to instantiate custom circuits within the FPGA, including potentially malicious circuits for power and temperature measurement. Normally, cloud users have no remote access to power and temperature data, but with SmartSSDs they could abuse the FPGA component to instantiate circuits to learn this information. Additionally, custom power waster circuits can be instantiated within the FPGA. This paper shows for the first time that by leveraging ring oscillator sensors and power wasters, numerous covert-channels in FPGA-enabled SmartSSDs could be used to transmit information. This work presents two channels in single-tenant setting (SmartSSD is used by one user at a time) and two channels in multi-tenant setting (FPGA and SSD inside SmartSSD is shared by different users). The presented covert channels can reach close to 100% accuracy. Meanwhile, bandwidth of the channels can be easily scaled by cloud users renting more SmartSSDs as the bandwidth of the covert channels is proportional to number of SmartSSD used.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-03-22T16:00:00Z'
date_end: '2024-03-22T16:15:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-03-23T16:00:00Z'

authors: ['Anthony Etim']
tags: ['FPGA Security']

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
