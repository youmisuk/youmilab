---
title: 'Designing optimal, data-driven policies from multisite randomized trials'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Chan Park.

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-10-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Psychometrika*
publication_short: In *Psychometrika*

abstract: Optimal treatment regimes (OTRs) have been widely employed in computer science and personalized medicine to provide data-driven, optimal recommendations to individuals. However, previous research on OTRs has primarily focused on settings that are independent and identically distributed, with little attention given to the unique characteristics of educational settings, where students are nested within schools and there are hierarchical dependencies. The goal of this study is to propose a framework for designing OTRs from multisite randomized trials, a commonly used experimental design in education and psychology to evaluate educational programs. We investigate modifications to popular OTR methods, specifically Q-learning and weighting methods, in order to improve their performance in multisite randomized trials. A total of 12 modifications, 6 for Q-learning and 6 for weighting, are proposed by utilizing different multilevel models, moderators, and augmentations. Simulation studies reveal that all Q-learning modifications improve performance in multisite randomized trials and the modifications that incorporate random treatment effects show the most promise in handling cluster-level moderators. Among weighting methods, the modification that incorporates cluster dummies into moderator variables and augmentation terms performs best across simulation conditions. The proposed modifications are demonstrated through an application to estimate an OTR of conditional cash transfer programs using a multisite randomized trial in Colombia to maximize educational attainment.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/article/10.1007/s11336-023-09937-2'
url_code: 'https://github.com/youmisuk/multisiteOTR'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
url_preprint: 'https://osf.io/preprints/psyarxiv/me5gb'

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

