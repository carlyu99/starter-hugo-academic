---
title: "Exploiting Linear Models for Model-Free Nonlinear Control: A Provably Convergent Policy Gradient Approach"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Guannan Qu
- admin
- Steven Low
- Adam Wierman

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-12-14"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 2021 60th IEEE Conference on Decision and Control (CDC)
publication_short: CDC 2021

abstract: Model-free learning-based control methods have seen great success recently. However, such methods typically suffer from poor sample complexity and limited convergence guarantees. This is in sharp contrast to classical model-based control, which has a rich theory but typically requires strong modeling assumptions. In this paper, we combine the two approaches. We consider a dynamical system with both linear and non-linear components and use the linear model to define a warm start for a model-free, policy gradient method. We show this hybrid approach outperforms the model-based controller while avoiding the convergence issues associated with model-free approaches via both numerical experiments and theoretical analyses, in which we derive sufficient conditions on the non-linear component such that our approach is guaranteed to converge to the (nearly) global optimal controller.

# Summary. An optional shortened abstract.
summary:

tags: [Learning, Control Theory]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2006.07476'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
