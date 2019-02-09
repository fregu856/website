+++
title = "Automotive 3D Object Detection Without Target Domain Annotations"
date = "2018-06-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Fredrik K. Gustafsson", "Erik Linder-Norén"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication = "Master of Science Thesis in Electrical Engineering, Linköping University"
publication_short = "Master of Science Thesis in Electrical Engineering, 2018"

# Abstract and optional shortened version.
abstract = "In this thesis we study a perception problem in the context of autonomous driving. Specifically, we study the computer vision problem of 3D object detection, in which objects should be detected from various sensor data and their position in the 3D world should be estimated. We also study the application of Generative Adversarial Networks in domain adaptation techniques, aiming to improve the 3D object detection model's ability to transfer between different domains. The state-of-the-art Frustum-PointNet architecture for LiDAR-based 3D object detection was implemented and found to closely match its reported performance when trained and evaluated on the KITTI dataset. The architecture was also found to transfer reasonably well from the synthetic SYN dataset to KITTI, and is thus believed to be usable in a semi-automatic 3D bounding box annotation process. The Frustum-PointNet architecture was also extended to explicitly utilize image features, which surprisingly degraded its detection performance. Furthermore, an image-only 3D object detection model was designed and implemented, which was found to compare quite favourably with current state-of-the-art in terms of detection performance. Additionally, the PixelDA approach was adopted and successfully applied to the MNIST to MNIST-M domain adaptation problem, which validated the idea that unsupervised domain adaptation using Generative Adversarial Networks can improve the performance of a task network for a dataset lacking ground truth annotations. Surprisingly, the approach did however not significantly improve upon the performance of the image-based 3D object detection models when trained on the SYN dataset and evaluated on KITTI."

abstract_short = "In this thesis we study the computer vision problem of 3D object detection, in which objects should be detected from various sensor data and their position in the 3D world should be estimated. We also study the application of Generative Adversarial Networks in domain adaptation techniques, aiming to improve the 3D object detection model's ability to transfer between different domains."

# Featured image thumbnail (optional)
image_preview = "thesis_color.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_pdf = "http://urn.kb.se/resolve?urn=urn:nbn:se:liu:diva-148585"
url_preprint = ""
url_code = "https://github.com/fregu856/3DOD_thesis"
url_dataset = ""
url_project = ""
url_video = "https://youtu.be/KdrHLXpYYlg"
url_slides = "http://www.fregu856.com/static/msc_thesis_slides.pdf"
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Link to paper", url = "https://doi.org/10.1093/bioinformatics/btw304"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image="thesis_color.png" # (full-width header image)
#small_image = "thesis_color.png" # (header image the same size as the article)
video="https://www.youtube.com/embed/KdrHLXpYYlg?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
