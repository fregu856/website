+++
title = "Benchmarking Pathology Foundation Models for Breast Cancer Survival Prediction"
date = "2026-04-28"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Fredrik K. Gustafsson**, Constance Boissin, Johan Vallon-Christersson, David&nbsp;A.&nbsp;Clifton, Mattias Rantalainen"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
# 7 = Thesis
# 8 = Preprint
# 9 = Extended abstract
publication_types = ["8"]

# Publication name and optional abbreviated version.
publication = "Preprint, 2026"
publication_short = "Preprint, 2026"

# Abstract and optional shortened version.
abstract = "Pathology foundation models (PFMs) have recently emerged as powerful pretrained encoders for computational pathology, enabling transfer learning across a wide range of downstream tasks. However, systematic comparisons of these models for clinically meaningful prediction problems remain limited, especially in the context of survival prediction under external validation. In this study, we benchmark widely used and recently proposed PFMs for breast cancer survival prediction from whole-slide histopathology images. Using a standardized pipeline based on patch-level feature extraction and a unified survival modeling framework, we evaluate model representations across three independent clinical cohorts comprising more than 5,400 patients with long-term follow-up. Models are trained on one cohort and evaluated on two independent external cohorts, enabling a rigorous assessment of cross-dataset generalization. Overall, H-optimus-1 achieves the strongest survival prediction performance. More broadly, we observe consistent generational improvements across model families, with second-generation PFMs outperforming their first-generation counterparts. However, absolute performance differences between many recent PFMs remain modest, suggesting diminishing returns from further scaling of pretraining data or model size alone. Notably, the compact distilled model H0-mini slightly outperforms its larger teacher model H-optimus-0, despite using fewer than 8% of the parameters and enabling significantly faster feature extraction. Together, these results provide the first large-scale, externally validated benchmark of PFMs for breast cancer survival prediction, and offer practical guidance for efficient deployment of PFMs in clinical workflows."

abstract_short = "Pathology foundation models (PFMs) are central to computational pathology, yet systematic comparisons for clinically meaningful prediction tasks remain limited. We benchmark 12 PFMs for survival prediction from WSIs across three independent cohorts with over 5,400 breast cancer patients. H-optimus-1 achieves the best overall performance, but differences between many recent PFMs are small, suggesting diminishing returns from further scaling of pretraining data or model size alone. Notably, the compact distilled model H0-mini slightly outperforms its larger teacher model, despite using fewer than 8% of the parameters. Overall, this work provides the first large-scale, externally validated benchmark of PFMs for breast cancer survival prediction."

# Featured image thumbnail (optional)
image_preview = "pfms_survival.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2604.24679"
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_video_90sec = ""
url_slides_90sec = ""
url_video = ""
url_slides = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "arXiv", url = "http://www.fregu856.com/"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image="signalmc-med4.png" # (full-width header image)
small_image = "pfms_survival.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
