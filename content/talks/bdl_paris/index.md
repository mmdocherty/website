---
title: Bayesian model comparison for simulation-based inference

event: Bayesian deep learning for cosmology and time domain astrophysics conference
event_url: https://example.org

location: Paris, France
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Conference talk at BDL Paris.
abstract: "Simulation-based inference techniques will play a key role in the analysis of upcoming astronomical
surveys, providing a statistically rigorous method for Bayesian parameter estimation. However,
these techniques do not provide a natural way to perform Bayesian model comparison, as they do
not have access to the Bayesian model evidence.
In my talk I will present a novel method to estimate the Bayesian model evidence in a simulation-
based inference scenario, which makes use of the learnt harmonic mean estimator. We recently
implemented this method in a public software package, HARMONIC, which allows one to obtain esti-
mates of the evidence from posterior distribution samples, irrespective of the method used to sample
the posterior distribution. I will showcase the performance of HARMONIC in multiple simulation-
based inference scenarios where the estimated evidence can be compared with exact analytical re-
sults, including an example of model selection in the analysis of gravitational waveforms.
The versatility of the model evidence estimation framework provided by HARMONIC, coupled with
the robustness of simulation-based inference techniques, creates a new complete Bayesian pipeline
for parameter estimation and model comparison from next-generation astronomical surveys."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-06-22T10:20:00Z"
date_end: "2022-06-22T10:40:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-06-22T00:00:00Z"

authors: [admin]
tags: [Bayesian model comparison, simulation-based inference, gravitational waves]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/mdochertyastro
url_code: "https://github.com/astro-informatics/harmonic"
# url_pdf: "slides/bdl_paris.pdf"
url_slides: "slides/bdl_paris.pdf"
url_video: "https://www.youtube.com/watch?v=YBECAHFurGc&list=PLywBH0_7tBJ9BG2nKodRdn6ReDaW075gM&index=35&t=414s"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- harmonic_sbi
---

<!-- Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
