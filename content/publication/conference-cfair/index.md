---
draft: true
title: 'Counterpart Fairness--Addressing Systematic between-group Differences in Fairness Evaluation'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zhengyang Zhou
  - Liqin Wang
  - John Laurentiev
  - Peter Hou
  - Li Zhou
  - Pengyu Hong

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - ''
  - ''
  - ''
  - ''
  - ''


date: '2024-11-19T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Neural Information Processing Systems Workshop: Algorithmic Fairness through the Lens of Metrics and Evaluation (AMFE 2024)"
publication_short: NIPS 2024 Workshop

abstract: When using machine learning (ML) to aid decision-making, it is critical to ensure that an algorithmic decision is fair and does not discriminate against specific individuals/groups, particularly those from underprivileged populations. Existing group fairness methods aim to ensure equal outcomes (such as loan approval rates) across groups delineated by protected variables like race or gender. However, these methods overlook the intricate, inherent differences among these groups that could influence outcomes. The confounding factors, which are non-protected variables but manifest systematic differences, can significantly affect fairness evaluation. Therefore, we recommend a more refined and comprehensive approach that accounts for both the systematic differences within groups and the multifaceted, intertwined confounding effects. We proposed a fairness metric based on counterparts (i.e., individuals who are similar with respect to the task of interest) from different groups, whose group identities cannot be distinguished algorithmically by exploring confounding factors. We developed a propensity-score-based method for identifying counterparts, avoiding the issue of comparing "oranges" with "apples". In addition, we introduced a counterpart-based statistical fairness index, called Counterpart-Fairness (CFair), to assess the fairness of ML models. Various empirical studies were conducted to validate the effectiveness of CFair.

# Summary. An optional shortened abstract.
summary: We analyzed the impact of systematic differences and biases in data collection on group fairness assessment and accordingly proposed a counterpart-based fairness evaluation index.
tags:
  - Fairness

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: ""

# Custom links
url_pdf: https://arxiv.org/pdf/2305.18160
url_code: https://github.com/zhengyjo/CFair
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---

<!-- > [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
