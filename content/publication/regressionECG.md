+++
title = "ECG-Based Electrolyte Prediction: Evaluating Regression and Probabilistic Methods"
date = "2022-12-21"

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
publication_types = ["8"]

# Publication name and optional abbreviated version.
publication = "Preprint, 2022"
publication_short = "Preprint, 2022"

# Abstract and optional shortened version.
abstract = "Objective: Imbalances of the electrolyte concentration levels in the body can lead to catastrophic consequences, but accurate and accessible measurements could improve patient outcomes. While blood tests provide accurate measurements, they are invasive and the laboratory analysis can be slow or inaccessible. In contrast, an electrocardiogram (ECG) is a widely adopted tool which is quick and simple to acquire. However, the problem of estimating continuous electrolyte concentrations directly from ECGs is not well-studied. We therefore investigate if regression methods can be used for accurate ECG-based prediction of electrolyte concentrations. Methods: We explore the use of deep neural networks (DNNs) for this task. We analyze the regression performance across four electrolytes, utilizing a novel dataset containing over 290000 ECGs. For improved understanding, we also study the full spectrum from continuous predictions to binary classification of extreme concentration levels. To enhance clinical usefulness, we finally extend to a probabilistic regression approach and evaluate different uncertainty estimates. Results: We find that the performance varies significantly between different electrolytes, which is clinically justified in the interplay of electrolytes and their manifestation in the ECG. We also compare the regression accuracy with that of traditional machine learning models, demonstrating superior performance of DNNs. Conclusion: Discretization can lead to good classification performance, but does not help solve the original problem of predicting continuous concentration levels. While probabilistic regression demonstrates potential practical usefulness, the uncertainty estimates are not particularly well-calibrated. Significance: Our study is a first step towards accurate and reliable ECG-based prediction of electrolyte concentration levels."

abstract_short = "Imbalances of the electrolyte concentration levels in the body can lead to catastrophic consequences, but accurate and accessible measurements could improve patient outcomes. While blood tests provide accurate measurements, they are invasive and the laboratory analysis can be slow or inaccessible. In contrast, an ECG is a widely adopted tool which is quick and simple to acquire. However, the problem of estimating continuous electrolyte concentrations directly from ECGs is not well-studied. We therefore investigate if regression methods can be used for ECG-based prediction of electrolyte concentrations."

# Featured image thumbnail (optional)
image_preview = "regressionECG.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2212.13890"
url_pdf = ""
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
small_image = "regressionECG.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
