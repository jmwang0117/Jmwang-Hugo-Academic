
---
title: "ComDrive: Comfort-Oriented End-to-End Autonomous Driving"


date: "2025-06-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: "In this paper, we propose HE-Drive: the first human-like-centric end-to-end autonomous driving system to generate trajectories that are both temporally consistent and comfortable. Recent studies have shown that imitation learning-based planners and learning-based trajectory scorers can effectively generate and select accuracy trajectories that closely mimic expert demonstrations. However, such trajectory planners and scorers face the dilemma of generating temporally inconsistent and uncomfortable trajectories.

To solve the above problems, Our HE-Drive first extracts key 3D spatial representations through sparse perception, which then serves as conditional inputs for the Conditional Denoising Diffusion Probabilistic Model (DDPM)-based motion planner to generate temporal consistency multi-modal trajectories. A Vision-Language Model (VLM)-guided trajectory scorer subsequently selects the most comfortable trajectory from these candidates to control the vehicle, ensuring human-like end-to-end driving. 

Experiments show that HE-Drive not only achieves state-of-the-art performance (i.e., reduces the average collision rate by 71% than VAD) and efficiency (i.e., 1.9x faster than SparseDrive) on the challenging nuScenes and OpenScene datasets but also provides the most comfortable driving experience on real-world data."

# Summary. An optional shortened abstract.
summary: <b style="color:#E08040">Junming Wang*,</b> Xingyu Zhang*, Zebin Xing, Songen Gu, Xiaoyang Guo, Yang Hu, Ziying Song, Qian Zhang, Xiaoxiao Long, Wei Yin* </br> 
<b style="color:#3F51B5">  IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2025</b> 
<b style="color:red">  | Oral Presentation </b>



tags:
  - 2025
#- Source Themes
featured: false

links:

url_project: 'https://jmwang0117.github.io/HE-Drive/'
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


