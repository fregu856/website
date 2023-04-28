+++
title = "Image Restoration with Mean-Reverting Stochastic Differential Equations"
date = "2023-01-27"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ziwei Luo, **Fredrik K. Gustafsson**, Zheng Zhao, Jens Sjölund, Thomas B. Schön"]

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
publication = "The International Conference on Machine Learning (ICML), 2023"
publication_short = "ICML, 2023"

# Abstract and optional shortened version.
abstract = "This paper presents a stochastic differential equation (SDE) approach for general-purpose image restoration. The key construction consists in a mean-reverting SDE that transforms a high-quality image into a degraded counterpart as a mean state with fixed Gaussian noise. Then, by simulating the corresponding reverse-time SDE, we are able to restore the origin of the low-quality image without relying on any task-specific prior knowledge. Crucially, the proposed mean-reverting SDE has a closed-form solution, allowing us to compute the ground truth time-dependent score and learn it with a neural network. Moreover, we propose a maximum likelihood objective to learn an optimal reverse trajectory which stabilizes the training and improves the restoration results. In the experiments, we show that our proposed method achieves highly competitive performance in quantitative comparisons on image deraining, deblurring, and denoising, setting a new state-of-the-art on two deraining datasets. Finally, the general applicability of our approach is further demonstrated via qualitative results on image super-resolution, inpainting, and dehazing."

abstract_short = "We present a stochastic differential equation (SDE) approach for general-purpose image restoration. The key construction is a mean-reverting SDE that models the degradation process from high-quality image to low-quality counterpart. By simulating the corresponding reverse-time SDE, high-quality images can then be restored. We also propose a maximum likelihood objective that stabilizes the training and improves the restoration results. Our method achieves highly competitive performance on the tasks of image deraining, deblurring and denoising. The general applicability is further demonstrated via qualitative results on image super-resolution, inpainting and dehazing."

# Featured image thumbnail (optional)
image_preview = "ir_sde.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2301.11699"
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/Algolzw/image-restoration-sde"
url_dataset = ""
url_project = "https://algolzw.github.io/ir-sde/index.html"
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
#image="ir_sde.png" # (full-width header image)
small_image = "ir_sde.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
