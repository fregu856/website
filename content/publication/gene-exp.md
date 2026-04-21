+++
title = "Evaluation and Prognostic Validation of Deep Regression Models for WSI-Based Gene-Expression Prediction"
date = "2026-04-20"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Fredrik K. Gustafsson**, TODO!, Mattias Rantalainen"]

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

#Gene-expression profiling is central to precision oncology but remains costly and not universally accessible. Recent advances in computational pathology enable prediction of transcriptomic profiles directly from hematoxylin and eosin (H&E)-stained whole-slide images (WSIs), although optimal modelling strategies and clinical relevance remain unclear. In this study, we systematically evaluate deep regression models for WSI-based gene-expression prediction across multiple regression formulations and pathology foundation models (PFMs), and assess whether the resulting predicted transcriptomic signals retain prognostic utility. Across four TCGA datasets, we find that direct regression using attention-based multiple instance learning together with PFM feature extractors provides a strong and computationally efficient baseline, with no consistent benefit from separately training multiple models on subsets of genes. We then externally validate the selected configuration on an independent cohort of 997 breast cancer patients, demonstrating robust generalization for clinically relevant gene sets such as PAM50. To assess clinical relevance, we further perform external evaluation of predicted gene-expression scores on two independent survival cohorts comprising 4,172 breast cancer patients, where predicted scores retain prognostic value in both the full patient cohort and the ER+ & HER2- subgroup. Together, these results demonstrate that WSI-based gene-expression prediction can generalize across independent cohorts and recover biologically and clinically meaningful molecular structure, supporting its potential as a scalable approach for transcriptomic phenotyping and risk stratification.
#abstract_short = "Gene-expression profiling is central to precision oncology but remains costly and not universally accessible. Recent advances in computational pathology enable prediction of transcriptomic profiles directly from WSIs, but optimal modelling strategies and clinical relevance remain unclear. We systematically evaluate deep regression models for WSI-based gene-expression prediction and assess whether the resulting predicted transcriptomic signals retain prognostic utility. Across TCGA datasets, we find that direct regression using AMBIL together with PFM feature extractors provides a strong and computationally efficient baseline, with no consistent benefit from separately training multiple models on subsets of genes. We then externally validate the selected configuration on an independent cohort of 997 breast cancer patients, demonstrating robust generalization for clinically relevant gene sets such as PAM50. To assess clinical relevance, we further perform external evaluation of predicted gene-expression scores on two independent survival cohorts comprising 4,172 breast cancer patients, where predicted scores retain prognostic value in both the full patient cohort and the ER+ & HER2- subgroup. Together, these results demonstrate that WSI-based gene-expression prediction can generalize across independent cohorts and recover biologically and clinically meaningful molecular structure, supporting its potential as a scalable approach for transcriptomic phenotyping and risk stratification."
#abstract_short = "Gene-expression profiling is central to precision oncology but remains costly and not universally accessible. We systematically evaluate deep regression models for WSI-based gene-expression prediction, finding that direct regression using AMBIL together with PFMs provides a strong and computationally efficient baseline, with no consistent benefit from training multiple models on gene subsets. We externally validate this approach on a dataset of 997 breast cancer patients, with robust generalization for clinically relevant gene sets such as PAM50. Predicted gene-expression scores further retain prognostic value across two independent survival datasets of 4,172 patients. These results demonstrate that WSI-based gene-expression prediction can generalize across cohorts and capture clinically meaningful molecular structure, supporting its potential as a scalable approach for transcriptomic phenotyping."
abstract_short = "Gene-expression profiling is central to precision oncology but is not universally accessible. We systematically evaluate deep regression models for WSI-based gene-expression prediction, finding that direct regression using ABMIL provides a strong and efficient baseline, with no consistent benefit from training multiple models on gene subsets. We externally validate this approach on a cohort of 997 breast cancer patients, with good performance for gene sets such as PAM50. Predicted gene-expression scores also retain prognostic value across two independent survival cohorts of 4,172 patients. These results show that WSI-based gene-expression prediction captures clinically meaningful molecular structure, supporting its potential for scalable transcriptomic phenotyping."

# Featured image thumbnail (optional)
image_preview = "gene-exp_v2.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2410.00945"
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_video_90sec = ""
url_slides_90sec = ""
url_video = ""
url_slides = ""
url_poster = "/files/gene-exp_poster.pdf"
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
small_image = "gene-exp_v2.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
