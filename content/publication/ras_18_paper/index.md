---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Probabilistic RGB-D Odometry based on Points, Lines and Planes Under Depth Uncertainty"
authors: [Pedro F. Proença, Yang Gao]
date: 2018-03-10T14:33:10+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2018-03-10T14:33:10+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Robotics and Autonomous Systems, 104"
publication_short: ""

abstract: "This paper presents CAPE, a method to extract planes and cylinder segments from organized point clouds, which processes 640 × 480 depth images on a single CPU core at an average of 300 Hz, by operating on a grid of planar cells. While, compared to state-of-the-art plane extraction, the latency of CAPE is more consistent and 4-10 times faster, depending on the scene, we also demonstrate empirically that applying CAPE to visual odometry can improve trajectory estimation on scenes made of cylindrical surfaces (e.g. tunnels), whereas using a plane extraction approach that is not curve-aware deteriorates performance on these scenes. To use these geometric primitives in visual odometry, we propose extending a probabilistic RGB-D odometry framework based on points, lines and planes to cylinder primitives. Following this framework, CAPE runs on fused depth maps and the parameters of cylinders are modelled probabilistically to account for uncertainty and weight accordingly the pose optimization residuals."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.sciencedirect.com/science/article/pii/S0921889017303378
url_preprint: https://arxiv.org/abs/1706.04034
url_code: https://github.com/pedropro/OMG_Depth_Fusion
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://youtu.be/Y0T2_ghlng0

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
