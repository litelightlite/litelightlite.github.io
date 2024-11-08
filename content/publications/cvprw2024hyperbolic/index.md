---
title: "A Fashion Item Recommendation Model in Hyperbolic Space"
authors:
- Ryotaro Shimizu
- Yu Wang
- Masanari Kimura
- admin
- Takashi Wada
- Yuki Saito
- Julian McAuley

date: "2024-09-04T10:30:11Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference paper']

# Publication name and optional abbreviated publication name.
publication: "Computer Vision and Pattern Recognition (CVPR) Workshops"
publication_short: "CVPR Workshops"

abstract: In this work, we propose a fashion item recommendation model that incorporates hyperbolic geometry into user and item representations. Using hyperbolic space, our model aims to capture implicit hierarchies among items based on their visual data and users’ purchase history. During training, we apply a multi-task learning framework that considers both hyperbolic and Euclidean distances in the loss function. Our experiments on three data sets show that our model performs better than previous models trained in Euclidean space only, confirming the effectiveness of our model. Our ablation studies show that multi-task learning plays a key role, and removing the Euclidean loss substantially deteriorates the model performance.


tags:
- recommendation system
- fashion

featured: true

url_pdf: https://openaccess.thecvf.com/content/CVPR2024W/CVFAD/papers/Shimizu_A_Fashion_Item_Recommendation_Model_in_Hyperbolic_Space_CVPRW_2024_paper.pdf

#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
