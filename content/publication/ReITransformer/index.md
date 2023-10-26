+++
title = "RelTransformer: A Transformer-Based Long-Tail Visual Relationship Recognition"
date = 2022-03-29T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jun Chen", "Aniket Agarwal", "Sherif Abdelkarim", "Deyao Zhu", "Mohamed Elhoseiny"]

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
publication = "The Conference on Computer Vision and Pattern Recognition 2022"
publication_short = "CVPR'22"

# Abstract and optional shortened version.
abstract = "The visual relationship recognition (VRR) task aims at understanding the pairwise visual relationships between interacting objects in an image. This paper shows that modeling an effective message-passing flow through an attention mechanism can be critical to tackling the compositionality and long-tail challenges in VRR. The method, called RelTransformer, represents each image as a fully-connected scene graph and restructures the whole scene into the relation-triplet and global-scene contexts."
abstract_short = "The visual relationship recognition (VRR) task aims at understanding the pairwise visual relationships between interacting objects in an image. These relationships typically have a long-tail distribution due to their compositional nature. This problem gets more severe when the vocabulary becomes large, rendering this task very challenging. This paper shows that modeling an effective message-passing flow through an attention mechanism can be critical to tackling the compositionality and long-tail challenges in VRR. The method, called RelTransformer, represents each image as a fully-connected scene graph and restructures the whole scene into the relation-triplet and global-scene contexts. It directly passes the message from each element in the relation-triplet and global-scene contexts to the target relation via self-attention. We also design a learnable memory to augment the long-tail relation representation learning. Through extensive experiments, we find that our model generalizes well on many VRR benchmarks. Our model outperforms the best-performing models on two large-scale long-tail VRR benchmarks, VG8K-LT (+2.0% overall acc) and GQA-LT (+26.0% overall acc), both having a highly skewed distribution towards the tail. It also achieves strong results on the VG200 relation detection task."

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
url_pdf = "https://arxiv.org/pdf/2104.11934.pdf"
url_preprint = "https://arxiv.org/abs/2104.11934"
url_code = "https://github.com/Vision-CAIR/RelTransformer"
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
