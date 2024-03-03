---
title: 'Tuning random forests for causal inference under cluster-level unmeasured confounding'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hyunseung Kang

# Author notes (optional)
author_notes:
  - ''
  - ''

date: '2022-02-01 T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-02-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Multivariate Behavioral Research*
publication_short: In *Multivariate Behavioral Research*

abstract: Recently, there has been growing interest in using machine learning methods for causal inference due to their automatic and flexible ability to model the propensity score and the outcome model. However, almost all the machine learning methods for causal inference have been studied under the assumption of no unmeasured confounding and there is little work on handling omitted/unmeasured variable bias. This paper focuses on a machine learning method based on random forests known as Causal Forests and presents five simple modifications for tuning Causal Forests so that they are robust to cluster-level unmeasured confounding. Our simulation study finds that adjusting the default tuning procedure with the propensity score from fixed effects logistic regression or using variables that are centered to their cluster means produces estimates that are more robust to cluster-level unmeasured confounding. Also, when these parametric propensity score models are mis-specified, our modified machine learning methods remain robust to bias from cluster-level unmeasured confounders compared to existing parametric approaches based on propensity score weighting. We conclude by demonstrating our proposals in a real data study concerning the effect of taking an eighth-grade algebra course on math achievement scores from the Early Childhood Longitudinal Study.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.tandfonline.com/doi/abs/10.1080/00273171.2021.1994364'
url_code: 'https://osf.io/preprints/psyarxiv/36w72'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
url_preprint: 'https://osf.io/preprints/psyarxiv/36w72'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

