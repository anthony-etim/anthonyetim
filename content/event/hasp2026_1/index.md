---
title: Voltage Fault Injection Against On-Device Language Models

event: 2026 International Workshop on Hardware and Architectural Support for Security and Privacy (HASP 2026)
event_url: https://www.haspworkshop.org/2026/index.html

location: 2026 International Workshop on Hardware and Architectural Support for Security and Privacy (HASP 2026)
address:
  street:
  city: Athens
  region: Attica
  postcode: ''
  country: Greece

summary:
abstract: "Transformer-based language models are increasingly deployed on resource-constrained edge devices, raising new security concerns when attackers have physical access to the underlying hardware. This paper investigates the susceptibility of on-device transformer language models to voltage fault injection attacks. We present a stage-level characterization of crowbar voltage glitches against a 4,192-parameter autoregressive transformer with a key-value (KV) cache running on an Arm Cortex-M4 microcontroller. Using stage-selectable triggers, on-device cycle measurements, and automated fault-parameter exploration, we analyze the effects of voltage glitches across six regions of the model's forward pass. Across 3,300 fault-injection attempts at selected timing offsets, each evaluated stage exhibits non-crash anomalies, with the highest observed anomaly rates ranging from 43.0% to 99.7% depending on the stage. Additional experiments characterize the impact of glitch strength and input-dependent execution timing, demonstrating that effective injection parameters can vary across prompts. We also evaluate a temporal redundancy-based countermeasure that restores the precomputation state, recomputes model outputs with fault triggers disabled, and compares the resulting logits. Across 6,100 evaluated defense attempts, no silent emitted-token changes are observed under the tested conditions. We further distinguish between detected anomalies, actual token-output changes, device crashes, and subsequent text-generation divergence. These findings highlight physical fault-injection risks in embedded language models and motivate lightweight fault detection and redundancy mechanisms for secure on-device inference."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with #.
date: '2026-10-31T12:40:00Z'
date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2026-11-05T00:00:00Z'

authors: ['Anthony Etim', 'Jakub Szefer']
tags: ['Voltage Fault Injection', 'Machine Learning', 'Language Models', 'Transformers', 'Hardware Security', 'Embedded Systems']

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point:

# links:
#   - icon: link
#     icon_pack: fas
#     name: DOI
#     url: https://doi.org/10.1145/3857307.3857310

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
