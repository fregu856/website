+++
title = "Towards Accurate and Reliable Deep Regression Models"
date = "2023-11-30"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Fredrik K. Gustafsson**"]

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
publication_types = ["7"]

# Publication name and optional abbreviated version.
publication = "PhD Thesis, 2023"
publication_short = "PhD Thesis, 2023"

# Abstract and optional shortened version.
abstract = "Regression is a fundamental machine learning task with many important applications within computer vision and other domains. In general, it entails predicting continuous targets from given inputs. Deep learning has become the dominant paradigm within machine learning in recent years, and a wide variety of different techniques have been employed to solve regression problems using deep models. There is however no broad consensus on how deep regression models should be constructed for best possible accuracy, or how the uncertainty in their predictions should be represented and estimated. These open questions are studied in this thesis, aiming to help take steps towards an ultimate goal of developing deep regression models which are both accurate and reliable enough for real-world deployment within medical applications and other safety-critical domains. The first main contribution of the thesis is the formulation and development of energy-based probabilistic regression. This is a general and conceptually simple regression framework with a clear probabilistic interpretation, using energy-based models to represent the true conditional target distribution. The framework is applied to a number of regression problems and demonstrates particularly strong performance for 2D bounding box regression, improving the state-of-the-art when applied to the task of visual tracking. The second main contribution is a critical evaluation of various uncertainty estimation methods. A general introduction to the problem of estimating the predictive uncertainty of deep models is first provided, together with an extensive comparison of the two popular methods ensembling and MC-dropout. A number of regression uncertainty estimation methods are then further evaluated, specifically examining their reliability under real-world distribution shifts. This evaluation uncovers important limitations of current methods and serves as a challenge to the research community. It demonstrates that more work is required in order to develop truly reliable uncertainty estimation methods for regression."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_pdf = ""
url_pdf_pdf = "/files/thesis.pdf"
url_diva = "https://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-513727"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_video = ""
url_slides = "/files/defense_slides_handout.pdf"
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
small_image = "thesis_front.jpg" # (header image the same size as the article)
#video="https://www.youtube.com/embed/KdrHLXpYYlg?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
