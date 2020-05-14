+++
title = "Revisiting CycleGAN for Semi-Supervised Segmentation"
date = 2019-11-03T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Arnab Kumar Mondal", "Aniket Agarwal", "Jose Dolz", "Christain Desrosiers"]

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
publication = "arXiv preprint, Submitted to WACV 2020"
publication_short = "arXiv preprint, Submitted to WACV 2020"

# Abstract and optional shortened version.
abstract = "In this work, we study the problem of training deep networks for semantic image segmentation using only a fraction of annotated images, which may significantly reduce human annotation efforts. Particularly, we propose a strategy that exploits the unpaired image style transfer capabilities of CycleGAN in semi-supervised segmentation. Unlike recent works using adversarial learning for semi-supervised segmentation, we enforce cycle consistency to learn a bidirectional mapping between unpaired images and segmentation masks. This adds an unsupervised regularization effect that boosts the segmentation performance when annotated data is limited. Experiments on three different public segmentation benchmarks (PASCAL VOC 2012, Cityscapes and ACDC) demonstrate the effectiveness of the proposed method. The proposed model achieves 2-4% of improvement with respect to the baseline and outperforms recent approaches for this task, particularly in low labeled data regime."

abstract_short = ""

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
#url_pdf = "https://dl.acm.org/citation.cfm?doid=3242969.3264985"
url_preprint = "https://arxiv.org/abs/1908.11569"
url_code = "https://github.com/arnab39/Semi-supervised-segmentation-cycleGAN"
#url_dataset = ""
#url_project = ""
#url_slides = "https://drive.google.com/file/d/1ArxcgCwuP9pz7hd_mTspkWfo7QPs5A3w/view?usp=sharing"
#url_slides = "img/Presentation_EmotiW.pdf"
#url_video = ""
#url_poster = "https://drive.google.com/file/d/14cS5vWA0i1a2xCkBqfJcHssFYE_iXWUJ/view?usp=sharing"
#url_poster = "img/Poster_EmotiW.pdf"
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "icmi_fig.jpg"
caption = "An Attention Model for Group Level Emotion Recognition"

+++
