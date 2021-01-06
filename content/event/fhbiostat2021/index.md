---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Statistical inference and containerization in computational pipelines"
event: "Fred Hutchinson Cancer Research Center Biostatistics Program Seminar Series"
event_url: https://www.fredhutch.org/en/research/divisions/public-health-sciences-division/research/biostatistics/seminars-events.html
location: "Virtual"
address:
  street:
  city:
  region:
  postcode:
  country:
summary: Seminar Series of the Biostatistics Program at the Fred Hutchinson Cancer Research Center
abstract: "Machine learning, while a valuable tool in many contexts, is often used without reliable checks to ensure that the resulting predictions are useful and reproducible. In this talk, I will discuss three approaches towards a more principled use of machine learning: inference on the goodness of fit, inference on variable importance, and containerization. Inference on meaningful target parameters in the context of machine learning can be a helpful part of the data analysis pipeline, ensuring that the predictions made are achieving some level of good performance. The use of containers allows for explicit standardization of an entire computing environment, from the operating system down to specific software packages. As case study, we will consider the task of selecting broadly neutralizing antibody (bnAb) regimens for future efficacy trials using machine learning, and a computational platform for doing so that incorporates the above methods. This is joint work with Craig Magaret, Sohail Nizam, Peter Gilbert, and David Benkeser."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-01-06T12:00:00
date_end: 2021-01-06T13:00:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2021-01-05T14:00:00-00:00

authors: []
tags: ["variable-importance", "machine-learning", "infectious-diseases"]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: "https://bdwilliamson.github.io/slapnaptalk/"
url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["bnabs"]
---
