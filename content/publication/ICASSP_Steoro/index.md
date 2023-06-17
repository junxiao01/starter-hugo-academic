---
title: 'Efficient Feature Fusion for Learning-based Photometric Stereo'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yakun Ju
  - Kin-Man Lam
  - admin
  - Cong Zhang
  - Cuixin Yang
  - Junyu Dong

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'


date: '2023-01-10T00:00:00Z'
doi: 'https://doi.org/10.1109/ICASSP49357.2023.10095806'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2023*
publication_short: In ICASSP

abstract: How to handle an arbitrary number for input images is a fundamental problem of learning-based photometric stereo methods. Existing approaches adopt max-pooling or observation map to fuse an arbitrary number of extracted features. However, these methods discard a large amount of the features from the input images, impacting the utilization and accuracy, or ignore the constraints from the intra-image spatial domain. In this paper, we explore how to efficiently fuse features from a variable number of input images. First, we propose a bilateral extraction module, which categorizes features into positive and negative, to maximally keep the useful feature in the fusion stage. Second, we adopt a top-k pooling to both the bilateral information, which selects the k maximum response value from all features. These two modules proposed are "plug-and-play" and can be used in different fusion tasks. We further propose a hierarchical photometric stereo network, namely HPS-Net, to handle bilateral extraction and top-k pooling for multiscale features. Experiments in the widely used benchmark illustrate the improvement of our proposed framework in the conventional max-pooling method and the proposed HPS-Net outperforms existing learning-based photometric stereo methods.

# Summary. An optional shortened abstract.
summary: In **IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)**, 2023.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1109/ICASSP49357.2023.10095806'
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
