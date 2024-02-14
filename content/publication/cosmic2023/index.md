---
title: "Fast emulation of anisotropies induced in the cosmic microwave background by cosmic strings"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Matthew A. Price
- Matthijs Mars
- admin
- Alessio Spurio Mancini
- Augustin Marignier
- Jason D. McEwen

# Author notes (optional)
# author_notes:

date: "2023-10-04T00:00:00Z"
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

abstract: Cosmic strings are linear topological defects that may have been produced during symmetry-breaking phase transitions in the very early Universe. In an expanding Universe the existence of causally separate regions prevents such symmetries from being broken uniformly, with a network of cosmic string inevitably forming as a result. To faithfully generate observables of such processes requires computationally expensive numerical simulations, which prohibits many types of analyses. We propose a technique to instead rapidly emulate observables, thus circumventing simulation. Emulation is a form of generative modelling, often built upon a machine learning backbone. End-to-end emulation often fails due to high dimensionality and insufficient training data. Consequently, it is common to instead emulate a latent representation from which observables may readily be synthesised. Wavelet phase harmonics are an excellent latent representations for cosmological fields, both as a summary statistic and for emulation, since they do not require training and are highly sensitive to non-Gaussian information. Leveraging wavelet phase harmonics as a latent representation, we develop techniques to emulate string induced CMB anisotropies over a 7.2 degree field of view, with sub-arcminute resolution, in under a minute on a single GPU. Beyond generating high fidelity emulations, we provide a technique to ensure these observables are distributed correctly, providing a more representative ensemble of samples. The statistics of our emulations are commensurate with those calculated on comprehensive Nambu-Goto simulations. Our findings indicate these fast emulation approaches may be suitable for wide use in, e.g., simulation based inference pipelines. We make our code available to the community so that researchers may rapidly emulate cosmic string induced CMB anisotropies for their own analysis. 


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [harmonic mean estimator, model comparison, Bayesian evidence, marginal likelihood]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Preprint
  url: https://arxiv.org/abs/2307.04798
# - name: DOI
#   url: ''

url_pdf: 'https://arxiv.org/pdf/2307.04798.pdf'
# url_code: 'https://github.com/astro-informatics/harmonic'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: 'https://www.youtube.com/watch?v=RHoQItSA4J4'

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
- 

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
