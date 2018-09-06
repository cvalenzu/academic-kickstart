+++
title = "The ChiVO Library: advanced computational methods for astronomy"
date = 2015-10-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Mauricio Araya"
, "Mauricio Solar"
, "Diego Mardones"
, "Luis Arevalo"
, "Marcelo Mendoza"
,"Camilo Valenzuela"
, "Teodoro Hochfärber"
, "Martín Villanueva"
 ,"Marcelo Jara "
, "Axel Simonsen"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Astronomical Data Analysis Software and Systems*."
publication_short = "In *ADASS*"

# Abstract and optional shortened version.
abstract = "The main objective of the Advanced Computational Astronomy Library (ACALib) is to ensemble a coherent software package with the research on computational methods for astronomy performed by the first phase of the Chilean Virtual Observatory between years 2013 and 2015. During this period, researchers and students developed functional prototypes, implementing state of the art computational methods and proposing new algorithms and techniques. This research was mainly focused on spectroscopic data cubes, as they strongly require computational methods to reduce, visualize and infer astrophysical quantities from them, and because most of the techniques are directly applicable either to images or to spectra. The ACALib philosophy is to use a persistent workspace abstraction where spec-troscopic data cubes can be loaded from files, created from other cubes or artificially generated from astrophysical parameters. Then, computational methods can be applied to them, resulting in new data cube instances or new data tables in the workspace. The idea is to provide not only API bindings for the workspace and the cubes, but also web-services to use the library in cloud-based frameworks and in the Virtual Observatory. In a nutshell, ACALib is integrating and testing several cube manipulation routines , stacking procedures, structure detection algorithms, spectral line association techniques and a synthetic data cube generation module. The library is developed in python, strongly rooted in astropy modules and using efficient numerical libraries such as numpy and scipy, and machine learning libraries like scikitlearn and astroML. In the near future, we plan to propose ACALib as an astropy affiliated package, and to create a CASA add-on to ease the usage of our methods. Also, we are exploring bleeding-edge computational methods to include to ACALib, such as deep learning networks, and developing new prototypes for other types of astronomical data, such as light curves in the time-domain."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

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
url_pdf = "https://www.researchgate.net/profile/Mauricio_Araya2/publication/327023130_The_ChiVO_Library_advanced_computational_methods_for_astronomy/links/5b733703a6fdcc87df7a251c/The-ChiVO-Library-advanced-computational-methods-for-astronomy.pdf?_sg%5B0%5D=H5RN_1X9ekHHeA1fFS1E5baPFcQlusEsdb9-nVa82G7YvHo_RWrruPKqBsUh6HAXIbyJAfaJTGHpoFQeS5hIcg.J4dWzIQvM05ZS5jjIZECcx2D2EpdJJWkYmaieVBFkX7Gnu-HXKL-uq_yZw-hOWOscMiP9VDBrrsb_BwLAPxnWA&_sg%5B1%5D=ns_SNmmM0IFxaK8w2YsVWQHwm9l_RLmV79bLEJhm5cvSF6oFkH9AccMT3NwjAqE1xMuOJn5-s10Ym1vA28FaOH_pdf6BqnbC4mwLClQKN5IY.J4dWzIQvM05ZS5jjIZECcx2D2EpdJJWkYmaieVBFkX7Gnu-HXKL-uq_yZw-hOWOscMiP9VDBrrsb_BwLAPxnWA&_iepl="

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
image = ""
caption = ""

+++
