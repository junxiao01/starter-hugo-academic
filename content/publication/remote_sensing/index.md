---
title: 'Boosting Object Detectors via Strong-Classification Weak-Localization Pretraining in Remote Sensing Imagery'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Cong Zhang
  - Tianshan Liu
  - admin
  - Kin-Man Lam
  - Qi Wang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'


date: '2023-01-13T00:00:00Z'
doi: 'https://doi.org/10.1109/TIM.2023.3315392'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-13T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In IEEE Transactions on Instrumentation and Measurement 2023
publication_short: In IEEE Transactions on Instrumentation and Measurement (TIM)

abstract: Deep learning-based object detectors in remote sensing (RS) scenarios typically follow the paradigm of pretraining and fine-tuning to alleviate the limitation of insufficient downstream data. Despite the improved performance, existing pretraining paradigms are suboptimal due to three deficiencies, 1) inconsistent domains, i.e., pretraining on natural scenes and fine-tuning for RS scenes; 2) mismatched task objectives, i.e., classification-oriented pretraining while detection-oriented fine-tuning; and 3) misaligned architectures, i.e., pretraining only one bare backbone yet neglecting other vital detection components. Against these issues, this article proposes a novel pretraining paradigm specifically for the task of RS object detection, namely, RS strong-classification weak-localization (SCWL) pretraining. Unlike conventional classification pretraining, such as the widely used ImageNet pretraining, our pretraining strategy can adaptively perform bounding box generation on a reconstructed large-scale RS classification-style dataset. These pseudobounding boxes are integrated with the original accurate class labels as location- and category-related supervisions, respectively, to pretrain the entire RS detectors. The proposed RS SCWL pretraining paradigm is able to significantly improve downstream detection performance and outperforms classification pretraining methods, including ImageNet pretraining. Extensive experiments on different object detection datasets demonstrate its effectiveness and superiority in boosting various RS detectors.

summary: In **IEEE Transactions on Instrumentation and Measurement (TIM)**, 2023. 
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1109/TIM.2023.3315392'
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
  caption: 'Image credit: [**HongBo**](https://github.com/LifelongYuan)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
research:
  - RL-Based Locomotion Control

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
