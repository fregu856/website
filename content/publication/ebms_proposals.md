+++
title = "Learning Proposals for Practical Energy-Based Regression"
date = "2021-10-22"

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
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "The International Conference on Artificial Intelligence and Statistics (AISTATS), 2022"
publication_short = "AISTATS, 2022"

# Abstract and optional shortened version.
abstract = "Energy-based models (EBMs) have experienced a resurgence within machine learning in recent years, including as a promising alternative for probabilistic regression. However, energy-based regression requires a proposal distribution to be manually designed for training, and an initial estimate has to be provided at test-time. We address both of these issues by introducing a conceptually simple method to automatically learn an effective proposal distribution, which is parameterized by a separate network head. To this end, we derive a surprising result, leading to a unified training objective that jointly minimizes the KL divergence from the proposal to the EBM, and the negative log-likelihood of the EBM. At test-time, we can then employ importance sampling with the trained proposal to efficiently evaluate the learned EBM and produce stand-alone predictions. Furthermore, we utilize our derived training objective to learn mixture density networks (MDNs) with a jointly trained energy-based teacher, consistently outperforming conventional MDN training on four real-world regression tasks within computer vision."

abstract_short = "We derive an efficient and convenient objective that can be employed to train a parameterized distribution q(y|x; phi) by directly minimizing its KL divergence to a conditional EBM p(y|x; theta). We then employ the proposed objective to jointly learn an effective MDN proposal distribution during EBM training, thus addressing the main practical limitations of energy-based regression. Furthermore, we utilize our derived training objective to learn MDNs with a jointly trained energy-based teacher, consistently outperforming conventional MDN training on four real-world regression tasks within computer vision."

# Featured image thumbnail (optional)
image_preview = "ebms_proposals.svg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2110.11948"
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/fregu856/ebms_proposals"
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
small_image = "ebms_proposals.svg" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
