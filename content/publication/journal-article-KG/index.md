---
draft: true
title: "Knowledgebra: An Algebraic Learning Framework for Knowledge Graph"
authors:
- Tong Yang
- admin
- Long Sha
- Jan Engelbrecht
- Pengyu Hong
author_notes: ""
date: "2022-05-03"
doi: "10.3390/make4020019"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-03T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Machine Learning and Knowledge Extraction"
publication_short: "MAKE"

abstract: "Knowledge graph (KG) representation learning aims to encode entities and relations into dense continuous vector spaces such that knowledge contained in a dataset could be consistently represented. Dense embeddings trained from KG datasets benefit a variety of downstream tasks such as KG completion and link prediction. However, existing KG embedding methods fell short to provide a systematic solution for the global consistency of knowledge representation. We developed a mathematical language for KG based on an observation of their inherent algebraic structure, which we termed as Knowledgebra. By analyzing five distinct algebraic properties, we proved that the semigroup is the most reasonable algebraic structure for the relation embedding of a general knowledge graph. We implemented an instantiation model, SemE, using simple matrix semigroups, which exhibits state-of-the-art performance on standard datasets. Moreover, we proposed a regularization-based method to integrate chain-like logic rules derived from human knowledge into embedding training, which further demonstrates the power of the developed language. As far as we know, by applying abstract algebra in statistical learning, this work develops the first formal language for general knowledge graphs, and also sheds light on the problem of neural-symbolic integration from an algebraic perspective."

# Summary. An optional shortened abstract.
summary: "We developed an algebraic framework for learning consistent relation embeddings in knowledge graphs and proposed an algebraic-based instantiation for a knowledge graph embedding model."

tags:
- Knowledge Graph
- Logic Reasoning
- Neural-symbolic Integration

featured: false
# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.mdpi.com/2504-4990/4/2/19'
url_code: 'https://github.com/yifeiwang15/Knowledgebra'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
