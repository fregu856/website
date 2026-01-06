+++
title = "Forward-only Diffusion Probabilistic Models"
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
publication_types = ["8"]

# Publication name and optional abbreviated version.
publication = "Preprint, 2025"
publication_short = "Preprint, 2025"

# Abstract and optional shortened version.
abstract = "This work presents a forward-only diffusion (FoD) approach for generative modelling. In contrast to traditional diffusion models that rely on a coupled forward-backward diffusion scheme, FoD directly learns data generation through a single forward diffusion process, yielding a simple yet efficient generative framework. The core of FoD is a state-dependent stochastic differential equation that involves a mean-reverting term in both the drift and diffusion functions. This mean-reversion property guarantees the convergence to clean data, naturally simulating a stochastic interpolation between source and target distributions. More importantly, FoD is analytically tractable and is trained using a simple stochastic flow matching objective, enabling a few-step non-Markov chain sampling during inference. The proposed FoD model, despite its simplicity, achieves state-of-the-art performance on various image restoration tasks. Its general applicability on image-conditioned generation is also demonstrated via qualitative results on image-to-image translation."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "fod.png"

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2505.16733?"
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/Algolzw/FoD"
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
small_image = "fod.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
