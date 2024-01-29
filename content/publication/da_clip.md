+++
title = "Controlling Vision-Language Models for Multi-Task Image Restoration"
date = "2023-10-02"

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
publication = "International Conference on Learning Representations (ICLR), 2024"
publication_short = "ICLR, 2024"

# Abstract and optional shortened version.
abstract = "Vision-language models such as CLIP have shown great impact on diverse downstream tasks for zero-shot or label-free predictions. However, when it comes to low-level vision such as image restoration their performance deteriorates dramatically due to corrupted inputs. In this paper, we present a degradation-aware vision-language model (DA-CLIP) to better transfer pretrained vision-language models to low-level vision tasks as a multi-task framework for image restoration. More specifically, DA-CLIP trains an additional controller that adapts the fixed CLIP image encoder to predict high-quality feature embeddings. By integrating the embedding into an image restoration network via cross-attention, we are able to pilot the model to learn a high-fidelity image reconstruction. The controller itself will also output a degradation feature that matches the real corruptions of the input, yielding a natural classifier for different degradation types. In addition, we construct a mixed degradation dataset with synthetic captions for DA-CLIP training. Our approach advances state-of-the-art performance on both degradation-specific and unified image restoration tasks, showing a promising direction of prompting image restoration with large-scale pretrained vision-language models."

abstract_short = "We present a degradation-aware vision-language model (DA-CLIP) as a multi-task framework for image restoration. DA-CLIP trains an additional controller that adapts the fixed CLIP image encoder to predict high-quality feature embeddings. By integrating the embedding into an image restoration network via cross-attention, we are able to pilot the model to learn a high-fidelity image reconstruction. The controller itself also outputs a degradation feature that matches the real corruptions of the input, yielding a natural classifier for different degradation types. Our approach advances state-of-the-art performance on both degradation-specific and unified image restoration tasks."

# Featured image thumbnail (optional)
image_preview = "da_clip.jpg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2310.01018"
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/Algolzw/daclip-uir"
url_dataset = ""
url_project = "https://algolzw.github.io/daclip-uir/"
url_video_90sec = ""
url_slides_90sec = ""
url_video = ""
url_slides = ""
url_poster = ""
url_source = ""
url_openreview = "https://openreview.net/forum?id=t3vnnLeajU"

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
small_image = "da_clip.jpg" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
