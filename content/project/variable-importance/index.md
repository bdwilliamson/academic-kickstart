---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Variable Importance"
subtitle: ""
summary: ""
authors: []
tags:
- "variable-importance"
- "machine-learning"
- "biostatistics"
- "semiparametric-inference"
categories: []
date: 2020-07-13T10:58:17-07:00
lastmod: 2020-07-13T10:58:17-07:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Variable importance estimates using SPVIM (left; from Williamson and Feng [2020]) and SHAP (right) for the MIMIC-II data."
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

It is often of interest to understand the population interplay between
the outcome and measured covariates. Variable importance is a useful
tool towards this goal. Examples include: HIV vaccine studies,
correlates of risk analyses, and identifying patients at high risk of
returning to a hospital after discharge for heart failure. This is joint
work with [Marco
Carone](http://faculty.washington.edu/mcarone/about.html), [Peter
Gilbert](https://www.fredhutch.org/en/labs/profiles/gilbert-peter.html), [Noah Simon](http://faculty.washington.edu/nrsimon/), and [Jean Feng](https://www.jeanfeng.com/).
