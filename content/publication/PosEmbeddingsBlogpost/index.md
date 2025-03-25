+++
title = "Positional Embeddings in Transformer Models: Evolution from Text to Vision Domains"
date = 2025-01-23T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Abhinav Kumar" , "Adesh Gupta" , "Shivank Garg" , "Mansi Gupta"]

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
publication = "ICLR Blogpost track"
publication_short = "ICLR Blogpost"

# Abstract and optional shortened version.
abstract = "Positional encoding has become an essential element in transformer models, addressing their fundamental property of permutation invariance and allowing them to understand sequential relationships within data. This blog post examines positional encoding techniques, emphasizing their vital importance in traditional transformers and their use with 2D data in Vision Transformers (ViT). We explore two contemporary methods—ALiBi (Attention with Linear Biases) and RoPE (Rotary Position Embedding)—analyzing their unique approaches to tackling the challenge of sequence length extrapolation during inference, a significant issue for transformers. Additionally, we compare these methods' fundamental similarities and differences, assessing their impact on transformer performance across various fields. We also look into how interpolation strategies have been utilized to enhance the extrapolation capabilities of these methods; we conclude this blog with an empirical comparison of ALiBi and RoPE in Vision Transformers. To the best of our knowledge, this represents the first direct comparison of these positional encoding methods with those used in standard Vision Transformers."

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
url_pdf = ""
url_preprint = "https://d2jud02ci9yv69.cloudfront.net/2025-04-28-positional-embedding-19/blog/positional-embedding/"
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
