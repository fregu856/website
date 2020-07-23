+++
title = "Energy-Based Models for Deep Probabilistic Regression"
date = "2019-09-26"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Fredrik K. Gustafsson", "Martin Danelljan", "Goutam Bhat", "Thomas B. Schön"]

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
publication = "The European Conference on Computer Vision (ECCV), 2020"
publication_short = "ECCV, 2020"

# Abstract and optional shortened version.
abstract = "While deep learning-based classification is generally tackled using standardized approaches, a wide variety of techniques are employed for regression. In computer vision, one particularly popular such technique is that of confidence-based regression, which entails predicting a confidence value for each input-target pair (x,y). While this approach has demonstrated impressive results, it requires important task-dependent design choices, and the predicted confidences lack a natural probabilistic meaning. We address these issues by proposing a general and conceptually simple regression method with a clear probabilistic interpretation. In our proposed approach, we create an energy-based model of the conditional target density p(y|x), using a deep neural network to predict the un-normalized density from (x,y). This model of p(y|x) is trained by directly minimizing the associated negative log-likelihood, approximated using Monte Carlo sampling. We perform comprehensive experiments on four computer vision regression tasks. Our approach outperforms direct regression, as well as other probabilistic and confidence-based methods. Notably, our model achieves a 2.2% AP improvement over Faster-RCNN for object detection on the COCO dataset, and sets a new state-of-the-art on visual tracking when applied for bounding box estimation. In contrast to confidence-based methods, our approach is also shown to be directly applicable to more general tasks such as age and head-pose estimation."

abstract_short = "We propose a general and conceptually simple regression method with a clear probabilistic interpretation. We create an energy-based model of the conditional target density p(y|x), using a deep neural network to predict the un-normalized density from the input-target pair (x,y). This model of p(y|x) is trained by directly minimizing the associated negative log-likelihood, approximated using Monte Carlo sampling. Notably, our model achieves a 2.2% AP improvement over Faster-RCNN for object detection on the COCO dataset, and sets a new state-of-the-art on visual tracking when applied for bounding box regression."
#abstract_short = "We propose a general and conceptually simple regression method with a clear probabilistic interpretation. We create an energy-based model of the conditional target density p(y|x), using a deep neural network to predict the un-normalized density from the input-target pair (x,y). This model of p(y|x) is trained by directly minimizing the associated negative log-likelihood, approximated using Monte Carlo sampling. Notably, our model achieves a 1.9% AP improvement over Faster-RCNN for object detection on the COCO dataset, and sets a new state-of-the-art on visual tracking when applied for bounding box regression."
#abstract_short = "We propose Deep Conditional Target Densities (DCTD), a novel and general regression method with a clear probabilistic interpretation. #DCTD models the conditional target density p(y|x) by using a neural network to directly predict the un-normalized density from the input-target pair (x, #y). This model of p(y|x) is trained by minimizing the associated negative log-likelihood, approximated using Monte Carlo sampling. Notably, our method #achieves a 1.9% AP improvement over Faster-RCNN for object detection on COCO, and sets a new state-of-the-art on visual tracking when applied for #bounding box regression."

# Featured image thumbnail (optional)
image_preview = "learning_dctd__.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/1909.12297"
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/fregu856/ebms_regression"
url_dataset = ""
url_project = ""
url_video_1min = "https://youtu.be/oacQnWV7XeI"
url_slides_1min = "/files/dctd_1min.pdf"
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
#small_image = "learning_dctd__.png" # (header image the same size as the article)
video="https://www.youtube.com/embed/oacQnWV7XeI?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
