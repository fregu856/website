+++
title = "Uncertainty-Aware Body Composition Analysis with Deep Regression Ensembles on UK Biobank MRI"
date = "2021-01-18"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Taro Langner", "**Fredrik K. Gustafsson**", "Benny Avelin", "Robin Strand", "Håkan Ahlström", "Joel Kullberg"]

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
publication = "Computerized Medical Imaging and Graphics, 2021"
publication_short = "Computerized Medical Imaging and Graphics, 2021"

# Abstract and optional shortened version.
abstract = "Purpose: To enable fast and automated analysis of body composition from UK Biobank MRI with accurate estimates of individual measurement errors. Methods: In an ongoing large-scale imaging study the UK Biobank has acquired MRI of over 40,000 men and women aged 44-82. Phenotypes derived from these images, such as body composition, can reveal new links between genetics, cardiovascular disease, and metabolic conditions. In this retrospective study, neural networks were trained to provide six measurements of body composition from UK Biobank neck-to-knee body MRI. A ResNet50 architecture can automatically predict these values by image-based regression, but may also produce erroneous outliers. Predictive uncertainty, which could identify these failure cases, was therefore modeled with a mean-variance loss and ensembling. Its estimates of individual prediction errors were evaluated in cross-validation on over 8,000 subjects, tested on another 1,000 cases, and finally applied for inference. Results: Relative measurement errors below 5% were achieved on all but one target, for intra-class correlation coefficients (ICC) above 0.97 both in validation and testing. Both mean-variance loss and ensembling yielded improvements and provided uncertainty estimates that highlighted some of the worst outlier predictions. Combined, they reached the highest quality, but also exhibited a consistent bias towards high uncertainty in heavyweight subjects. Conclusion: Mean-variance regression and ensembling provided complementary benefits for automated body composition measurements from UK Biobank MRI, reaching high speed and accuracy. These values were inferred for the entire cohort, with uncertainty estimates that can approximate the measurement errors and identify some of the worst outliers automatically."

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
url_arxiv = "https://arxiv.org/abs/2101.06963"
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/tarolangner/mri-biometry"
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
small_image = "mri_regression.png" # (header image the same size as the article)
#video="" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
