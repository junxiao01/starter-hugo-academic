---
title: 'Progressive and Selective Fusion Network for High Dynamic Range Imaging'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qian Ye
  - admin
  - Kin-Man Lam
  - Takayuki Okatani

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'


date: '2021-10-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-10-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *AMM Conference on Multimedia, 2021*
publication_short: In ACM-MM

abstract: This paper considers the problem of generating an HDR image of a scene from its LDR images. Recent studies employ deep learning and solve the problem in an end-to-end fashion, leading to significant performance improvements. However, it is still hard to generate a good quality image from LDR images of a dynamic scene captured by a hand-held camera, e.g., occlusion due to the large motion of foreground objects, causing ghosting artifacts. The key to success relies on how well we can fuse the input images in their feature space, where we wish to remove the factors leading to low-quality image generation while performing the fundamental computations for HDR image generation, e.g., selecting the best-exposed image/region. We propose a novel method that can better fuse the features based on two ideas. One is multi-step feature fusion; our network gradually fuses the features in a stack of blocks having the same structure. The other is the design of the component block that effectively performs two operations essential to the problem, i.e., comparing and selecting appropriate images/regions. Experimental results show that the proposed method outperforms the previous state-of-the-art methods on the standard benchmark tests.
# Summary. An optional shortened abstract.
summary: In **AMM Conference on Multimedia(ACM-MM)**, 2021.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2108.08585'
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
  caption: 'Image credit: [**Zhouyang**](https://www.researchgate.net/profile/Zhou-Yang-18/research)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
research:
  - construction_robot

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
