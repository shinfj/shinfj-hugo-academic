---
title: 'Progressive Material Caching'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Takahiro Harada

# Author notes (optional)
author_notes:

date: '2022-12-01T00:00:00Z'
doi: '10.1145/3550340.3564223'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "In *SIGGRAPH Asia 2022 Technical Communications*"
publication_short: "In *SA '22*"

abstract: The evaluation of material networks is a relatively resource-intensive process in the rendering pipeline. Modern production scenes can contain hundreds or thousands of complex materials with massive networks, so there is a great demand for an efficient way of handling material networks. In this paper, we introduce an efficient method for progressively caching the material nodes without an overhead on the rendering performance. We evaluate the material networks as usual in the rendering process. Then, the output value of part of the network is stored in a cache and can be used in the evaluation of the next materials. Using our method, we can render the scene with performance equal to or better than that of the method without caching, with a slight difference in the images rendered with caching and without it.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Supplemental
  url: 'https://dl.acm.org/action/downloadSupplement?doi=10.1145%2F3550340.3564223&file=SA2022_ProgressiveMaterialCache_supplemental.pdf'
- name: Publisher's official version
  url: 'https://dl.acm.org/doi/pdf/10.1145/3550340.3564223'
url_pdf: 'https://gpuopen.com/download/publications/SA2022_ProgressiveMaterialCache.pdf'
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
