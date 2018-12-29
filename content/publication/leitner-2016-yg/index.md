+++
title = "Modelling and Managing Deployment Costs of Microservice-based Cloud Applications"

selected = false
draft = false

# Posting date, Publication date
date = 2016-12-06

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Philipp Leitner", "Juergen Cito", "Emanuel Stoeckli"]

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

# Abstract and optional shortened version.
abstract = "We present an approach to model the deployment costs, including compute and IO costs, of Microservice-based applications deployed to a public cloud. Our model, which we dubbed CostHat, supports both, Microservices deployed on traditional IaaS or PaaS clouds, and services that make use of novel cloud programming paradigms, such as AWS Lambda. CostHat is based on a network model, and allows for what-if and cost sensitivity analysis. Further, we have used this model to implement tooling that warns cloud developers directly in the Integrated Development Environment (IDE) about certain classes of potentially costly code changes. We illustrate our work based on a case study, and evaluate the CostHat model using a standalone Python implementation. We show that, once instantiated, cost calculation in CostHat is computationally inexpensive on standard hardware (below 1 ms even for applications consisting of thousand services and endpoints). This enables its use in real-time for developer tooling which continually re-evaluates the costs of an application in the background, while the developer is working on the code."
abstract_short = ""

# Publication name and optional abbreviated version.
publication = "*Proceedings of the 9th International Conference on Utility and Cloud Computing*"
publication_short = ""

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Cloud Computing", "Cost Predictions", "Serverless", "Microservices", "Integrated-Development Environment"]

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
url_custom = [{name = "ACM", url = "http://doi.acm.org/10.1145/2996890.2996901"}, {name = "IEEE Xplore", url = "https://ieeexplore.ieee.org/abstract/document/7881628/"}, {name = "UNISG Alexandria", url = "https://www.alexandria.unisg.ch/250955/"}]

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1145/2996890.2996901"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

+++
