---
title: "Machine learning assisted Bayesian model comparison: learnt harmonic mean estimator"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jason D. McEwen
- Christopher G. R. Wallis
- Matthew A. Price
- admin

# Author notes (optional)
# author_notes:

date: "2022-01-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

abstract: We resurrect the infamous harmonic mean estimator for computing the marginal likelihood (Bayesian evidence) and solve its problematic large variance. The marginal likelihood is a key component of Bayesian model selection since it is required to evaluate model posterior probabilities; however, its computation is challenging. The original harmonic mean estimator, first proposed in 1994 by Newton and Raftery, involves computing the harmonic mean of the likelihood given samples from the posterior. It was immediately realised that the original estimator can fail catastrophically since its variance can become very large and may not be finite. A number of variants of the harmonic mean estimator have been proposed to address this issue although none have proven fully satisfactory. We present the learnt harmonic mean estimator, a variant of the original estimator that solves its large variance problem. This is achieved by interpreting the harmonic mean estimator as importance sampling and introducing a new target distribution. The new target distribution is learned to approximate the optimal but inaccessible target, while minimising the variance of the resulting estimator. Since the estimator requires samples of the posterior only it is agnostic to the strategy used to generate posterior samples. We validate the estimator on a variety of numerical experiments, including a number of pathological examples where the original harmonic mean estimator fails catastrophically. In all cases our learnt harmonic mean estimator is shown to be highly accurate. The estimator is computationally scalable and can be applied to problems of dimension \mathcal{O}(10^3) and beyond. Code implementing the learnt harmonic mean estimator is made publicly available.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [harmonic mean estimator, model comparison, Bayesian evidence, marginal likelihood]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Preprint
  url: https://arxiv.org/abs/2111.12720
# - name: DOI
#   url: ''

url_pdf: 'https://arxiv.org/pdf/2111.12720.pdf'
url_code: 'https://github.com/astro-informatics/harmonic'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
url_video: 'https://www.youtube.com/watch?v=RHoQItSA4J4'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- harmonic

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

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
