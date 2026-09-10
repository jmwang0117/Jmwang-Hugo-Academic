
---
title: "WALL-WM: Carving World Action Modeling at the Event Joints"

date: "2026-05-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-05-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Technical Report"
publication_short: "Tech Report"

abstract: "WALL-WM is a World Action Model that shifts video-action learning from chunk-centric optimization to event-grounded Vision-Language-Action pretraining, using semantically coherent action events as the atomic unit of learning. Existing WAMs commonly initialize from multimodal or video foundation models and then optimize fixed-length action chunks conditioned directly on the current observation and instruction. Although convenient, this chunk-centric formulation creates a fundamental granularity mismatch. Language describes semantic goals and events, vision evolves through continuous scene dynamics, and actions operate at control-level timescales; forcing all three into the same fixed-length prediction window turns VLA training into short-horizon correlation fitting. This not only underuses the pretrained visual-semantic prior, but can actively overwrite it with chunk-specific action shortcuts, weakening compositionality and long-horizon generalization. WALL-WM addresses this mismatch by organizing both supervision and data around semantic events. Specifically, it pairs event-grounded VLA pretraining with a data ecosystem built from event-level captions and cluster-balanced sampling, enabling scalable learning over diverse behaviors, scenes, and task structures. From the same event-pretrained backbone, WALL-WM supports two complementary inference modes. The event mode consumes next-event descriptions and enables variable-length execution chunks, while the unified mode uses a VLM with Staircase Decoding to condition conventional fixed-length chunk inference while preserving a gradient-continuous VLA path. Together with Muon-optimizer-based large-scale pretraining infrastructure, WALL-WM provides a practical scale-up recipe for general-purpose WAMs. Experiments show that WALL-WM generalizes broadly across language, scenes, and tasks, achieving state-of-the-art performance in large-scale real-world generalization evaluation."

# Summary. An optional shortened abstract.
summary: >-
  Shalfun Li*†, Victor Yao*, Charles Yang*, Truth Qu*, Regis Cheng*, Ryan Yu*, Howard Lu*, Vincent Chen*, Newton Von*, Yohann Tang, Maeve Zhang, Ellie Ma, Gody Li, Sage Yang, Lorien Shu, J.W. Gao, Ethan Chen, Colin Ye, Rain Sun, Elise Mon, PS Zhang, Neo Li, Lily Li, <b style="color:#E08040">James Wang</b>, Ping Yang, Chris Pan, Lucy Liang, Hang Su, Roy Gan, Hao Wang‡, Qian Wang </br>
  <b style="color:#3F51B5">Technical Report</b> </br>
  <b style="color:#3F51B5">ECCV 2026 Workshop - </b><b style="color:red">Best Paper Award</b>



tags:
  - 2026
#- Source Themes
featured: true

links:

url_project: 'https://x2robot.com/pages/wm'
url_pdf: 'https://x2robot.com/pages/wm'
url_code: 'https://github.com/X-Square-Robot/wall-x'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ""
  preview_only: false

projects: []
slides:
---
