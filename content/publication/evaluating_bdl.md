+++
title = "Evaluating Scalable Bayesian Deep Learning Methods for Robust Computer Vision"
date = "2019-06-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Fredrik K. Gustafsson**", "Martin Danelljan", "Thomas B. Schön"]

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
# 10 = Workshop paper
publication_types = ["1"]

# Publication name and optional abbreviated version.
#publication = "Preprint, 2019"
#publication_short = "Preprint, 2019"
#publication = "NeurIPS Bayesian Deep Learning Workshop, 2019"
#publication_short = "NeurIPS Bayesian Deep Learning Workshop, 2019"
publication = "The IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPR Workshops), 2020"
publication_short = "CVPR Workshops, 2020"

# Abstract and optional shortened version.
abstract = "While deep neural networks have become the go-to approach in computer vision, the vast majority of these models fail to properly capture the uncertainty inherent in their predictions. Estimating this predictive uncertainty can be crucial, for example in automotive applications. In Bayesian deep learning, predictive uncertainty is commonly decomposed into the distinct types of aleatoric and epistemic uncertainty. The former can be estimated by letting a neural network output the parameters of a certain probability distribution. Epistemic uncertainty estimation is a more challenging problem, and while different scalable methods recently have emerged, no extensive comparison has been performed in a real-world setting. We therefore accept this task and propose a comprehensive evaluation framework for scalable epistemic uncertainty estimation methods in deep learning. Our proposed framework is specifically designed to test the robustness required in real-world computer vision applications. We also apply this framework to provide the first properly extensive and conclusive comparison of the two current state-of-the-art scalable methods: ensembling and MC-dropout. Our comparison demonstrates that ensembling consistently provides more reliable and practically useful uncertainty estimates."
#abstract = "While Deep Neural Networks (DNNs) have become the go-to approach in computer vision, the vast majority of these models fail to properly capture the uncertainty inherent in their predictions. Estimating this predictive uncertainty can be crucial, e.g. in automotive applications. In Bayesian deep learning, predictive uncertainty is often decomposed into the distinct types of aleatoric and epistemic uncertainty. The former can be estimated by letting a DNN output the parameters of a certain probability distribution. Epistemic uncertainty estimation is a more challenging problem, and while different scalable methods recently have emerged, no extensive comparison has been performed in a real-world setting. We therefore accept this task and propose a comprehensive evaluation framework for scalable epistemic uncertainty estimation methods. Our proposed framework is specifically designed to test the robustness required in real-world computer vision applications. We also apply this framework to provide the first properly conclusive comparison of the two current state-of-the-art scalable methods: ensembling and MC-dropout. Our comparison demonstrates that ensembling consistently provides more reliable and practically useful uncertainty estimates."

abstract_short = "We propose a comprehensive evaluation framework for scalable epistemic uncertainty estimation methods in deep learning. It is specifically designed to test the robustness required in real-world computer vision applications. We also apply our proposed framework to provide the first properly extensive and conclusive comparison of the two current state-of-the-art scalable methods: ensembling and MC-dropout. Our comparison demonstrates that ensembling consistently provides more reliable and practically useful uncertainty estimates."
#abstract_short = "We propose an evaluation framework for predictive uncertainty estimation that is specifically designed to test the robustness required #in real-world computer vision applications. Using the framework, we perform an extensive comparison of the popular ensembling and MC-dropout methods on #the tasks of depth completion and street-scene semantic segmentation. Our comparison suggests that ensembling consistently provides more reliable #uncertainty estimates."

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
url_slides = "/files/evaluating_bdl_slides.pdf"
url_poster = "/files/evaluating_bdl_poster_bdl-workshop.pdf"
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
