---
title: 'Which Company Adjustment Matter? Insights from Uplift Modeling on Financial Health'
authors:
- admin
- Mats Brorsson
# author_notes:
# - 'Equal contribution'
# - 'Equal contribution'
date: '2024-09-01T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2506.19049'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Midas@ECML-PKDD*
publication_short: In *ECML-PKDD*

abstract: |
  Uplift modeling has achieved significant success in various fields, particularly in online marketing. It is a method that primarily utilizes machine learning and deep learning to estimate individual treatment effects. This paper we apply uplift modeling to analyze the effect of company adjustment on their financial status, and we treat these adjustment as treatments or interventions in this study. Although there have been extensive studies and application regarding binary treatments, multiple treatments, and continuous treatments, company adjustment are often more complex than these scenarios, as they constitute a series of multiple time-dependent actions. The effect estimation of company adjustment needs to take into account not only individual treatment traits but also the temporal order of this series of treatments. This study collects a real-world data set about company financial statements and reported behavior in Luxembourg for the experiments. First, we use two meta-learners and three other well-known uplift models to analyze different company adjustment by simplifying the adjustment as binary treatments. Furthermore, we propose a new uplift modeling framework (MTDnet) to address the time-dependent nature of these adjustment, and the experimental result shows the necessity of considering the timing of these adjustment.

# Summary. An optional shortened abstract.
summary: |
  This paper applies uplift modeling to assess the impact of company adjustments on financial status, proposing a new framework (MTDnet) that accounts for the time-dependent nature of these actions and demonstrating that the timing of adjustments significantly influences their effectiveness.











tags:
- Causal Inference
- Deep Learning
featured: True

# links:
# - name: ''
#   url: ''
url_pdf: 'https://www.arxiv.org/pdf/2506.19049'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/a-bicycle-sign-lies-on-the-ground-4F4p30xJumE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
