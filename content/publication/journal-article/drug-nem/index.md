---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DRUG-NEM: Optimizing drug combinations using single-cell perturbation response to account for intratumoral heterogeneity"
authors:
- Benedict Anchang
- Kara Davis
- Harris Feinberg
- admin
- et al.
date: 2018-06-13
doi: "10.1073/pnas.1711365115"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-13T13:39:01-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the National Academy of Sciences"
publication_short: ""

abstract: ""

# Summary. An optional shortened abstract.
summary: "We propose a method for using single-cell mass cytometry data to learn the optimal combination of cancer treatment options to assign to a given patient."

tags: ["clinical-trials", "collaborative-science"]
categories: ["collaborative-science"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
 - name: Journal
   url: https://www.pnas.org/content/115/18/E4294
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://www.pnas.org/content/pnas/115/18/E4294.full.pdf"
url_code:
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
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["collaborative-science"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

In this work, our goal was to develop an algorithm for optimally
assigning patients to cancer treatment strategies. We leveraged data
from single-cell mass cytometry to: automatically determine
subpopulations of cells; create a nested effects model to infer gene
hierarchy based on perturbation effects due to administered drugs; and
create a scoring and ranking algorithm that identifies the minimal
number of drugs among a combination of drugs with the maximal desired
intracellular effects. This is joint work with [Sylvia
Plevritis](http://med.stanford.edu/plevritis.html), [Benedict
Anchang](http://med.stanford.edu/plevritis.html/People), and others.
