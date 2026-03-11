+++
title = "SignalMC-MED: A Multimodal Benchmark for Evaluating Biosignal Foundation Models on Single-Lead ECG and PPG"
date = "2026-03-11"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Fredrik K. Gustafsson**, Xiao Gu, Mattia Carletti, Patitapaban Palo, David W. Eyre, David A. Clifton"]

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
abstract = "Recent biosignal foundation models (FMs) have demonstrated promising performance across diverse clinical prediction tasks, yet systematic evaluation on long-duration multimodal data remains limited. We introduce SignalMC-MED, a benchmark for evaluating biosignal FMs on synchronized single-lead electrocardiogram (ECG) and photoplethysmogram (PPG) data. Derived from the MC-MED dataset, SignalMC-MED comprises 22,256 visits with 10-minute overlapping ECG and PPG signals, and includes 20 clinically relevant tasks spanning prediction of demographics, emergency department disposition, laboratory value regression, and detection of prior ICD-10 diagnoses. Using this benchmark, we perform a systematic evaluation of representative time-series and biosignal FMs across ECG-only, PPG-only, and ECG + PPG settings. We find that domain-specific biosignal FMs consistently outperform general time-series models, and that multimodal ECG + PPG fusion yields robust improvements over unimodal inputs. Moreover, using the full 10-minute signal consistently outperforms shorter segments, and larger model variants do not reliably outperform smaller ones. Hand-crafted ECG domain features provide a strong baseline and offer complementary value when combined with learned FM representations. Together, these results establish SignalMC-MED as a standardized benchmark and provide practical guidance for evaluating and deploying biosignal FMs."

abstract_short = "Biosignal foundation models (FMs) have shown promise for clinical prediction, yet systematic evaluation on long-duration multimodal data remains limited. We introduce SignalMC-MED, a benchmark of 22,256 emergency department visits with synchronized 10-minute single-lead ECG and PPG, evaluating FMs across 20 clinically relevant tasks. Using this benchmark, we compare representative time-series and biosignal FMs across ECG-only, PPG-only, and ECG + PPG settings. Domain-specific biosignal FMs outperform general time-series models, multimodal ECG + PPG fusion and longer signal segments consistently improve performance, larger model variants do not reliably outperform smaller ones, and hand-crafted ECG features remain strong complementary baselines."

# Featured image thumbnail (optional)
image_preview = "signalmc-med.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2603.09940"
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/fregu856/SignalMC-MED"
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
#image="signalmc-med4.png" # (full-width header image)
small_image = "signalmc-med_detailed.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
