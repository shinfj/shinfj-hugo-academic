---
title: 'Stochastic Light Culling for Single Scattering in Participating Media'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yusuke Tokuyoshi
  - Takahiro Harada

# Author notes (optional)
author_notes:

date: '2022-04-01T00:00:00Z'
doi: '10.2312/egs.20221023'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "In *Eurographics 2022 Short Papers*"
publication_short: "In *EG 2022*"

abstract: We introduce a simple but efficient method to compute single scattering from point and arbitrarily shaped area light sources in participating media. Our method extends the stochastic light culling method to volume rendering by considering the intersection of a ray and spherical bounds of light influence ranges. For primary rays, this allows simple computation of the lighting in participating media without hierarchical data structures such as a light tree. First, we show how to combine equiangular sampling with the proposed light culling method in a simple case of point lights. We then apply it to arbitrarily shaped area lights by considering virtual point lights on the surface of area lights. Using our method, we are able to improve the rendering quality for scenes with many lights without tree construction and traversal.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
links:
- name: Supplemental
  url: 'https://www.dropbox.com/s/8jdj8xzvgn16os4/supplemental.pdf?dl=0'
- name: Publisher's official version
  url: 'https://diglib.eg.org/handle/10.2312/egs20221023'
url_pdf: 'https://gpuopen.com/download/publications/EG22_VolumeSlc.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.dropbox.com/s/rghuswli7cfe5pg/202204_Stochastic_Light_Culling_Volume.pdf?dl=0'
url_source: ''
url_video: 'https://www.dropbox.com/s/36yx8cljryaeoie/EG2022_StochasticLightCullingForSingleScattering.mp4?dl=0'

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
