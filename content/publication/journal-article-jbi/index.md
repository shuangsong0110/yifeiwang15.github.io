---
draft: true
title: "Assessing fairness in machine learning models: A study of racial bias using matched counterparts in mortality prediction for patients with chronic diseases"
authors:
- admin
- Liqin Wang
- Zhengyang Zhou
- John Laurentiev
- Joshua R Lakin
- Li Zhou
- Pengyu Hong
author_notes: ""

date: "2024-06-11"
doi: "10.1016/j.jbi.2024.104677"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Biomedical Informatics"
publication_short: "JBI"

abstract: "Objective: Existing approaches to fairness evaluation often overlook systematic differences in the social determinants of health, like demographics and socioeconomics, among comparison groups, potentially leading to inaccurate or even contradictory conclusions. This study aims to evaluate racial disparities in predicting mortality among patients with chronic diseases using a fairness detection method that considers systematic differences. Methods: We created five datasets from Mass General Brigham’s electronic health records (EHR), each focusing on a different chronic condition: congestive heart failure (CHF), chronic kidney disease (CKD), chronic obstructive pulmonary disease (COPD), chronic liver disease (CLD), and dementia. For each dataset, we developed separate machine learning models to predict 1-year mortality and examined racial disparities by comparing prediction performances between Black and White individuals. We compared racial fairness evaluation between the overall Black and White individuals versus their counterparts who were Black and matched White individuals identified by propensity score matching, where the systematic differences were mitigated. Results: We identified significant differences between Black and White individuals in age, gender, marital status, education level, smoking status, health insurance type, body mass index, and Charlson comorbidity index (p-value <0.001). When examining matched Black and White subpopulations identified through propensity score matching, significant differences between particular covariates existed. We observed weaker significance levels in the CHF cohort for insurance type (p =0.043), in the CKD cohort for insurance type (p =0.005) and education level (p =0.016), and in the dementia cohort for body mass index (p =0.041); with no significant differences for other covariates. When examining mortality prediction models across the five study cohorts, we conducted a comparison of fairness evaluations before and after mitigating systematic differences. We revealed significant differences in the CHF cohort with p-values of 0.021 and 0.001 in terms of F1 measure and Sensitivity for the AdaBoost model, and p-values of 0.014 and 0.003 in terms of F1 measure and Sensitivity for the MLP model, respectively. Discussion and conclusion: This study contributes to research on fairness assessment by focusing on the examination of systematic disparities and underscores the potential for revealing racial bias in machine learning models used in clinical settings."

# Summary. An optional shortened abstract.
summary: "This study contributes to research on fairness assessment by focusing on the examination of systematic disparities and underscores the potential for revealing racial bias in machine learning models used in clinical settings."

tags:
- Fairness
- Electronic Health Records
- Mortality Prediction
- Machine Learning
- Chronic Disease
featured: false
# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S1532046424000959
url_code: ''
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
