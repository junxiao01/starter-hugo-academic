---
title: 'Improving Robustness of Single Image Super-Resolution Models with Monte Carlo Method'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Cuixin Yang
  - admin
  - Cong Zhang
  - Kin-Man Lam

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'


date: '2023-09-22T00:00:00Z'
doi: 'https://doi.org/10.1109/ICIP49359.2023.10222757'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Image Processing (ICIP), 2023*
publication_short: In ICIP

abstract: Deep learning-based methods have achieved promising results in single image super-resolution (SISR). However, the performance of existing deep SISR methods is very sensitive to image degradation. In addition, these methods are deterministic and do not introduce any uncertainty to the generated images, so we have no way of knowing the reliability of these generated images. To address these two challenging issues, we propose a model-agnostic approach for existing deep SISR networks to improve their robustness under various degradations. Our proposed method follows a probabilistic framework and applies Monte Carlo dropout to existing deep SISR methods. Instead of performing point estimation, the proposed method predicts the posterior distribution of super-resolved images. Based on this, we can determine the uncertainty of the generated images. Experiment results show that the proposed method can effectively improve the robustness of existing deep SISR methods, leading to state-of-the-art performance when applied to images having different degradations. The code is available at https://github.com/YangTracy/MCD-SR.
# Summary. An optional shortened abstract.
summary: In **IEEE International Conference on Image Processing (ICIP)**, 2023.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '10.1109/ICIP.2019.8803251'
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
