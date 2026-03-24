+++
title = "Semantic Self-Distillation for Language Model Uncertainty"
date = "2026-03-24"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Edward Phillips, Sean Wu, **Fredrik K. Gustafsson**, Boyan Gao, David A. Clifton"]

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
abstract = "Large language models present challenges for principled uncertainty quantification, in part due to their complexity and the diversity of their outputs. Semantic dispersion, or the variance in the meaning of sampled answers, has been proposed as a useful proxy for model uncertainty, but the associated computational cost prohibits its use in latency-critical applications. We show that sampled semantic distributions can be distilled into lightweight student models which estimate a prompt-conditioned density before the language model generates an answer token. The student model predicts a semantic distribution over possible answers; the entropy of this distribution provides a prompt-level uncertainty signal, and the probability density allows answer-level reliability evaluation. Across experiments on TriviaQA and MMLU, we find our student models perform competitively relative to sampling-based semantic dispersion baselines on a hallucination prediction task, whilst offering additional uncertainty primitives for out-of-domain detection and multiple-choice answer selection. We term this technique Semantic Self-Distillation (SSD), which can serve as a general framework for distilling predictive uncertainty in complex output spaces beyond language."

abstract_short = "LLMs make principled uncertainty estimation difficult due to their complexity and diverse outputs. Semantic dispersion, the variance in the meaning of sampled answers, captures this uncertainty but is too computationally expensive for latency-critical applications. We show that sampled semantic distributions can be distilled into lightweight student models which estimate a prompt-conditioned density before generation. The student model predicts a semantic distribution over answers, where the entropy provides a prompt-level uncertainty signal, and the density allows answer-level reliability evaluation. Our approach matches sampling-based baselines for hallucination detection while enabling out-of-domain detection and multiple-choice answer selection."

# Featured image thumbnail (optional)
image_preview = "ssd.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2602.04577"
url_pdf = ""
url_preprint = ""
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
small_image = "ssd.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
