---
title: Fault Injection Attacks on Machine Learning-based Quantum Computer Readout Error Correction

event: QCCS 2025 3rd Annual Quantum Computer Cybersecurity Symposium
event_url: https://caslab.io/events/qccs/index.html

location: QCCS 2025 3rd Annual Quantum Computer Cybersecurity Symposium
address:
  street: 
  city: Evanston
  region: IL
  postcode: ''
  country: United States

summary: 
abstract: "Machine-learning (ML) classifiers are increasingly used in quantum computing systems to improve multi-qubit readout discrimination and to mitigate correlated readout errors. These ML classifiers are an integral component of today's quantum computer's control and readout stacks. This paper is the first to analyze the susceptibility of such ML classifiers to physical fault-injection which can result in generation of incorrect readout results from quantum computers. The study targets 5-qubit (thus 32-class) readout error-correction model. Using the ChipWhisperer Husky for physical voltage glitching, this work leverages an automated algorithm for scanning the fault injection parameter search space to find various successful faults in all the layers of the target ML model. Across repeated trials, this work finds that fault susceptibility is strongly layer-dependent: early-layers demonstrate higher rates of misprediction when faults are triggered in them, whereas later layers have smaller misprediction rates. This work further characterizes the resulting readout failures at the bitstring level using Hamming-distance and per-bit flip statistics, showing that single-shot glitches can induce structured readout corruption rather than purely random noise. These results motivate treating ML-based quantum computer readout and readout correction as a security-critical component of quantum systems and highlight the need for lightweight, deployment-friendly fault detection and redundancy mechanisms in the quantum computer readout pipelines."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-11-06T11:15:00Z'
date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-11-06T11:15:00Z'

authors: ['Anthony Etim']
tags: ['Quantum Computer Security']

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
