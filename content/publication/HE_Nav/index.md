
---
title: "HE-Nav: A High-Performance and Efficient Navigation System for Aerial-Ground Robots in Cluttered Environments"

<div style="background-color: #E08040; color: white; padding: 10px; border-radius: 5px; text-align: center; margin-bottom: 20px;">
  <strong>RA-L 2024</strong>
</div>

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zekai Sun
  - Xiuxian Guan
  - Tianxiang Shen
  - Dong Huang
  - Zongyuan Zhang
  - Tianyang Duan
  - Fangming Liu
  - Heming Cui


# Author notes (optional)
author_notes:
  - 
  - 
  - 
  - 
  - 
  - 
  - 
  - 
  - 'Corresponding author'


date: "2024-04-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Robotics and Automation Letters (RA-L)*
publication_short: In *RA-L 2024*

abstract: "Aerial-ground robots (AGRs) have unique dual-mode capabilities (i.e., flying and driving), making them ideal for search and rescue tasks. Existing AGR navigation systems have advanced in structured indoor scenarios using Euclidean Signed Distance Field (ESDF) maps for collision-free pathfinding. However, these systems are exhibit suboptimal performance and efficient in occluded environments (e.g., forests) due to perception module and path planner limitations. In this paper, we present HE-Nav, the first high-performance and efficient navigation system tailored for AGRs. The perception module utilizes a lightweight semantic scene completion network (LBSCNet), guided by a bird's eye view (BEV) feature fusion and enhanced by an exquisitely designed SCB-Fusion module and attention mechanism. This enables real-time and efficient obstacle prediction in occluded areas, generating a complete local map. Building upon this completed map, our novel AG-Planner employs the energy-efficient kinodynamic A* search algorithm to guarantee planning is energy-saving. Subsequent trajectory optimization and post-refinement processes yield safe, smooth, dynamically feasible and ESDF-free aerial-ground hybrid paths. Extensive experiments demonstrate that HE-Nav achieved 7x energy savings in real-world situations while maintaining planning success rates of 98% in simulation scenarios."

# Summary. An optional shortened abstract.
summary: <b style="color:#E08040">Junming Wang,</b> Zekai Sun, Xiuxian Guan, Tianxiang Shen, Dong Huang, Zongyuan Zhang, Tianyang Duan, Fangming Liu, Heming Cui*  </br> 
         
         <b style="color:#3F51B5">IEEE Robotics and Automation Letters (RA-L), 2024</b> 
         <b style="color:red">  | IF = 4.6 </b>



tags:
  - 2024
#- Source Themes
featured: false

links:
#- name: arXiv
#  url: https://arxiv.org/abs/1609.06118
url_project: 'https://jmwang0117.github.io/HE-Nav/'
url_pdf: 'https://jmwang0117.github.io/HE_Nav.pdf'
url_code: 'https://github.com/jmwang0117/HE-Nav'
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


