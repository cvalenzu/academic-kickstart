+++
title = "Towards Large-Scale RoI Indexing for Content-Aware Data Discovery"
date = 2017-10-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Mauricio Araya"
, "Rodrigo Caceres"
, "Lukas Gutierrez"
, "Marcelo Mendoza"
, "Carlos Ponce"
, "Camilo Valenzuela"]

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
abstract = "Data discovery within large archives is a key issue for modern astronomy: multi-source, multi-wavelength, multi-instrument and large-scale verifications need proper data discovery tools for filtering the very large datasets of observations available nowadays. The Virtual Observatory and file format standards have contributed to allow data discovery at the metadata level, where the filtering is circumscribed to what was explicitly annotated at the observation, calibration or data reduction stages. The next step is to perform data discovery at the content level, where content descriptors are automatically gathered from the observations to perform content-aware search. In a very general sense, this corresponds to automatically generate catalogs from large and diverse datasets. In this work, we consider the public spectroscopic data products from ALMA (fits cubes), and we apply the fast Region of Interest Seek and Extraction algorithm (RoiSE) to obtain content-descriptors of the spatial forms, positions, intensities and wavelengths of the source emissions. Despite the efficiency of the algorithm, it is impractical to process all the data in a batch/sequential manner. Then, the problem was to decide the tools and architecture to use for the task distribution across the datacenter. Between the several distributed/parallel computing alternatives, we selected the Dask packages to build the distributed pipeline that we outline in this paper, mainly because the current RoiSE implementation is written in Python. The main challenge of this pipeline is the diversity of data products: different resolutions, signal-to-noise ratios, densities, morphologies, imaging parameters, etc. Therefore, we include an adaptive parameter tuning mechanism to cope with this diversity. Finally, we present an example of content-aware data discovery over the obtained database."

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
url_pdf = "https://www.researchgate.net/profile/Mauricio_Araya2/publication/327023098_JOVIAL_Jupyter_OVerrIde_for_Astronomical_Libraries/links/5b73352345851546c9033095/JOVIAL-Jupyter-OVerrIde-for-Astronomical-Libraries.pdf?_sg%5B0%5D=bxC5nG4k2w9et8T3fIWfT-hUsmRjZyp-HaiZsQ0GRZfVLpOcQi1pKH58i1qTY-zBIJ_Aw4Xgkdq8bxJZd-9yBw.aGjcQ9-PNacH4PDzZ-BXtYFYjOWxaEsD84lDe5UXq9aAahhBgHb_fOWuVBOjvRF4t7zFmvK8Vvyl0iLvmeRNCQ&_sg%5B1%5D=NIYJDo9Zaeat3ynWK89Wklmlt-sKRq1hcWmraZf2chIhmc8naHdB_eC0ruuKnfBGxFvMwtnQKsWjYG1F6Z77qKif6Hkz1MABDZ4lxp25BfTO.aGjcQ9-PNacH4PDzZ-BXtYFYjOWxaEsD84lDe5UXq9aAahhBgHb_fOWuVBOjvRF4t7zFmvK8Vvyl0iLvmeRNCQ&_iepl="

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
