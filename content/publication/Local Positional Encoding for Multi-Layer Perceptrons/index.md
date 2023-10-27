---
title: 'Local Positional Encoding for Multi-Layer Perceptrons'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Atsushi Yoshimura
  - Takahiro Harada

# Author notes (optional)
author_notes:

date: '2023-10-01T00:00:00Z'
doi: '10.2312/pg.20231273'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "In *PG2023 Short Papers and Posters*"
publication_short: "In *PG '23*"

abstract: A multi-layer perceptron (MLP) is a type of neural networks which has a long history of research and has been studied actively recently in computer vision and graphics fields. One of the well-known problems of an MLP is the capability of expressing highfrequency signals from low-dimensional inputs. There are several studies for input encodings to improve the reconstruction quality of an MLP by applying pre-processing against the input data. This paper proposes a novel input encoding method, local positional encoding, which is an extension of positional and grid encodings. Our proposed method combines these two encoding techniques so that a small MLP learns high-frequency signals by using positional encoding with fewer frequencies under the lower resolution of the grid to consider the local position and scale in each grid cell. We demonstrate the effectiveness of our proposed method by applying it to common 2D and 3D regression tasks where it shows higher-quality results compared to positional and grid encodings, and comparable results to hierarchical variants of grid encoding such as multi-resolution grid encoding with equivalent memory footprint.

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Supplemental
  url: 'https://diglib.eg.org/bitstream/handle/10.2312/pg20231273/paper1117_mm.pdf?sequence=2&isAllowed=y'
url_pdf: 'https://arxiv.org/abs/2309.15101'
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
