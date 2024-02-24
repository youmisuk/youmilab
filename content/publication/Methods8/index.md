---
title: 'Random forests approach for causal inference with clustered observational data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Hyunseung Kang
  - Jee Seon Kim

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2020-08-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-28T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Multivariate Behavioral Research*
publication_short: In *Multivariate Behavioral Research*

abstract: There is a growing interest in using machine learning (ML) methods for causal inference due to their (nearly) automatic and flexible ability to model key quantities such as the propensity score or the outcome model. Unfortunately, most ML methods for causal inference have been studied under single-level settings where all individuals are independent of each other and there is little work in using these methods with clustered or nested data, a common setting in education studies. This paper investigates using one particular ML method based on random forests known as Causal Forests to estimate treatment effects in multilevel observational data. We conduct simulation studies under different types of multilevel data, including two-level, three-level, and cross-classified data. Our simulation study shows that when the ML method is supplemented with estimated propensity scores from multilevel models that account for clustered/hierarchical structure, the modified ML method outperforms preexisting methods in a wide variety of settings. We conclude by estimating the effect of private math lessons in the Trends in International Mathematics and Science Study data, a large-scale educational assessment where students are nested within schools.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.tandfonline.com/doi/full/10.1080/00273171.2020.1808437'
url_code: 'https://github.com/youmisuk/multilevelCF'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
url_preprint: 'https://osf.io/preprints/psyarxiv/xgq2k'

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

