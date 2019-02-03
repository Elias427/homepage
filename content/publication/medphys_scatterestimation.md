+++
title = "Real-time scatter estimation for medical CT using the deep scatter estimation : Method and robustness analysis with respect to different anatomies, dose levels, tube voltages, and data truncation"
date = 2018-11-02T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["J. Maier", "E. Eulig", "T. Voth", "M. Knaup", "J. Kuntz", "S. Sawall", "M. Kachelrieß"]


# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *Medical Physics*"
publication_short = "In *Medical Physics*"

# Abstract and optional shortened version.
abstract = "*Purpose:* X‐ray scattering leads to CT images with a reduced contrast, inaccurate CT values as well as streak and cupping artifacts. Therefore, scatter correction is crucial to maintain the diagnostic value of CT and CBCT examinations. However, existing approaches are not able to combine both high accuracy and high computational performance. Therefore, we propose the deep scatter estimation (DSE): a deep convolutional neural network to derive highly accurate scatter estimates in real time. <br/>
*Methods:* Gold standard scatter estimation approaches rely on dedicated Monte Carlo (MC) photon transport codes. However, being computationally expensive, MC methods cannot be used routinely. To enable real‐time scatter correction with similar accuracy, DSE uses a deep convolutional neural network that is trained to predict MC scatter estimates based on the acquired projection data. Here, the potential of DSE is demonstrated using simulations of CBCT head, thorax, and abdomen scans as well as measurements at an experimental table‐top CBCT. Two conventional computationally efficient scatter estimation approaches were implemented as reference: a kernel‐based scatter estimation (KSE) and the hybrid scatter estimation (HSE). <br/>"
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.13274"
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

# Digital Object Identifier (DOI)
doi = "10.1002/mp.13274"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
