+++
title = "Regional Multiscale Motion Representation for Cardiac Disease Prediction"

# Date first published.
date = "2019-02-22"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Alejandra Moreno", "Jefferson Rodríguez", "Fabio Martínez"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *XXII Symposium on Image, Signal Processing and Artificial Vision, Colombia.*"
publication_short = "In *STSIVA*, **Accepted** "

# Abstract and optional shortened version.
abstract="Heart characterization is a challenging task due to the non-linear dynamic performance and the strong shape deformation during cardiac cycle. This work presents a regional multiscale motion representation of cardiac structures that is able to recognize pathologies on cine-MRI sequences. Firstly, a dense optical flow that considers large displacements was computed to obtain a velocity field representation. Then, regional dynamic patterns are coded into a multiscale scheme, from coarse to fine, emerging the most relevant cardiac patterns that remain along the different scales. The resulting motion descriptor is then formed by a set of flow orientation occurrences computed in whole multiscale regions. This descriptor is mapped to a previously trained Random forest classifier to obtain a prediction of the cardiac condition. The proposed strategy was evaluated over a set of 45 cine-MRI volumes achieving an average F1-score of  76.7% on the task of binary classification of among fourth cardiac conditions."

abstract_short = "A short version of the abstract."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# [header]
# image = "headers/bubbles-wide.jpg"
# caption = "My caption 😄"

+++
