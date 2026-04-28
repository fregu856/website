+++
title = "Evaluating Deep Regression Models for WSI-Based Gene-Expression Prediction"
date = "2024-10-01"

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
abstract = "Prediction of mRNA gene-expression profiles directly from routine whole-slide images (WSIs) using deep learning models could potentially offer cost-effective and widely accessible molecular phenotyping. While such WSI-based gene-expression prediction models have recently emerged within computational pathology, the high-dimensional nature of the corresponding regression problem offers numerous design choices which remain to be analyzed in detail. This study provides recommendations on how deep regression models should be trained for WSI-based gene-expression prediction. For example, we conclude that training a single model to simultaneously regress all 20530 genes is a computationally efficient yet very strong baseline."

#abstract_short = "Gene-expression profiling is central to precision oncology but is not universally accessible. We systematically evaluate deep regression models for WSI-based gene-expression prediction, finding that direct regression using ABMIL provides a strong and efficient baseline, with no consistent benefit from training multiple models on gene subsets. We externally validate this approach on a cohort of 997 breast cancer patients, with good performance for gene sets such as PAM50. Predicted gene-expression scores also retain prognostic value across two independent survival cohorts of 4,172 patients. These results show that WSI-based gene-expression prediction captures clinically meaningful molecular structure, supporting its potential for scalable transcriptomic phenotyping."
abstract_short = "Prediction of mRNA gene-expression profiles directly from routine WSIs using deep learning models could potentially offer cost-effective and widely accessible molecular phenotyping. While such WSI-based gene-expression prediction models have recently emerged, the high-dimensional nature of the corresponding regression problem offers numerous design choices which remain to be analyzed in detail. We provide recommendations on how deep regression models should be trained for WSI-based gene-expression prediction. For example, we conclude that training a single model to simultaneously regress all 20530 genes is a computationally efficient yet very strong baseline."

# Featured image thumbnail (optional)
image_preview = "gene-exp.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2410.00945"
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_video_90sec = ""
url_slides_90sec = ""
url_video = ""
url_slides = ""
url_poster = "/files/gene-exp_poster.pdf"
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
small_image = "gene-exp.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
