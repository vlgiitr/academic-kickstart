+++
title = "Model Merging using Geometric Median of Task Vectors"
date = 2024-12-12T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Aakash Gupta", "Siddharth Gupta"]

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
publication = "Annual Conference on Neural Information Processing Systems 2024, NeurIPS"
publication_short = "NeurIPS 2024"

# Abstract and optional shortened version.
abstract = "Training high-performing large language models (LLMs) from scratch is an expensive and complex task. Model merging techniques offer a more computationally efficient alternative, where pretrained LLMs are fine-tuned on specific tasks and then combined to produce a versatile model capable of handling a broad range of tasks, including reasoning, coding, mathematics, conversation, and tool usage. Unlike traditional fine-tuning or ensemble methods, our approach to merging is less computationally intensive. We represent each fine-tuned model with a \"Task Vector\" relative to a pretrained \"Base LLM\" , derived from the LoRA (Low Rank Adaptation) weights of the fine-tuned models. By computing the geometric median of these task vectors in high-dimensional space using Weiszfeld’s iterative algorithm and adding it to the \"Base LLM\" weights, we create a unified model that generalizes effectively across tasks. This efficient method achieves state-of-the-art performance on benchmark tests while reducing computational demands"

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
url_pdf = "https://openreview.net/pdf?id=4VD2jMqJbN"
url_preprint = "https://openreview.net/forum?id=4VD2jMqJbN"
url_code = "https://github.com/iMmOrTaL2121/geometric_median_llm_merging"
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
