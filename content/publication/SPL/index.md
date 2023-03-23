---
title: 'Progressive Motion Representation Distillation With Two-Branch Networks for Egocentric Activity Recognition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tianshan Liu
  - Rui Zhao
  - admin
  - Kin-Man Lam

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'


date: '2020-07-22T00:00:00Z'
doi: '10.1109/LSP.2020.3011326'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-07-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Signal Processing Letter, 2020*
publication_short: In *SPL*

abstract: Video-based egocentric activity recognition involves fine-grained spatio-temporal human-object interactions. State-of-the-art methods, based on the two-branch-based architecture, rely on pre-calculated optical flows to provide motion information. However, this two-stage strategy is computationally intensive, storage demanding, and not task-oriented, which hampers it from being deployed in real-world applications. Albeit there have been numerous attempts to explore other motion representations to replace optical flows, most of the methods were designed for third-person activities, without capturing fine-grained cues. To tackle these issues, in this letter, we propose a progressive motion representation distillation (PMRD) method, based on two-branch networks, for egocentric activity recognition. We exploit a generalized knowledge distillation framework to train a hallucination network, which receives RGB frames as input and produces motion cues guided by the optical-flow network. Specifically, we propose a progressive metric loss, which aims to distill local fine-grained motion patterns in terms of each temporal progress level. To further enforce the proposed distillation framework to concentrate on those informative frames, we integrate a temporal attention mechanism into the metric loss. Moreover, a multi-stage training procedure is employed for the efficient learning of the hallucination network. Experimental results on three egocentric activity benchmarks demonstrate the state-of-the-art performance of the proposed method.
# Summary. An optional shortened abstract.
summary: In **Signal Processing Letter**, 2020.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '10.1109/LSP.2020.3011326'
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
