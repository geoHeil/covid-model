+++
title = "The impact of COVID-19 on relative changes in aggregated mobility using mobile-phone data"
date = 2020-09-04T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Georg Heiler", "Allan Hanbury", "Peter Filzmoser"]

# author_notes = ["Equal contribution", "Equal contribution"]

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
publication = "Preprint: The impact of COVID-19 on relative changes in aggregated"
publication_short = "Compositional analysis of mobility changes due to COVID lock-down measures"

# Abstract and optional shortened version.
abstract = "Evaluating relative changes leads to additional insights that would remain hidden when only evaluating absolute changes. We analyze a dataset describing the mobility of mobile phones in Austria before, during COVID-19 lock-down measures until recently.By applying compositional data analysis we show that formerly hidden information becomes available: we see that the elderly population groups increase relative mobility and that the younger groups, especially on weekends, also do not decrease their mobility as much as the others."
abstract_short = "CODA COVID"

# Is this a selected publication? (true/false)
featured = true

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
tags = ["covid-19"]

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/2009.03798"
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
doi = ""

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Biplots of the centered log ratio coefficients of the median radius of gyration values for females (left) and male (right) age groups. Green color for period before the lock-down, pink for lock-down period, purple after lock-down until mid of June, and light-blue after this period."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "bottom"
+++

# Management summary

Mobility data from mobile phones are used to investigate mobility changes during Covid- 19 lock-down measures in Austria. Here we focus on relative changes between different sub-groups of the population by using the tools from compositional data analysis. This allows to gain much deeper insight into differences between the groups, and how these differences evolved over time.

Also take a look at the other publication anylzing absolute mobility behavior changes:
[Country-wide mobility changes observed using mobile phone data during COVID-19 pandemic ]({{< ref "/publication/covid-basic/index.md" >}})