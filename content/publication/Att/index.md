+++
title = "An Attention Model for Group Level Emotion Recognition"
date = 2018-08-02T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Aarush Gupta&ast;**", "**Dakshit Agrawal&ast;**", "Hardik Chauhan", "Jose Dolz", "Marco Pedersoli"]

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
publication = "ACM International Conference on Multimodal Interaction 2018"
publication_short = "ICMI 2018"

# Abstract and optional shortened version.
abstract = "In this paper we propose a new approach for classifying the global emotion of images containing groups of people. To achieve this task, we consider two different and complementary sources of information: i) a global representation of the entire image (ii) a local representation where only faces are considered. While the global representation of the image is learned with a convolutional neural network (CNN), the local representation is obtained by merging face features through an attention mechanism. The two representations are first learned independently with two separate CNN branches and then fused through concatenation in order to obtain the final group-emotion classifier. For our submission to the EmotiW 2018 group-level emotion recognition challenge, we combine several variations of the proposed model into an ensemble, obtaining a final accuracy of 64.83% on the test set and ranking 4th among all challenge participants."

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
url_pdf = "https://dl.acm.org/citation.cfm?doid=3242969.3264985"
url_preprint = "https://arxiv.org/abs/1807.03380v1"
url_code = "https://github.com/vlgiitr/Group-Level-Emotion-Recognition"
url_dataset = ""
url_project = ""
#url_slides = "https://drive.google.com/file/d/1ArxcgCwuP9pz7hd_mTspkWfo7QPs5A3w/view?usp=sharing"
url_slides = "img/Presentation_EmotiW.pdf"
url_video = ""
#url_poster = "https://drive.google.com/file/d/14cS5vWA0i1a2xCkBqfJcHssFYE_iXWUJ/view?usp=sharing"
url_poster = "img/Poster_EmotiW.pdf"
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
[header]
image = "icmi_fig.jpg"
caption = "An Attention Model for Group Level Emotion Recognition"

+++