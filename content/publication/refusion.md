+++
title = "Refusion: Enabling Large-Size Realistic Image Restoration with Latent-Space Diffusion Models"
date = "2023-04-18"

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
publication = "The IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPR Workshops), 2023"
publication_short = "CVPR Workshops, 2023"

# Abstract and optional shortened version.
abstract = "This work aims to improve the applicability of diffusion models in realistic image restoration. Specifically, we enhance the diffusion model in several aspects such as network architecture, noise level, denoising steps, training image size, and optimizer/scheduler. We show that tuning these hyperparameters allows us to achieve better performance on both distortion and perceptual scores. We also propose a U-Net based latent diffusion model which performs diffusion in a low-resolution latent space while preserving high-resolution information from the original input for the decoding process. Compared to the previous latent-diffusion model which trains a VAE-GAN to compress the image, our proposed U-Net compression strategy is significantly more stable and can recover highly accurate images without relying on adversarial optimization. Importantly, these modifications allow us to apply diffusion models to various image restoration tasks, including real-world shadow removal, HR non-homogeneous dehazing, stereo super-resolution, and bokeh effect transformation. By simply replacing the datasets and slightly changing the noise network, our model, named Refusion, is able to deal with large-size images (e.g., 6000 x 4000 x 3 in HR dehazing) and produces good results on all the above restoration problems. Our Refusion achieves the best perceptual performance in the NTIRE 2023 Image Shadow Removal Challenge and wins 2nd place overall."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "refusion.png"

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2304.08291"
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/Algolzw/image-restoration-sde"
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
#image="ir_sde.png" # (full-width header image)
small_image = "refusion.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
