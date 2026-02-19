---
draft: true
title: 'AI-assisted literature screening: A hybrid approach using large language models and retrieval-augmented generation'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yiming Li
  - Xinsong Du
  - admin
  - Xinyu Chen
  - Zhengyang Zhou
  - John Lian
  - Ya-Wen Chuang
  - Pengyu Hong
  - Peter C. Hou
  - Li Zhou

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-11-30T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-11-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: International Journal of Medical Informatics
publication_short: IJMEDI

abstract: "Objective: Current systematic literature reviews largely rely on manual screening of articles retrieved through keyword search, which is time-consuming and difficult to scale. To address this limitation, large language model (LLM)-based approaches offer the potential to automate the screening process. In this study, we aim to enhance the efficiency and accuracy of literature screening by developing an LLM-based method and exploring techniques such as rule-based preprocessing, prompt engineering (i.e., retrieval-augmented generation (RAG)) and ensemble strategies. Methods: We explored a hybrid framework that combines RAG prompting with LLM-based classification strategies. Our methods were developed and evaluated on a corpus of 6331 biomedical articles, focusing on identifying literature discussing the applications of LLMs in patient care using Electronic Health Record (EHR) data. We evaluated three recent models-DeepSeek-V3, Deepseek-R1 and GPT-4o under three prompting strategies: binary classification prompting, RAG prompting, and justification-based prompting. Given the context of literature screening, recall (sensitivity) was prioritized in this study to maximize the inclusion of relevant studies. Additionally, we also considered other metrics, including precision, specificity, and negative predictive value (NPV) to minimize the inclusion of irrelevant articles. To evaluate generalizability, the models and prompts were further tested on ten additional topics related to Cancer Immunotherapy and Targeted Therapy and LLMs in Medicine. Results: The hybrid approach combining rule-based preprocessing with DeepSeek R1 using RAG prompting (rule + DeepSeek-reasoner@Prompt II) achieved the best overall performance among individual models, with a precision of 0.34, recall of 0.77, NPV of 1.00, and g-mean of 0.87. Ensemble methods outperformed this approach greatly in precision, achieving a perfect score of 1.00 in the main use case, but showed comparable performance across other metrics, with the exception of F1. In generalizability tests, DeepSeek-R1 achieved the highest F1-score (0.93) and accuracy (0.88) across additional topics, whereas ensemble methods did not show substantial improvement. Conclusion: This study introduces a LLM-based approach that integrates RAG prompting and ensemble strategies to enhance literature screening, offering substantial gains in accuracy and scalability. The findings establish a foundation for advancing LLM-driven evidence synthesis in biomedical research and clinical decision support."

# Summary. An optional shortened abstract.
summary: "This study aims to improve literature screening efficiency and accuracy by developing an LLM-based approach that incorporates rule-based preprocessing, prompt engineering (including RAG), and ensemble techniques."
tags:
  - Large Language Model
  - AI For Healthcare

# Display this page in the Featured widget?
featured: False

# Standard identifiers for auto-linking
doi: 10.1016/j.ijmedinf.2025.106205

# Custom links
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S1386505625004228?via%3Dihub
  # - type: code
  #   url: https://github.com/yifeiwang15/ACML
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
