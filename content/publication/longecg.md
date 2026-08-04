+++
title = "Extending Pretrained 10-Second ECG Foundation Models to Longer Horizons"
date = "2026-05-16"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wei Tang, Jinpei Han, Kangning Cui, Mattia Carletti, **Fredrik K. Gustafsson**, Shreyank N Gowda, Patitapaban Palo, Anshul Thakur, Lei Clifton, Jean-michel Morel, Raymond H. Chan, David A. Clifton, Xiao Gu"]

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
abstract = "Electrocardiogram (ECG) foundation models pretrained on typical diagnostic 10-second ECG segments, have demonstrated strong transferability across a range of clinical applications. However, many real-world applications produce recordings that are typically longer, and are varied in duration during inference time. These 10-second models have no built-in way to combine information across time. Extending them to longer horizons introduces two challenges: structural incompatibilities arising from input-length disparities, and semantic challenges that limit meaningful temporal aggregation. We propose a parameter-efficient framework that extends pretrained ECG foundation models to longer and variable-length ECGs without retraining the backbone. Guided by a frozen pretrained 10-second model, we introduce a lightweight plug-in module that extends the model in two complementary ways: (i) structurally compatible long-sequence processing and (ii) semantically informed temporal modeling. Experiments on multiple long-horizon ECG tasks, datasets, and foundation model backbones demonstrate that our method enables robust long-horizon extension from pretrained snapshot models, consistently outperforming sliding-window and pooling-based baselines with strong parameter efficiency."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "longecg.png"

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2605.16975"
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
#image="thesis_color.png" # (full-width header image)
small_image = "longecg.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
