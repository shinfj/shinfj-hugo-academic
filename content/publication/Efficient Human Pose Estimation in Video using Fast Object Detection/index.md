---
title: 'Efficient Human Pose Estimation in Video using Fast Object Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Toshihiko Yamasaki
  - Kiyoharu Aizawa

# Author notes (optional)
author_notes:

date: '2016-03-10T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-12-08T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *The 78th National Convention of IPSJ*
publication_short: In *The 78th National Convention of IPSJ*

abstract: 本研究では、カーネル密度推定を用いて1フレーム中の複数の姿勢候補を統合するだけでなく、動画の時間連続性を考慮して前後フレームの姿勢推定結果も統合することで、より高精度に人物の姿勢推定を行う方法を提案する。さらに、高速に一般物体検出を行うための手法であるFaster R-CNNを用いてフレーム中の人物位置の特定を行うことにより、処理の高速化を図る。提案手法の有効性を確認するためにTED講演会で行われた複数の講演の動画に対して2つの既存手法と提案手法による推定を行った。結果として、提案手法はおよそ60%の精度で、既存手法に比べて3.4%~5.0%高精度に人物の姿勢推定を行うことができ、処理速度はおよそ2倍になることを示した。

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.dropbox.com/s/pnhiivxopypouo0/IPSJ_78.pdf?dl=0'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.dropbox.com/s/xx6av6zwrqc6k0t/IPSJ_78.pptx?dl=0'
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
