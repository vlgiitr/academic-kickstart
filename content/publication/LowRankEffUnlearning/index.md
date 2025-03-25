+++
title = "Low Rank Adaptations for Effective Machine Unlearning"
date = 2024-11-23T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Atharv Mittal"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Working paper
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "AAAI 2025 CoLoRAI Workshop"
publication_short = "AAAI 2025 CoLoRAI Workshop"

# Abstract and optional shortened version.
abstract = "Growing privacy regulations have made machine unlearning an essential process for removing the influence of specific data points from trained models. While retraining on the remaining dataset is a straightforward solution, it incurs high computational costs and requires access to the retained dataset, which may not always be practical. Existing unlearning methods, such as gradient ascent, often suffer from unstable optimization and catastrophic forgetting. Recent studies have demonstrated that by training fewer parameters, Low-Rank Adaptation (LoRA) constrains updates to prevent significant divergence from the base model, effectively mitigating catastrophic forgetting. Building on this insight, we propose a novel framework, NegLoRA that leverages LoRA to enhance the efficiency and effectiveness of machine unlearning. Experimental results across various metrics indicate that NegLoRA outperforms baseline methods in unlearning accuracy, generalization, and robustness to inference attacks while being computationally efficient."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning.md"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://openreview.net/pdf?id=AOj5DLBbdM"
url_preprint = "https://openreview.net/forum?id=AOj5DLBbdM"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# [header]
# image = "cache.png"
# caption = "DEAP Cache: Deep Eviction Admission and Prefetching for Cache"

+++
