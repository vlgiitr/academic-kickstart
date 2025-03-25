+++
title = "LoRA Unlearns More and Retains More"
date = 2024-11-16T00:00:00
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
publication = "AAAI-25 Student Abstract"
publication_short = "AAAI-25 Student Abstract"

# Abstract and optional shortened version.
abstract = "Due to increasing privacy regulations and regulatory compliance, Machine Unlearning (MU) has become essential. The goal of unlearning is to remove information related to a specific class from a model. Traditional approaches achieve exact unlearning by retraining the model on the remaining dataset, but incur high computational costs. This has driven the development of more efficient unlearning techniques, including model sparsification techniques, which boost computational efficiency, but degrade the model's performance on the remaining classes. To mitigate these issues, we propose a novel method, PruneLoRA which introduces a new MU paradigm, termed prune first, then adapt, then unlearn. LoRA (Hu et al. 2022) reduces the need for large-scale parameter updates by applying low-rank updates to the model. We leverage LoRA to selectively modify a subset of the pruned model's parameters, thereby reducing the computational cost, memory requirements and improving the model's ability to retain performance on the remaining classes. Experimental Results across various metrics showcase that our method outperforms other approximate MU methods and bridges the gap between exact and approximate unlearning."

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
url_pdf = "https://arxiv.org/pdf/2411.11907v1"
url_preprint = "https://arxiv.org/abs/2411.11907v1"
url_code = "https://github.com/vlgiitr/LoRA-Unlearn"
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
