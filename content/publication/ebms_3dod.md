+++
title = "Accurate 3D Object Detection using Energy-Based Models"
date = "2020-12-08"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Fredrik K. Gustafsson", "Martin Danelljan", "Thomas B. Schön"]

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
#publication = "Preprint, 2020"
#publication_short = "Preprint, 2020"
publication = "The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops, 2021"
publication_short = "CVPR Workshops, 2021"

# Abstract and optional shortened version.
abstract = "Accurate 3D object detection (3DOD) is crucial for safe navigation of complex environments by autonomous robots. Regressing accurate 3D bounding boxes in cluttered environments based on sparse LiDAR data is however a highly challenging problem. We address this task by exploring recent advances in conditional energy-based models (EBMs) for probabilistic regression. While methods employing EBMs for regression have demonstrated impressive performance on 2D object detection in images, these techniques are not directly applicable to 3D bounding boxes. In this work, we therefore design a differentiable pooling operator for 3D bounding boxes, serving as the core module of our EBM network. We further integrate this general approach into the state-of-the-art 3D object detector SA-SSD. On the KITTI dataset, our proposed approach consistently outperforms the SA-SSD baseline across all 3DOD metrics, demonstrating the potential of EBM-based regression for highly accurate 3DOD."

abstract_short = "We apply energy-based models p(y|x; theta) to the task of 3D bounding box regression, extending the recent energy-based regression approach from 2D to 3D object detection. This is achieved by designing a differentiable pooling operator for 3D bounding boxes y, and adding an extra network branch to the state-of-the-art 3D object detector SA-SSD. We evaluate our proposed detector on the KITTI dataset and consistently outperform the SA-SSD baseline, demonstrating the potential of energy-based models for 3D object detection."

# Featured image thumbnail (optional)
image_preview = "ebms_3dod.svg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2012.04634"
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/fregu856/ebms_3dod"
url_dataset = ""
url_project = ""
url_video_90sec = ""
url_slides_90sec = ""
url_video = "https://youtu.be/7JP6V818bh0"
url_slides = "/files/ebms_3dod_slides210129.pdf"
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
#small_image = "ebms_regression.jpg" # (header image the same size as the article)
video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
