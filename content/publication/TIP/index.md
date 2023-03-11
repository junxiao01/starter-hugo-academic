---
title: 'Invertible image decolorization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Rui Zhao
  - Tianshan Liu
  - admin
  - Kin-Man Lam

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'


date: '2021-07-20T00:00:00Z'
doi: '10.1109/TIP.2021.3091902'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-07-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Image Processing, 2021*
publication_short: In *TIP*

abstract: Invertible image decolorization is a useful color compression technique to reduce the cost in multimedia systems. Invertible decolorization aims to synthesize faithful grayscales from color images, which can be fully restored to the original color version. In this paper, we propose a novel color compression method to produce invertible grayscale images using invertible neural networks (INNs). Our key idea is to separate the color information from color images, and encode the color information into a set of Gaussian distributed latent variables via INNs. By this means, we force the color information lost in grayscale generation to be independent of the input color image. Therefore, the original color version can be efficiently recovered by randomly re-sampling a new set of Gaussian distributed variables, together with the synthetic grayscale, through the reverse mapping of INNs. To effectively learn the invertible grayscale, we introduce the wavelet transformation into a UNet-like INN architecture, and further present a quantization embedding to prevent the information omission in format conversion, which improves the generalizability of the framework in real-world scenarios. Extensive experiments on three widely used benchmarks demonstrate that the proposed method achieves a state-of-the-art performance in terms of both qualitative and quantitative results, which shows its superiority in multimedia communication and storage systems.
# Summary. An optional shortened abstract.
summary: In **IEEE Transactions on Image Processing**, 2021.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '10.1109/TIP.2021.3091902'
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
