---
draft: true
title: 'Precision Grounding: Augmenting Large Language Models with Evidence-Based Databases for Trustworthy Genetic Variant Summarization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xinsong Du
  - Anna Nagy
  - Michael F Oates
  - admin
  - Xinyi Wang
  - Joseph M Plasek
  - Samuel J Aronson
  - Matthew S Lebo
  - Li Zhou

# Author notes (optional)


date: '2025-06-09'
doi: '10.1101/2025.06.09.25329279'



# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: MedRxiv
publication_short: MedRxiv

abstract: "Backgrounds: Accurate interpretation of genetic variants is critical for precision medicine. While large language models (LLMs) show promise for summarization, they are prone to hallucinations. In this study, we thus propose a novel approach named “precision grounding” that augments LLMs with a query tool that integrated evidence-based, variant-specific information to improve summarization accuracy; Methods: Unlike traditional RAG methods that retrieve information via document embeddings from a vector database, precision grounding uses a domain-specific query tool to access evidence-based databases with unique identifiers. For variant summarization, we developed CATT, an open-source tool integrating ClinGen, ClinVar, and GenCC data. Users can query and retrieve curated evidence via Variation IDs to ground LLM outputs. We compared our approach to web grounding-based RAG using 50 expert-selected variants; Results: GPT-4o was selected due to its good performance on our task during a pilot test. Using GPT-4o, we found our precision grounding approach outperformed web-search grounding, achieving significantly higher accuracy and completeness scores, which were based on a 5-point Likert-Scale of 4.76 (+0.74) and 4.94 (+0.84), respectively. Error analysis revealed that precision grounding reduced clinically significant hallucinations, such as incorrect pathogenicity classification and summarizing the wrong variant; Conclusion: Precision grounding approach outperformed web-search grounding for genetic variant summarization. Our open-source tool, CATT, enables integration of curated, domain-specific knowledge and reduces hallucinations in LLM outputs."

# Summary. An optional shortened abstract.
summary: "LLMs are prone to generating inaccurate or misleading interpretation of genetic variants. To solve this, we propose a “precision grounding” approach that enhances LLM with publicly available evidence-based databases and resources identified by domain experts."

tags:
  - Large Language Model
  - Halluhallucination
# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://pmc.ncbi.nlm.nih.gov/articles/PMC12204447/'
url_code: 'https://shorturl.at/pw81X'
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
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
