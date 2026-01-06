+++
title = "Automated Segmentation of Synchrotron-Scanned Fossils"
date = "2024-10-25"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Melanie A.D. During, Jordan K. Matelsky, **Fredrik K. Gustafsson**, Dennis F.A.E. Voeten, Donglei Chen, Brock A. Wester, Konrad P. Körding, Per E. Ahlberg, Thomas B. Schön"]

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
publication = "Fossil Record, 2025"
publication_short = "Fossil Record, 2025"

# Abstract and optional shortened version.
abstract = "Computed tomography has revolutionised the study of the internal three-dimensional structure of fossils. Historically, fossils typically spent years in preparation to be freed from the enclosing rock. Now, X-ray and synchrotron tomography reveal structure that is otherwise invisible and data acquisition can be fast. However, manual segmentation of these 3D volumes can still take months to years. This is especially challenging for resource-poor teams, as scanning may be free, but the computing power and (AI-assisted) segmentation software required to handle the resulting large data sets are complex to use and expensive. Here we present a free, browser-based segmentation tool that reduces computational overhead by splitting volumes into small chunks, allowing processing on low-memory, inexpensive hardware. Our tool also speeds up collaborative ground-truth generation and 3D visualization, all in-browser. We developed and evaluated our pipeline on various open-data scans of differing contrast, resolution, textural complexity, and size. Our tool successfully isolated the Thrinaxodon and Broomistega pair from an Early Triassic burrow. It isolated cranial bones from the Cretaceous acipenseriform Parapsephurus willybemisi on both 45.53 µm and 13.67 µm resolution scanning data. We also isolated bones of the Middle Triassic sauropterygian Nothosaurus and a challenging scan of a squamate embryo inside an egg dating back to the Early Cretaceous. Our tool reliably reproduces expert-supervised segmentation at a fraction of the time and cost, offering greater accessibility than existing tools. Beyond the online tool, all our code is open source, enabling contributions from the palaeontology community to further this emerging machine learning ecosystem."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "ml4paleo.png"

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = ""
url_pdf = "https://fr.pensoft.net/article/139379/"
url_preprint = "https://www.biorxiv.org/content/10.1101/2024.10.23.619778v1.abstract"
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
#image="cpath_fms_shifts.png" # (full-width header image)
small_image = "ml4paleo.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
