
---
title: "OMEGA: Efficient Occlusion-Aware Navigation for Air-Ground Robot in Dynamic Environments via State Space Model"


date: "2024-08-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation*
publication_short: In *ICRA 2024*

abstract: "Air-ground robots (AGRs) are widely used in surveillance and disaster response due to their exceptional mobility and versatility (i.e., flying and driving). Current AGR navigation systems perform well in static occlusion-prone environments (e.g., indoors) by using 3D semantic occupancy networks to predict occlusions for complete local mapping and then computing Euclidean Signed Distance Field (ESDF) for path planning. However, these systems face challenges in dynamic, severe occlusion scenes (e.g., crowds) due to limitations in perception networks' low prediction accuracy and path planners' high computation overhead. In this paper, we propose OMEGA, which contains OccMamba with an Efficient AGR-Planner to address the above-mentioned problems. OccMamba adopts a novel architecture that separates semantic and occupancy prediction into independent branches, incorporating two mamba blocks within these branches. These blocks efficiently extract semantic and geometric features in 3D environments with linear complexity, ensuring that the network can learn long-distance dependencies to improve prediction accuracy. Semantic and geometric features are combined within the Bird's Eye View (BEV) space to minimise computational overhead during feature fusion. The resulting semantic occupancy map is then seamlessly integrated into the local map, providing occlusion awareness of the dynamic environment. Our AGR-Planner utilizes this local map and employs kinodynamic A* search and gradient-based trajectory optimization to guarantee planning is ESDF-free and energy-efficient. Extensive experiments demonstrate that OccMamba outperforms the state-of-the-art 3D semantic occupancy network with 25.0% mIoU. End-to-end navigation experiments in dynamic scenes verify OMEGA's efficiency, achieving a 96% average planning success rate."

# Summary. An optional shortened abstract.
summary: <b style="color:#E08040">Junming Wang,</b> Dong Huang*, Xiuxian Guan, Zekai Sun, Tianxiang Shen, Fangming Liu, Heming Cui </br> 
         
         <b style="color:#3F51B5"> Under Review</b> 




#- Source Themes
featured: false

links:
#- name: arXiv
#  url: https://arxiv.org/abs/1609.06118
url_project: 'https://jmwang0117.github.io/OMEGA/'
#url_pdf: 'https://arxiv.org/abs/2403.11607'
url_code: 'https://github.com/jmwang0117/Occ-Mamba'
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


