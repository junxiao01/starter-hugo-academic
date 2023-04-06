---
title: 'Bayesian sparse hierarchical model for image denoising'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Rui Zhao
  - Kin-Man Lam

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'


date: '2021-04-20T00:00:00Z'
doi: 'https://doi.org/10.1016/j.image.2021.116299'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-04-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2021*
publication_short: In Signal Processing:Image Communication

abstract: Sparse models and their variants have been extensively investigated, and have achieved great success in image denoising. Compared with recently proposed deep-learning-based methods, sparse models have several advantages:(1) Sparse models do not require a large number of pairs of noisy images and the corresponding clean images for training. (2) The performance of sparse models is less reliant on the training data, and the learned model can be easily generalized to natural images across different noise domains. In sparse models, L0 norm penalty makes the problem highly non-convex, which is difficult to be solved. Instead, L1 norm penalty is commonly adopted for convex relaxation, which is considered as the Laplacian prior from the Bayesian perspective. However, many previous works have revealed that L1 norm regularization causes a biased estimation for the sparse code, especially for high-dimensional data, e.g., images. In this paper, instead of using the L1 norm penalty, we employ an improper prior in the sparse model and formulate a hierarchical sparse model for image denoising. Compared with other competitive methods, experiment results show that our proposed method achieves a better generalization for images with different characteristics across various domains, and achieves state-of-the-art performance for image denoising on several benchmark datasets.
# Summary. An optional shortened abstract.
summary: In **Signal Processing:Image Communication**, 2021.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1109/ICASSP39728.2021.9413846'
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
