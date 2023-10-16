---
title: "New Problems in Active Sampling for Mobile Robotic Online Learning"
authors:
- Xiuxian Guan
- admin
- Zekai Sun
- Zongyuan Zhang
- Tianyang Duan
- Shengliang Deng
- Fangming Liu
- Heming Cui*
date: "2023-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the 6th IEEE International Workshop on Advances in Artificial Intelligence & Machine Learning*
publication_short: In *AIML 2023*

abstract: "AI models deployed in real-world tasks (e.g., surveillance, implicit mapping, health care) typically need to be online trained for better modelling of the changing real-world environments and various online training methods (e.g., domain adaptation, few shot learning) are proposed for refining the AI models based on sampled training input from the real world. However, in the whole loop of AI model online training, there is a section rarely discussed: sampling of training input from the real world. In this paper, we show from the perspective of online training of AI models deployed on edge devices (e.g., robots) that several problems in sampling of training input are hindering the effectiveness (e.g., final training accuracy) and efficiency (e.g., online training accuracy gain per epoch) for the online training process. Notably, the online training relies on training input consecutively sampled from the real world and suffers from locality problem: the consecutive samples from nearby states (e.g., position and orientation of a camera) are too similar and would limit the training efficiency; on the other hand, while we can choose to sample more about the inaccurate samples to better final training accuracy, it is costly to obtain the accuracy statistics of samples via traditional ways such as validating, especially for AI models deployed on edge devices. These findings aim to raise research effort for practical online training of AI models, so that they can achieve resiliently and sustainably high performance in real-world tasks."

# Summary. An optional shortened abstract.
summary: Xiuxian Guan, <b style="color:#E08040">Junming Wang</b>, Zekai Sun,  Zongyuan Zhang, Tianyang Duan, Shengliang Deng, Fangming Liu, Heming Cui* </br> 
         <b style="color:#3F51B5"> IEEE 47th Annual Computers, Software, and Applications Conference (COMPSAC), 2023</b> 



tags:
  - 2023
#- Source Themes
featured: false

links:
#- name: arXiv
#  url: https://arxiv.org/abs/1609.06118

url_pdf: 'https://drive.google.com/file/d/1mP-m3uqdPuS1IRq7-dZ1MwYn-BqQtg7d/view?usp=sharing'
#url_code: 'files/ColorTracking_code.zip'
#url_dataset: '#'
#url_poster: 'http://www.cvl.isy.liu.se/research/objrec/visualtracking/colvistrack/CN_Tracking_CVPR14_poster.pdf'
#url_project: 'http://www.cvl.isy.liu.se/research/objrec/visualtracking/colvistrack/index.html'
#url_slides: ''
#url_source: '#'
#url_video: 'https://youtu.be/GKAsIh0o1mM?t=106'

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


