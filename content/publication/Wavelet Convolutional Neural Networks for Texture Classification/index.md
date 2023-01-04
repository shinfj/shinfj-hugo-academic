---
title: "Wavelet Convolutional Neural Networks for Texture Classification"
authors:
- admin
- Kohei Takayama
- Toshiya Hachisuka
date: "2017-07-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-12-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "In *arXiv*"
publication_short: "In *arXiv*"

abstract: Texture classification is an important and challenging problem in many image processing applications. While convolutional neural networks (CNNs) achieved significant successes for image classification, texture classification remains a difficult problem since textures usually do not contain enough information regarding the shape of object. In image processing, texture classification has been traditionally studied well with spectral analyses which exploit repeated structures in many textures. Since CNNs process images as-is in the spatial domain whereas spectral analyses process images in the frequency domain, these models have different characteristics in terms of performance. We propose a novel CNN architecture, wavelet CNNs, which integrates a spectral analysis into CNNs. Our insight is that the pooling layer and the convolution layer can be viewed as a limited form of a spectral analysis. Based on this insight, we generalize both layers to perform a spectral analysis with wavelet transform. Wavelet CNNs allow us to utilize spectral information which is lost in conventional CNNs but useful in texture classification. The experiments demonstrate that our model achieves better accuracy in texture classification than existing models. We also show that our model has significantly fewer parameters than CNNs, making our model easier to train with less memory.

# Summary. An optional shortened abstract.
summary:

tags:
featured: false

links:
- name: arXiv
  url: 'https://arxiv.org/abs/1707.07394'
url_pdf: 'http://arxiv.org/pdf/1512.04133v1'
url_code: 'https://github.com/shinfj/WaveletCNN_for_TextureClassification'
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
