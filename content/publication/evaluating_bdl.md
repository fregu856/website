+++
title = "Evaluating Scalable Bayesian Deep Learning Methods for Robust Computer Vision"
date = "2019-06-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Fredrik K. Gustafsson", "Martin Danelljan", "Thomas B. Schön"]

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
publication_types = ["8"]

# Publication name and optional abbreviated version.
publication = "Preprint, 2019"
publication_short = "Preprint, 2019"

# Abstract and optional shortened version.
abstract = "While Deep Neural Networks (DNNs) have become the go-to approach in computer vision, the vast majority of these models fail to properly capture the uncertainty inherent in their predictions. Estimating this predictive uncertainty can be crucial, for instance in automotive applications. In Bayesian deep learning, predictive uncertainty is often decomposed into the distinct types of aleatoric and epistemic uncertainty. The former can be estimated by letting a DNN output the parameters of a probability distribution. Epistemic uncertainty estimation is a more challenging problem, and while different scalable methods recently have emerged, no comprehensive comparison has been performed in a real-world setting. We therefore accept this task and propose an evaluation framework for predictive uncertainty estimation that is specifically designed to test the robustness required in real-world computer vision applications. Using the proposed framework, we perform an extensive comparison of the popular ensembling and MC-dropout methods on the tasks of depth completion and street-scene semantic segmentation. Our comparison suggests that ensembling consistently provides more reliable uncertainty estimates."

abstract_short = "We propose an evaluation framework for predictive uncertainty estimation that is specifically designed to test the robustness required in real-world computer vision applications. Using the framework, we perform an extensive comparison of the popular ensembling and MC-dropout methods on the tasks of depth completion and street-scene semantic segmentation. Our comparison suggests that ensembling consistently provides more reliable uncertainty estimates."

# Featured image thumbnail (optional)
image_preview = "evaluating_bdl__.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/1906.01620"
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/fregu856/evaluating_bdl"
url_dataset = ""
url_project = ""
url_video = "https://youtu.be/CabPVqtzsOI"
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
#small_image = "thesis_color.png" # (header image the same size as the article)
video="https://www.youtube.com/embed/CabPVqtzsOI?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++