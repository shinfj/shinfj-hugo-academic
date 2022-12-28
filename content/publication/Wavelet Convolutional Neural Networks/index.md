---
title: "Wavelet Convolutional Neural Networks"
authors:
- admin
- Kohei Takayama
- Toshiya Hachisuka
date: "2018-05-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "In *arXiv*"
publication_short: "In *arXiv*"

abstract: Spatial and spectral approaches are two major approaches for image processing tasks such as image classification and object recognition. Among many such algorithms, convolutional neural networks (CNNs) have recently achieved significant performance improvement in many challenging tasks. Since CNNs process images directly in the spatial domain, they are essentially spatial approaches. Given that spatial and spectral approaches are known to have different characteristics, it will be interesting to incorporate a spectral approach into CNNs. We propose a novel CNN architecture, wavelet CNNs, which combines a multiresolution analysis and CNNs into one model. Our insight is that a CNN can be viewed as a limited form of a multiresolution analysis. Based on this insight, we supplement missing parts of the multiresolution analysis via wavelet transform and integrate them as additional components in the entire architecture. Wavelet CNNs allow us to utilize spectral information which is mostly lost in conventional CNNs but useful in most image processing tasks. We evaluate the practical performance of wavelet CNNs on texture classification and image annotation. The experiments show that wavelet CNNs can achieve better accuracy in both tasks than existing models while having significantly fewer parameters than conventional CNNs.

# Summary. An optional shortened abstract.
summary:

tags:
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1805.08620
url_pdf: https://arxiv.org/pdf/1805.08620.pdf
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
slides: ""
---
