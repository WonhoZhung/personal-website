---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Heavy-tail behaviour of SGD? - Part 2"
event: OSI Lab Seminar
event_url:
location: Zoom
address:
  street:
  city:
  region:
  postcode:
  country:
summary: This talk introduces a rather new approach to analyzing SGD, from the perspective of heavy-tail behaviors.
abstract: Part 1 was about introducing reasons of why heavy-tailed model should be used to describe the SGD dynamics. This talk(Part 2) gives a from-ground talk on necessary mathematical background, and as the title suggests, how Hausdorff dimension is directly related to the generalization capability, when the behavior of SGD is described using Feller process. On the way, various papers (ICML2019, ICML2020, NIPS2020, arXiv) will be briefly mentioned.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-11-06T14:30:00+09:00
date_end: 2020-11-06T16:30:00+09:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-10-27T01:47:47+09:00

authors: []
tags: ["SGD", "SDE", "heavy-tail", "Feller process", "Hausdorff dimension"]

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
url_slides:

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
projects: ["sgd-behavior"]
---

Papers discussed in the talk:
- **Main:** Şimşekli, U., Sener, O., Deligiannidis, G., Erdogdu, M. A. Hausdorff Dimension, Stochastic Differential Equations, and Generalization in Neural Networks. In *NIPS*, 2020. (*Spotlight paper!*)
- Şimşekli, U., Gürbüzbalaban, M., Nguyen, T. H., Richard, G., Sagun, L. On the Heavy-Tailed Theory of Stochastic Gradient Descent for Deep Neural Networks. In *arXiv*, 2019.
- Gürbüzbalaban, M., Şimşekli, U., Zhu, L. The Heavy-Tail Phenomenon in SGD. In *arXiv*, 2020.