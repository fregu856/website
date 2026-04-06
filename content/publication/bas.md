+++
title = "BAS: A Decision-Theoretic Approach to Evaluating Large Language Model Confidence"
date = "2026-04-06"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Sean Wu*, **Fredrik K. Gustafsson***, Edward Phillips, Boyan Gao, Anshul Thakur, David A. Clifton"]

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
abstract = "Large language models (LLMs) often produce confident but incorrect answers in settings where abstention would be safer. Standard evaluation protocols, however, require a response and do not account for how confidence should guide decisions under different risk preferences. To address this gap, we introduce the _Behavioral Alignment Score_ (BAS), a decision-theoretic metric for evaluating how well LLM confidence supports abstention-aware decision making. BAS is derived from an explicit answer-or-abstain utility model and aggregates realized utility across a continuum of risk thresholds, yielding a measure of decision-level reliability that depends on both the magnitude and ordering of confidence. We show theoretically that truthful confidence estimates uniquely maximize expected BAS utility, linking calibration to decision-optimal behavior. BAS is related to proper scoring rules such as log loss, but differs structurally: log loss penalizes underconfidence and overconfidence symmetrically, whereas BAS imposes an asymmetric penalty that strongly prioritizes avoiding overconfident errors. Using BAS alongside widely used metrics such as ECE and AURC, we then construct a benchmark of self-reported confidence reliability across multiple LLMs and tasks. Our results reveal substantial variation in decision-useful confidence, and while larger and more accurate models tend to achieve higher BAS, even frontier models remain prone to severe overconfidence. Importantly, models with similar ECE or AURC can exhibit very different BAS due to highly overconfident errors, highlighting limitations of standard metrics. We further show that simple interventions, such as top-k confidence elicitation and post-hoc calibration, can meaningfully improve confidence reliability. Overall, our work provides both a principled metric and a comprehensive benchmark for evaluating LLM confidence reliability."

abstract_short = "We introduce BAS, a confidence reliability metric derived from an explicit answer-or-abstain utility model, and show that it defines a proper scoring objective for selective prediction. BAS asymmetrically penalizes overconfident errors, reflecting their impact on decision-level risk. Using BAS alongside widely used metrics such as ECE and AURC, we then construct a benchmark of self-reported confidence reliability across multiple LLMs and tasks. Our results reveal substantial variation in performance, and while larger and more accurate LLMs tend to also achieve better reliability metrics, even frontier models remain prone to severe overconfidence. Our work provides both a principled metric and a comprehensive benchmark for evaluating LLM confidence reliability."



# Featured image thumbnail (optional)
image_preview = "bas.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = []

# Links (optional).
url_arxiv = "https://arxiv.org/abs/2604.03216"
url_pdf = ""
url_code = "https://github.com/SeanWu25/Behavioral-Alignment-Score"
url_preprint = ""
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
small_image = "bas.png" # (header image the same size as the article)
#video="https://www.youtube.com/embed/7JP6V818bh0?enablejsapi=1&version=3&playerapiid=ytplayer" # (like small_image, but with an embedded youtube video instead)
caption = ""

+++
