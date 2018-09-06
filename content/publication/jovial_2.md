+++
title = "Notebook-based Astronomical Data Analysis in the Cloud"
date = 2018-09-04T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Mauricio Araya"
, "Camilo Valenzuela"
, "Mauricio Solar"
, "Carlos Ponce"
, "Matías Díaz"
, "Martín Villanueva"
, "Maximiliano Osorio"]

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
publication = "In *Astronomy and Computing*."
publication_short = "In *Astronomy and Computing*"

# Abstract and optional shortened version.
abstract = "Performing astronomical data analysis using only personal computers is becoming impractical for the very large data sets produced nowadays. As analysis is not a task that can be automatized to its full extent, the idea of moving processing where the data is located means also moving the whole scientific process towards the archives and data centers. Using Jupyter Notebooks as a remote service is a recent trend in data analysis that aims to deal with this problem, but harnessing the infrastructure to serve the astronomer without increasing the complexity of the service is a challenge. In this paper we present the architecture and features of JOVIAL, a Cloud service where astronomers can safely use Jupyter notebooks over a personal space designed for high-performance processing under the high-availability principle. We show that features existing only in specific packages can be adapted to run in the notebooks, and that algorithms can be adapted to run across the data center without necessarily redesigning them."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Astronomy","Virtual Observatory"]

# Links (optional).
url_pdf = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Chilean Virtual Observatory", url = "http://chivo.cl"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "jovial.jpg"
caption = ""

+++
