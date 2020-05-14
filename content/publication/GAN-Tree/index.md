+++
title = "GAN-Tree: An Incrementally Learned Hierarchical Generative Framework for Multi-Modal Data Distributions"
date = 2019-07-02T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jogendra Nath Kundu&ast;", "Maharshi Gor&ast;", "**Dakshit Agrawal**", "R. Venkatesh Babu"]

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
publication = "IEEE International Conference on Computer Vision 2019"
publication_short = "ICCV 2019"

# Abstract and optional shortened version.
abstract = "Despite the remarkable success of generative adversarial networks, their performance seems less impressive for diverse training sets, requiring learning of discontinuous mapping functions. Though multi-mode prior or multigenerator models have been proposed to alleviate this problem, such approaches may fail depending on the empirically chosen initial mode components. In contrast to such bottom-up approaches, we present GAN-Tree, which follows a hierarchical divisive strategy to address such discontinuous multi-modal data. Devoid of any assumption on the number of modes, GAN-Tree utilizes a novel modesplitting algorithm to effectively split the parent mode to semantically cohesive children modes, facilitating unsupervised clustering. Further, it also enables incremental addition of new data modes to an already trained GAN-Tree, by updating only a single branch of the tree structure. As compared to prior approaches, the proposed framework offers a higher degree of flexibility in choosing a large variety of mutually exclusive and exhaustive tree nodes called GANSet. Extensive experiments on synthetic and natural image datasets including ImageNet demonstrate the superiority of GAN-Tree against the prior state-of-the-art."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "iccv_fig.jpg"

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
url_preprint = "https://arxiv.org/abs/1908.03919v3"
url_code = "https://github.com/val-iisc/GANTree"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
# url_poster = "https://drive.google.com/file/d/1_2FftUxtxkJM4DkRpnlXUh6HbD3x4XGr/view?usp=sharing"
url_poster = "img/gan_tree_iccv_poster.pdf"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "iccv_fig.jpg"
caption = "GAN-Tree: An Incrementally Learned Hierarchical Generative Framework for Multi-Modal Data Distributions"

+++
