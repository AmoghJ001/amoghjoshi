---
title: "GDenseMNet: Global Dense Multiscale Feature Learning Network for Efficient COVID-19 Detection in CT Images"
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Deepak Ranjan Nayak

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "July 2022"
#doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-17"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IJCNN
publication_short: The 2022 International Joint Conference on Neural Networks (CORE RANK A)

abstract: Accurate and rapid diagnosis of COVID-19 is crucial for curbing its fast spread across the globe, with constant mutations leading to newer variants. Recent studies have exhibited that chest CT scans manifest clear radiological findings for the COVID-19 infected patients. Convolutional neural networks (CNN) have been used considerably for COVID-19 diagnosis; however, most CNN architectures demand a huge amount of parameters, resulting in overfitting on limited training data and a slower inference. Further, residual and densely connected neural networks such as ResNet and DenseNet have been proven to strengthen feature extraction and feature propagation but fail to fully discover both local and global representations. Moreover, few linearly stacked networks fall short in capturing and preserving multi-scaled features from various receptive fields. This paper proposes a new CNN architecture called global dense multi-scale feature learning network (GDenseMNet) for COVID-19 detection from CT images that effectively incorporates global dense connections while capturing multi-scaled features. The GDenseMNet model comprises multi-scale local feature extraction (MLF) blocks that capture local features of various size receptive fields using multiple filters and residual skip connections. The global dense connections between these blocks further enable global feature learning capability. The proposed architecture is lightweight, end-to-end learnable, and validated using the SARS-CoV-2 CT-Scan dataset. Experimental results demonstrate that the GDenseMNet model achieves promising detection performance compared to state-of-the-art CNN approaches.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/ijcnn/Amogh_IJCNN_paper.pdf'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
---
