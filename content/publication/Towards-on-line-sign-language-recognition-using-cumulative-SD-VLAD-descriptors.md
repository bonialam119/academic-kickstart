+++
title = "Towards on-line sign language recognition using cumulative SD-VLAD descriptors"

# Date first published.
date = "2018-06-14, **Accepted**"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jefferson Rodríguez", "Fabio Martínez"]

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
publication = "In *Colombian Conference on Computing, Colombia.*"
publication_short = "In *13CCC*"

# Abstract and optional shortened version.
abstract = "On-line prediction of sign language gestures is nowadays a fundamental task to help and support multimedia interpretation of deaf communities. This work present a novel approach to recover partial sign language gestures by cumulative coding different intervals of the video sequences. The method starts by computing volumetric patches that contain kinematic information from different appearance flow primitives. Then, several sequential intervals are learned to carried out the task of partial recognition. For each new video, a cumulative shape difference (SD)-VLAD representation is obtained at different intervals of the video. Each SD-VLAD descriptor recover mean and variance motion information as signature of the computed gesture. Along the video, each partial representation is mapped to a support vector machine model to obtain a gesture recognition, being usable in on-line scenarios. The proposed approach was evaluated in a public dataset with 64 different classes, recorded in 3200 samples. The proposed approach is able to recognize sign gestures using only 20% of the sequence with an average accuracy of 53.8%. For complete sequences the proposed approach achieves 85% in average."

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
url_pdf = "pdf/my-paper-name.pdf"
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
