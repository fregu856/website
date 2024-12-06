+++
title = "Multi-Stain Modelling of Histopathology Slides for Breast Cancer Prognosis Prediction"
date = "2024-11-18"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Abhinav Sharma, **Fredrik K. Gustafsson**, Johan Hartman, Mattias Rantalainen"]

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
publication = "Preprint, 2024"
publication_short = "Preprint, 2024"

# Abstract and optional shortened version.
abstract = "**Background:** Pathologic assessment of the established biomarkers using standard hematoxylin & eosin (H&E) and immunohistochemical (IHC) stained whole slide images (WSIs) is central in routine breast cancer diagnostics and contributes prognostic and predictive information that guides clinical decision-making. However, other than only aggregated protein-expression values from IHC WSIs, a spatial combination of histo-morphological information from IHC and H&E WSIs can potentially improve prognosis prediction in breast cancer patients. In this study, we aim to develop a deep learning-based risk-stratification method for breast cancer using routine H&E and IHC-stained histopathology WSIs from resected tumours. **Methods:** This is a retrospective study including WSIs from surgical resected specimens from 945 patients from the South General Hospital in Stockholm. One H&E and four IHC (ER, PR, HER2, and Ki-67) stained sections were included from each patient, retrieved from the same tumour block. The IHC WSIs with the H&E WSI were registered, and corresponding images patches (tiles) were extracted for each image modality. Features from the registered tiles were extracted using two existing and publicly available histopathology foundation models (UNI and CONCH). Using the extracted features together with time-to-event data, we optimised an attention-based multiple instance learning (MIL) model using the Cox loss (negative partial log-likelihood loss) and recurrence-free survival (RFS) as the survival endpoint. **Results:** Using cross-validation we observed a prognostic performance with a C-index of 0.65 (95%CI: 0.56 - 0.72) for the risk score prediction using only H&E WSIs and UNI as the tile-level feature extractor. Combinations of H&E with one or more IHC modalities were subsequently evaluated, with the highest performance observed in the model combining the H&E and PR WSI data and the model combining all the stains, obtaining a C-index of 0.72 (95% CI: 0.65 - 0.79) and 0.72 (95% CI: 0.64 - 0.79) respectively. **Conclusion:** Multiple stain modalities are used in routine breast cancer pathology, but has not been considered together for prognostic modelling. The results in this study suggests that models combining morphological features extracted by histopathology foundation models across multiple stain modalities can improve prognostic risk-stratification performance compared to single-modality models."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "multi-stain.png"

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = ""
url_pdf = ""
url_preprint = "https://www.medrxiv.org/content/10.1101/2024.11.10.24317066v1"
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
small_image = "multi-stain.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
