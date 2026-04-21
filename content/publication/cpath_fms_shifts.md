+++
title = "Evaluating Computational Pathology Foundation Models for Prostate Cancer Grading under Distribution Shifts"
date = "2026-04-19"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Fredrik K. Gustafsson**, Mattias Rantalainen"]

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
abstract = "TODO! TODO! TODO!"

#Pathology foundation models (PFMs) have emerged as powerful pretrained encoders for computational pathology, but their robustness under clinically relevant distribution shifts remains insufficiently understood. We benchmark the robustness of recent PFMs in the setting of prostate cancer grading from whole-slide images (WSIs). Using the PANDA dataset, we evaluate PFMs as frozen patch-level feature extractors within weakly supervised slide-level grading models, and assess robustness to two important forms of distribution shift: shifts in WSI image appearance across collection sites, and shifts in the label distribution over cancer grade groups. Across in-distribution settings, PFMs consistently achieve strong performance and clearly outperform a natural-image baseline. Under cross-site transfer from Radboud to Karolinska, however, performance drops substantially for all models, showing that large-scale pretraining alone does not guarantee robust downstream generalization. In contrast, PFMs are less sensitive to label-distribution shift, indicating that visually grounded domain shift is the dominant challenge. Representation analysis further supports these findings by revealing persistent domain separation between sites across all PFMs. While grade-related structure is present, it is comparatively weak, indicating that domain-related variation dominates in the learned feature space. Together, these results provide a comprehensive benchmark of PFMs under distribution shift and highlight an important practical message: although PFMs provide strong representations, robust deployment remains constrained by the quality and diversity of the data used to train downstream prediction models.

#abstract_short = "Foundation models (FMs) are intended to be general-purpose feature extractors. Real-world pathology image data does however exhibit considerable variability. FMs should be robust to these variations and other distribution shifts which might be encountered in practice. We evaluate two computational pathology FMs (UNI and CONCH), by utilizing them as feature extractors within prostate cancer grading models. We find that while FMs perform well relative to baselines, the absolute performance can still be far from satisfactory. The fact that FMs have been trained on large and varied datasets does not guarantee that downstream models always will be robust to common distribution shifts."

#abstract_short = "Pathology foundation models (PFMs) have become central to computational pathology, but their robustness under distribution shifts remains insufficiently understood. We benchmark PFMs for prostate cancer grading from WSIs, evaluating robustness to shifts in WSI image appearance across sites and in the label distribution over cancer grades. PFMs consistently perform well in-distribution, but performance drops substantially under cross-site transfer. In comparison, PFMs are less sensitive to label-distribution shift. Representation analysis also reveals persistent domain separation between sites. These results show that while PFMs provide strong representations, robust deployment remains constrained by the quality and diversity of the data used to train downstream prediction models."

abstract_short = "Pathology foundation models (PFMs) have become central to computational pathology, but their robustness under distribution shifts remains insufficiently understood. We benchmark PFMs for prostate cancer grading from WSIs, evaluating robustness to shifts in WSI image appearance across sites and in the label distribution over cancer grades. PFMs consistently perform well in-distribution, but performance drops substantially under cross-site transfer. In comparison, PFMs are less sensitive to label-distribution shift, indicating that visually grounded domain shift is the dominant challenge. While PFMs provide strong representations, robust deployment remains constrained by the quality and diversity of the data used to train downstream prediction models."

# Featured image thumbnail (optional)
image_preview = "cpath_fms_shifts_v2.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2410.06723"
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_video_90sec = ""
url_slides_90sec = ""
url_video = ""
url_slides = "/files/talk_241016_slides.pdf"
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
#image="cpath_fms_shifts.png" # (full-width header image)
small_image = "cpath_fms_shifts_v2.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
