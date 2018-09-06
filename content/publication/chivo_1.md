+++
title = "Chilean Virtual Observatory services implementation for the ALMA public data"
date = 2014-01-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jonathan Antognini", "Mauricio Solar", "Jorge Ibsen","Mauricio Araya","Lars Nyman","Diego Mardones", "Camilo Valenzuela","Patricio Ramirez","Christopher Fernandez","Mario Garces"]

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
publication = "In *The International Society for Optical Engineering*."
publication_short = "In *SPIE*"

# Abstract and optional shortened version.
abstract = "Currently, the standards and protocols for data access in the Virtual Observatory architecture (DAL) are generally implemented with relational databases based on SQL. In particular, the Astronomical Data Query Language (ADQL), language used by IVOA to represent queries to VO services, was created to satisfy the different data access protocols, such as Simple Cone Search. ADQL is based in SQL92, and has extra functionality implemented using PgSphere. An emergent alternative to SQL are the so called NoSQL databases, which can be classified in several categories such as Column, Document, Key-Value, Graph, Object, etc.; each one recommended for different scenarios. Within their notable characteristics we can find: schema-free, easy replication support, simple API, Big Data, etc. The Chilean Virtual Observatory (ChiVO) is developing a functional prototype based on the IVOA architecture, with the following relevant factors: Performance, Scalability, Flexibility, Complexity, and Functionality. Currently, it's very difficult to compare these factors, due to a lack of alternatives. The objective of this paper is to compare NoSQL alternatives with SQL through the implementation of a Web API REST that satisfies ChiVO's needs: a SESAME-style name resolver for the data from ALMA. Therefore, we propose a test scenario by configuring a NoSQL database with data from different sources and evaluating the feasibility of creating a Simple Cone Search service and its performance. This comparison will allow to pave the way for the application of Big Data databases in the Virtual Observatory."

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
url_pdf = "https://www.researchgate.net/profile/Mauricio_Solar/publication/266617043_Chilean_Virtual_Observatory_services_implementation_for_the_ALMA_public_data/links/5970fec24585153016391e1e/Chilean-Virtual-Observatory-services-implementation-for-the-ALMA-public-data.pdf?_sg%5B0%5D=QLf1bdPt1MTRhDjNTtXR4orwo2e8p5AeEaPa_YRaouLkIaQtyutk1BRs922A5x8C61RQAq_KfOOp_FoUkh26Yg.APNs6PyrXRtOmvTK0aknf-S3rX7ATBEUC63VJvv-JPBWMQggMSJu7XSji6Or60opQCmqU63FnmY_sovj5V4dXg&_sg%5B1%5D=vlodNIWLzYGrESwMZ21UfZFGOGqQLXCtOef6InA_mTCDjBmC_ble3NijRqkq7UYDKde5UibCsLA5QF6yzfFp7NiVkrvWP0Z1FyMlHEYZQBqS.APNs6PyrXRtOmvTK0aknf-S3rX7ATBEUC63VJvv-JPBWMQggMSJu7XSji6Or60opQCmqU63FnmY_sovj5V4dXg&_iepl="

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
