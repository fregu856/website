+++
title = "Scanner-Induced Domain Shifts Undermine the Robustness of Pathology Foundation Models"
date = "2025-01-08"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Erik Thiringer, **Fredrik K. Gustafsson**, Kajsa Ledesma Eriksson, Mattias&nbsp;Rantalainen"]

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
publication = "Preprint"
publication_short = "Preprint"

# Abstract and optional shortened version.
abstract = "Pathology foundation models (PFMs) have become a central building block for computational pathology, aiming to provide a general encoder enabling feature extraction from whole-slide images (WSIs) for a wide range of downstream prediction tasks. Despite strong reported performance in benchmark studies, the robustness of PFMs to technical domain shifts commonly encountered in real-world clinical deployment and across studies remains poorly understood. In particular, variability introduced by differences in whole-slide scanner devices represents a common source of variability that has not been characterised as a primary source of domain shift.    In this study, we systematically evaluated the robustness of 14 PFMs to scanner-induced variability. The evaluated models include state-of-the-art PFMs, earlier pathology-specific models trained with self-supervised learning, and a ResNet baseline model trained on natural images. Using a controlled multiscanner dataset comprising 384 breast cancer WSIs scanned on five different whole-slide scanners, we isolate scanner effects independently of biological and laboratory confounders. Robustness is assessed through complementary unsupervised analyses of the embedding space and a set of clinicopathological supervised prediction tasks, including histological grade and routine biomarker predictions from hematoxylin and eosin images.   Our results demonstrate that current state-of-the-art PFMs are not invariant to scanner-induced domain shifts. Most models encode pronounced scanner-specific variability in their embedding spaces, leading to substantial distortions in both global and local feature space across scanners. Although prediction performance largely remains similar when measured by AUC, this apparent robustness masks a critical failure mode: scanner variability systematically alters the embedding space and impacts calibration of downstream model predictions, resulting in scanner-dependent bias that can impact  reliability in, for example, clinical use cases. We further show that robustness to scanner variability is not a simple function of training data scale, model size, or model recency. None of the models provided reliable robustness against scanner-induced variability. The models trained on the most diverse data, here represented by vision-language models, appear to have an  advantage with respect to robustness, while these models did not perform among the top models in the performance evaluation on supervised tasks.  We conclude that development and evaluation of PFMs requires moving beyond accuracy-centric benchmarks toward explicit evaluation and optimisation of embedding stability and calibration under realistic acquisition variability."

#abstract_short = "Pathology foundation models (PFMs) are central to computational pathology, yet their robustness to real-world technical domain shifts is poorly understood. Using an in-house multiscanner dataset that isolates scanner effects from all other sources of variation, we evaluate the robustness of 14 PFMs to scanner-induced variability. Robustness is assessed via complementary unsupervised embedding analyses and supervised prediction tasks. We find that current PFMs are not invariant to scanner-induced domain shifts. Although predictive AUC often remains stable, scanner variability distorts the embedding space and impacts calibration of downstream predictions. Moreover, robustness is not a simple function of training data scale, model size, or model recency."
#abstract_short = "Pathology foundation models (PFMs) are central to computational pathology, yet their robustness to real-world technical domain shifts is poorly understood. Using a multiscanner dataset that isolates scanner effects from all other sources of variation, we evaluate the robustness of 14 PFMs to scanner variability. Through unsupervised embedding analyses and supervised prediction tasks, we find that no PFM is invariant to scanner-induced domain shifts. Although predictive AUC remains stable, scanner variability distorts embedding spaces and affects calibration of downstream predictions. Robustness is not explained by training data scale, model size, or model recency."

#abstract_short = "Pathology foundation models (PFMs) are central to computational pathology, yet their robustness to real-world technical domain shifts is poorly understood. Using an in-house multiscanner dataset that isolates scanner effects from all other sources of variation, we evaluate the robustness of 14 PFMs to scanner variability. Complementary unsupervised embedding analyses and supervised prediction tasks reveal that no PFM is invariant to scanner-induced domain shifts. Although predictive AUC remains stable, scanner variability distorts embedding spaces and impacts calibration of model predictions. Moreover, robustness is not explained by training data scale, model size, or model recency."
abstract_short = "Pathology foundation models (PFMs) are central to computational pathology, yet their robustness to real-world technical domain shifts is poorly understood. Using an in-house multiscanner dataset that isolates scanner effects from all other sources of variation, we evaluate the robustness of 14 PFMs to scanner variability. Complementary unsupervised embedding analyses and supervised prediction tasks reveal that no PFM is invariant to scanner-induced domain shifts. Although predictive AUC remains stable, scanner variability distorts embedding spaces and impacts calibration of model predictions. Moreover, robustness is not explained by training data scale, model recency or size."

# Featured image thumbnail (optional)
image_preview = "pfms_scanners.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2601.04163"
url_pdf = ""
url_preprint = ""
url_code = ""
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
small_image = "pfms_scanners.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
