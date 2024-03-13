---
title: "Specifying multilevel mixture selection models in propensity score analysis"



authors:
- Jee-Seon Kim 
- Youmi Suk

author_notes:
- ""

date: "2019-05-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-05-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["application"]

# Publication name and optional abbreviated publication name.
publication: "*In Wiberg, M., Culpepper, S., Janssen, R., Gonzalez, J., & Molenaar, D *(Eds.), Quantitative psychology research: The 83rd annual meeting of the psychometric society *(pp. 279-291). New York, NY: Springer"
publication_short: ""

abstract: Causal inference with observational data is challenging, as the assignment to treatment is often not random and people may have different reasons to receive or to be assigned to the treatment. Moreover, the analyst may not have access to all of the important variables and may face omitted variable bias as well as selection bias in nonexperimental studies. It is known that fixed effects models are robust against unobserved cluster variables while random effects models provide biased estimates of model parameters in the presence of omitted variables. This study further investigates the properties of fixed effects models as an alternative to the common random effects models for identifying and classifying subpopulations or “latent classes” when selection or outcome processes are heterogeneous. A recent study by Suk and Kim (2018) found that linear probability models outperform standard logistic selection models in terms of the extraction of the correct number of latent classes, and the authors continue to search for optimal model specifications of mixture selection models across different conditions, such as strong and weak selection, various numbers of clusters and cluster sizes. It is found that fixed-effects models outperform random effects models in terms of classifying units and estimating treatment effects when cluster size is small.

# Summary. An optional shortened abstract.
summary: In conclusion, although RE LOGIT has been used as a natural extension of logistic regression for multilevel data, we can consider other approaches given the specific conditions of the data, such as heterogeneous selection or outcome processes, known or unknown homogenous group memberships, relative sizes of latent classes, strength of selection, the number of clusters, and cluster sizes. We can also use different models for the different steps of PSA; for example, RE LINEAR for class extraction and FE LOGIT for classification of units as different specifications have specific strengths. Finally, for real data analysis where the true selection mechanism is unknown, we can implement several specifications of models to compare their results, evaluate the validity of assumptions, and strengthen our inferences. For an empirical example of applying different multilevel mixture selection models to identify potentially heterogeneous ATEs, we refer to Suk and Kim in this volume.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-01310-3_25'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
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
slides: example
---

