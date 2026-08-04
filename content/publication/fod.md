+++
title = "Efficient Image Restoration with State-Dependent Forward Diffusion"
date = "2025-05-22"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ziwei Luo, **Fredrik K. Gustafsson**, Jens Sjölund, Thomas B. Schön"]

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
publication = "Transactions on Machine Learning Research (TMLR), 2026"
publication_short = "TMLR, 2026"

# Abstract and optional shortened version.
abstract = "This paper proposes to perform image restoration through a state-dependent mean-reverting forward diffusion (FoD) process. In contrast to traditional diffusion-based approaches that rely on a coupled forward-backward diffusion scheme, FoD directly learns image restoration through a single forward diffusion process, yielding a simple yet efficient framework. The core of FoD is a state-dependent stochastic differential equation (SDE) that involves a mean-reverting term in both the drift and diffusion functions. This mean-reverting structure drives the low-quality data toward the clean endpoint with controlled stochastic variation, therefore simulating a stochastic interpolation between source and target distributions. More importantly, FoD is analytically tractable and is trained using a simple stochastic flow matching objective, enabling few-step sampling during inference. The proposed FoD model, despite its simplicity, achieves strong overall performance on various image restoration tasks compared to representative diffusion, diffusion bridge, and flow matching approaches."

abstract_short = "We perform image restoration through a state-dependent mean-reverting forward diffusion (FoD) process. In contrast to traditional diffusion-based approaches that rely on a coupled forward-backward diffusion scheme, FoD directly learns image restoration through a single forward diffusion process. The core of FoD is a state-dependent SDE that involves a mean-reverting term in both the drift and diffusion functions. This mean-reverting structure drives the LQ data toward the clean endpoint with controlled stochastic variation, simulating a stochastic interpolation between source and target distributions. FoD achieves strong overall performance on various image restoration tasks compared to common diffusion, diffusion bridge, and flow matching methods."

# Featured image thumbnail (optional)
image_preview = "fod_v2.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2505.16733?"
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/Algolzw/FoD"
url_openreview = "https://openreview.net/forum?id=Eq9k6Va3hY"
url_dataset = ""
url_project = "https://algolzw.github.io/fod/"
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
small_image = "fod_v2.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
