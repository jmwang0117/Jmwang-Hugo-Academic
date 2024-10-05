
---
title: "HE-Drive: Human-Like End-to-End Driving with Vision Language Models"


date: "2024-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: "3D semantic occupancy prediction networks have demonstrated remarkable capabilities in reconstructing the geometric and semantic structure of 3D scenes, providing crucial information for robot navigation and autonomous driving systems. However, due to their large overhead from dense network structure designs, existing networks face challenges balancing accuracy and latency. In this paper, we introduce OccRWKV, an efficient semantic occupancy network inspired by Receptance Weighted Key Value (RWKV).

OccRWKV separates semantics, occupancy prediction, and feature fusion into distinct branches, each incorporating Sem-RWKV and Geo-RWKV blocks. These blocks are designed to capture long-range dependencies, enabling the network to learn domain-specific representation (i.e., semantics and geometry), which enhances prediction accuracy. Leveraging the sparse nature of real-world 3D occupancy, we reduce computational overhead by projecting features into the bird's-eye view (BEV) space and propose a BEV-RWKV block for efficient feature enhancement and fusion. This enables real-time inference at 22.2 FPS without compromising performance.

Experiments demonstrate that OccRWKV outperforms the state-of-the-art methods on the SemanticKITTI dataset, achieving a mIoU of 25.1 while being 20 times faster than the best baseline, Co-Occ, making it suitable for real-time deployment on robots to enhance autonomous navigation efficiency. To support the community and ensure reproducibility, we will release the code for reference."

# Summary. An optional shortened abstract.
summary: <b style="color:#E08040">Junming Wang,</b> Xingyu Zhang, Zebin Xing, Songen Gu, Xiaoyang Guo, Yang Hu, Ziying Song, Qian Zhang, Xiaoxiao Long, Wei Yin* </br> 
         
         <b style="color:#3F51B5"> Under Review</b> 



tags:
  - 2024
#- Source Themes
featured: false

links:

#url_project: 'https://jmwang0117.github.io/OccRWKV/'
#url_pdf: 'https://arxiv.org/abs/2403.11607'
#url_code: 'https://github.com/jmwang0117/OccRWKV'
#url_video: 'https://www.youtube.com/watch?v=8-8XW6ufnZo'

#url_dataset: '#'
#url_poster: 'http://www.cvl.isy.liu.se/research/objrec/visualtracking/colvistrack/CN_Tracking_CVPR14_poster.pdf'

#url_slides: ''
#url_source: '#'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---


