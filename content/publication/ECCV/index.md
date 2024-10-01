+++
title = "Benchmarking Object Detectors with COCO: A New Path Forward"
date = 2024-03-27T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Shweta Singh", "Aayan Yadav", "Jitesh Jain", "Humphrey Shi", "Justin Johnson", "Karan Desai"]

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
publication = " European Conference on Computer Vision 2024"
publication_short = "ECCV 24"

# Abstract and optional shortened version.
abstract = "The Common Objects in Context (COCO) dataset has been instrumental in benchmarking object detectors over the past decade. Like every dataset, COCO contains subtle errors and imperfections stemming from its annotation procedure. With the advent of high-performing models, we ask whether these errors of COCO are hindering its utility in reliably benchmarking further progress. In search for an answer, we inspect thousands of masks from COCO (2017 version) and uncover different types of errors such as imprecise mask boundaries, non-exhaustively annotated instances, and mislabeled masks. Due to the prevalence of COCO, we choose to correct these errors to maintain continuity with prior research. We develop COCO-ReM (Refined Masks), a cleaner set of annotations with visibly better mask quality than COCO-2017. We evaluate fifty object detectors and find that models that predict visually sharper masks score higher on COCO-ReM, affirming that they were being incorrectly penalized due to errors in COCO-2017. Moreover, our models trained using COCO-ReM converge faster and score higher than their larger variants trained using COCO-2017, highlighting the importance of data quality in improving object detectors. With these findings, we advocate using COCO-ReM for future object detection research. Our dataset is available at https://cocorem.xyz"

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
url_pdf = "https://arxiv.org/pdf/2403.18819"
url_preprint = "https://arxiv.org/abs/2403.18819"
url_code = "https://github.com/kdexd/coco-rem"
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
