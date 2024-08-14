+++
title = "Evaluating Regression and Probabilistic Methods for ECG-Based Electrolyte Prediction"
date = "2024-07-03"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Philipp Von Bachmann, Daniel Gedon, **Fredrik K. Gustafsson**, Antônio H. Ribeiro, Erik Lampa, Stefan Gustafsson, Johan Sundström, Thomas B. Schön"]

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
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Scientific Reports, 2024"
publication_short = "Scientific Reports, 2024"

# Abstract and optional shortened version.
abstract = "Imbalances in electrolyte concentrations can have severe consequences, but accurate and accessible measurements could improve patient outcomes. The current measurement method based on blood tests is accurate but invasive and time-consuming and is often unavailable for example in remote locations or an ambulance setting. In this paper, we explore the use of deep neural networks (DNNs) for regression tasks to accurately predict continuous electrolyte concentrations from electrocardiograms (ECGs), a quick and widely adopted tool. We analyze our DNN models on a novel dataset of over 290,000 ECGs across four major electrolytes and compare their performance with traditional machine learning models. For improved understanding, we also study the full spectrum from continuous predictions to a binary classification of extreme concentration levels. Finally, we investigate probabilistic regression approaches and explore uncertainty estimates for enhanced clinical usefulness. Our results show that DNNs outperform traditional models but model performance varies significantly across different electrolytes. While discretization leads to good classification performance, it does not address the original problem of continuous concentration level prediction. Probabilistic regression has practical potential, but our uncertainty estimates are not perfectly calibrated. Our study is therefore a first step towards developing an accurate and reliable ECG-based method for electrolyte concentration level prediction — a method with high potential impact within multiple clinical scenarios."

abstract_short = "Imbalances in electrolyte concentrations can have severe consequences, but accurate and accessible measurements could improve patient outcomes. The current measurement method based on blood tests is accurate but invasive and time-consuming, and is often unavailable e.g. in remote locations or an ambulance setting. In contrast, an ECG is a widely adopted tool which is quick and simple to acquire. The problem of estimating continuous electrolyte concentrations directly from ECGs is however not well-studied. We therefore investigate if DNN regression models can be used for ECG-based prediction of electrolyte concentrations, utilizing a novel dataset of over 290,000 ECGs."

# Featured image thumbnail (optional)
image_preview = "regECG.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = ""
url_pdf = "https://www.nature.com/articles/s41598-024-65223-w"
url_preprint = ""
url_code = "https://github.com/philippvb/ecg-electrolyte-regression"
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
small_image = "regECG.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
