---
title: 'Balanced distortion and perception in single-image super-resolution based on optimal transport in wavelet domain'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tianshan Liu
  - Rui Zhao
  - Kin-Man Lam

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'


date: '2021-08-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-08-13T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Neurocomputing 2021*
publication_short: In Neurocomputing

abstract: Single image super-resolution (SISR) is a classic ill-posed problem in computer vision. In recent years, deep-learning-based (DL-based) models have achieved promising results with the SISR problem. However, most existing methods suffer from an intrinsic trade-off between distortion and perceptual quality. To satisfy the requirements in different real-world situations, the balance of distortion and visual quality for image super-resolution is a critical issue. In DL-based models, the uses of hybrid loss (i.e., the combination of the distortion loss and the perceptual loss) and network interpolation are two common approaches to balancing the distortion and perceptual quality of super-resolved images. However, these two kinds of methods lack flexibility and hold strict constraints on network architectures. In this paper, we propose an image-fusion interpolation method for image super-resolution, which can balance the distortion and visual quality of super-resolved images, based on the optimal transport theory in the wavelet domain. The advantage of our proposed method is that it can be applied to any pretrained DL-based model, without any requirement from the network architecture and parameters. In addition, our proposed method is parameter-free and can run fast without using a GPU. Compared with existing state-of-the-art SISR methods, experiment results show that our proposed method can achieve a better balance between the distortion and visual quality in super-resolved images.

# Summary. An optional shortened abstract.
summary: In **Neurocomputing**, 2021

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1016/j.neucom.2021.08.073'
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
  caption: 'Image credit: [**Linzhu**](https://www.zhihu.com/people/yuexiaozhu)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
research:
  - offline_quadruped_jumping

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
