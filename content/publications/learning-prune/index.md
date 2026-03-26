---
title: 'Learning to Prune Branches in Modern Tree-Fruit Orchards'

authors:
  - me
  - 'Cindy Grimm'
  - 'Stefan Lee'

date: '2025-01-01T00:00:00Z'

publication_types: ['paper-conference']

publication: '2025 IEEE International Conference on Robotics and Automation (ICRA)'

abstract: 'Learning to Prune Branches in Modern Tree-Fruit Orchards'

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: '10.1109/ICRA55743.2025.11128361'

# Replace your current links block with this:
links:
  - type: pdf
    url: 'https://ieeexplore.ieee.org/document/11128361'
  - type: preprint
    name: arXiv
    url: 'https://arxiv.org/abs/2507.23015'
  - type: video
    url: 'https://www.youtube.com/watch?v=78LGGPcMVyQ'

# Featured image
# Ensure your graphical abstract is named `featured.jpg` or `featured.png` in this folder
image:
  caption: 'Graphical Abstract: Our pipeline for pruning branch detection in modern orchards.'
  focal_point: 'Center'
  preview_only: false

---
## Watch the Demo
See our robotic pruning system in action:

{{< youtube 78LGGPcMVyQ >}}

## Abstract Details
Dormant tree pruning is labor intensive but essential to maintaining modern highly-productive fruit orchards. In this work we present a closed-loop visuomotor controller for robotic pruning. The controller guides the cutter through a cluttered tree environment to reach a specified cut point and ensures the cutters are perpendicular to the branch. We train the controller using a novel orchard simulation that captures the geometric distribution of branches in a target apple orchard configuration. Unlike traditional methods requiring full 3D reconstruction, our controller uses just optical flow images from a wrist-mounted camera. We deploy our learned policy in simulation and the real-world for an example V-Trellis envy tree with zero-shot transfer, achieving a ~30% success rate - approximately half the performance of an oracle planner.
