---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Efficient nonparametric statistical inference on population feature importance using Shapley values"
author_note:
- "Equal contribution"
- "Equal contribution"
authors:
- admin
- Jean Feng
date: 2020-06-16
doi: ""
math: true

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-13T11:34:31-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: ""

abstract: ""

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/pdf/2006.09481.pdf"
url_code: "https://github.com/bdwilliamson/vimpy"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Variable importance estimates using SPVIM (left) and SHAP (right) for the MIMIC-II data."
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["variable-importance"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

[Jean Feng](https://www.jeanfeng.com/) and I
tied together developments in the Shapley value literature in both game theory and machine learning. We propose a computationally efficient procedure that solves the issue that the classical Shapley values require estimating $2^p$ regression functions (in a problem with $p$ variables).
