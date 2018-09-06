+++
title = "Wrapping and Deploying Legacy Astronomical Code Into Python Environments: An applied Case Study"
date = 2017-10-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Martin Villanueva", "Camilo Valenzuela", "Manuel Sanchez", "Mauricio Araya"]

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
abstract = "Jupyter notebooks have proven to be a powerful tool for teaching science, because they handle executable code snippets, context environments, visualiza-tion, equations and explanatory text, all within the same web-interface. We propose extending its usage from teaching activities to science activities through the integration of astronomical libraries to the Jupyter environment and its execution as a cloud service. The remote execution of processing tasks through notebooks not only simplifies the usage of libraries, but enables Big Data processing on data centers while hiding the infrastructure and platform-dependent details. This allows moving computations closer to the data archives, executing tasks in a graphical yet non-blocking fashion, using high-performance computing routines transparently and working with very large data files without exhausting local memory. Moreover, a proper use of the notebooks produces self-documented, exportable and reproducible pipelines with graphical support. Our prototype uses Jupyter Hub as the base service, including Astropy, ACALib and CASAC libraries to the Python kernel, and we are currently porting CUPID (Star-link), MPICASA and ADMIT through suitable wrappers. The integration with the VO is twofold: through the data access layer services via VOTables, and through the application layer via the SAMP protocol. Besides including more libraries, the next steps are exploring the integration with Big Data frameworks such as Apache Spark, and the proper parallelization of the main algorithms of the libraries. To encourage its usage we also plan to assemble a lite distribution of JOVIAL to be used off-line."

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
