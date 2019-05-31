---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SPLODE: Semi-Probabilistic Point and Line Odometry with Depth Estimation from RGB-D Camera Motion"
authors: [Pedro F. Proença, Yang Gao]
date: 2017-12-14T14:33:10+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-05-31T14:33:10+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)"
publication_short: "IROS"

abstract: "Active depth cameras suffer from several limitations, which cause incomplete and noisy depth maps, and may consequently affect the performance of RGB-D Odometry. To address this issue, this paper presents a visual odometry method based on point and line features that leverages both measurements from a depth sensor and depth estimates from camera motion. Depth estimates are generated continuously by a probabilistic depth estimation framework for both types of features to compensate for the lack of depth measurements and inaccurate feature depth associations. The framework models explicitly the uncertainty of triangulating depth from both point and line observations to validate and obtain precise estimates. Furthermore, depth measurements are exploited by propagating them through a depth map registration module and using a frame-to-frame motion estimation method that considers 3D-to-2D and 2D-to-3D reprojection errors, independently. Results on RGB-D sequences captured on large indoor and outdoor scenes, where depth sensor limitations are critical, show that the combination of depth measurements and estimates through our approach is able to overcome the absence and inaccuracy of depth measurements."

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

url_pdf: http://epubs.surrey.ac.uk/846020/1/SPLODE.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://youtu.be/6lMwPCiCXZc

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

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
