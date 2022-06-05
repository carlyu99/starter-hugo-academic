---
title: "The Power of Predictions in Online Control"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Guanya Shi
- Soon-Jo Chung
- Yisong Yue
- Adam Wierman

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-12-06"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Thirty-fourth Conference on Neural Information Processing Systems (NeurIPS 2020)
publication_short: NeurIPS 2020

abstract: We study the impact of predictions in online Linear Quadratic Regulator control with both stochastic and adversarial disturbances in the dynamics. In both settings, we characterize the optimal policy and derive tight bounds on the minimum cost and dynamic regret. Perhaps surprisingly, our analysis shows that the conventional greedy MPC approach is a near-optimal policy in both stochastic and adversarial settings. Specifically, for length-$T$ problems, MPC requires only $O(\\log T)$ predictions to reach $O(1)$ dynamic regret, which matches (up to lower-order terms) our lower bound on the required prediction horizon for constant regret.

# Summary. An optional shortened abstract.
summary:

tags: [Control Theory, Online Algorithm]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: blog post
  url: https://www.gshi.me/blog/CompetitiveMPC/

url_pdf: 'https://arxiv.org/abs/2006.07569'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://videos.neurips.cc/search/power%20of%20predictions%20in%20online%20control/video/slideslive-38936069'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: # example
---
