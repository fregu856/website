+++
title = "Evaluating Computational Pathology Foundation Models for Prostate Cancer Grading under Distribution Shifts"
date = "2024-10-10"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Fredrik K. Gustafsson**, Mattias Rantalainen"]

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
publication = "Preprint, 2024"
publication_short = "Preprint, 2024"

# Abstract and optional shortened version.
abstract = "Foundation models have recently become a popular research direction within computational pathology. They are intended to be general-purpose feature extractors, promising to achieve good performance on a wide range of downstream tasks. Real-world pathology image data does however exhibit considerable variability. Foundation models should be robust to these variations and other distribution shifts which might be encountered in practice. We evaluate two computational pathology foundation models: UNI (trained on more than 100,000 whole-slide images) and CONCH (trained on more than 1.1 million image-caption pairs), by utilizing them as feature extractors within prostate cancer grading models. We find that while UNI and CONCH perform well relative to baselines, the absolute performance can still be far from satisfactory. The fact that foundation models have been trained on large and varied datasets does not guarantee that downstream models always will be robust to common distribution shifts."

abstract_short = "Foundation models (FMs) are intended to be general-purpose feature extractors. Real-world pathology image data does however exhibit considerable variability. FMs should be robust to these variations and other distribution shifts which might be encountered in practice. We evaluate two computational pathology FMs (UNI and CONCH), by utilizing them as feature extractors within prostate cancer grading models. We find that while FMs perform well relative to baselines, the absolute performance can still be far from satisfactory. The fact that FMs have been trained on large and varied datasets does not guarantee that downstream models always will be robust to common distribution shifts."

# Featured image thumbnail (optional)
image_preview = "cpath_fms_shifts.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2410.06723"
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_video_90sec = ""
url_slides_90sec = ""
url_video = ""
url_slides = "/files/talk_241016_slides.pdf"
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
#image="cpath_fms_shifts.png" # (full-width header image)
small_image = "cpath_fms_shifts.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
