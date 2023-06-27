---
title: 🤖DAROS - Enabling Embodied Edge Computing for Embodied Intelligence
summary: <b style="color:#008080">The University of Hong Kong Project</b></br> 
 <b style="color:#E08040">ROG Team,</b> Supervisor - *Prof.Heming Cui*  </br>
 

tags:
- Robotics
date: "2022-09-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""
url_slides: ''



---
Embodied intelligence, a key enabler for real-world robotic applications, demands significant computational resources such as CPU, GPU, and memory. Although cloud computing has been considered to address these needs, it faces challenges in mission-critical scenarios and privacy regulations. Consequently, embodied edge computing (EEC) on a group of real-world robots has become essential for embodied intelligence. However, ensuring fast and reliable communication in EEC is challenging due to varying connection quality and environmental obstacles.

To tackle these issues, DAROS, a distributed scheduler, is developed to estimate wireless connection quality ex-ante and schedule applications' processes in advance. This approach offers two main advantages: fast and reliable migration of processes before connections degrade, and reduced unnecessary interruptions to applications by being aware of the root cause of connection quality changes.

DAROS's design is based on real-world robot motion patterns and consists of a real-time signal strength estimation pipeline (RTSP) to estimate connection quality. It also extends its decision space to include application configuration, aiming to optimize the computation power exploited per second.

Implemented as a Kubernetes controller, DAROS is open-source and easily deployable for various applications. Evaluations with prevalent embodied intelligence applications on a group of four-wheel robots show promising results in terms of low tail latency, high throughput, and scalability.
