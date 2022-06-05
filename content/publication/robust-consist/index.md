---
title: "Robustness and Consistency in Linear Quadratic Control with Predictions"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tongxin Li
- Ruixiao Yang
- Guannan Qu
- Guanya Shi
- admin
- Adam Wierman
- Steven Low

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-02-25"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the ACM on Measurement and Analysis of Computing Systems (SIGMETRICS 2022)
publication_short: SIGMETRICS 2022

abstract: We study the problem of learning-augmented predictive linear quadratic control. Our goal is to design a controller that balances consistency, which measures the competitive ratio when predictions are accurate, and robustness, which bounds the competitive ratio when predictions are inaccurate. We propose a novel $\lambda$-confident controller and prove that it maintains a competitive ratio upper bound of $1 + \min\{O(\lambda^2 \epsilon) + O(1 - \lambda)^2, O(1) + O(\lambda^2)\}$ where $\lambda \in [0, 1]$ is a trust parameter set based on the confidence in the predictions, and $\epsilon$ is the prediction error. Further, we design a self-tuning policy that adaptively learns the trust parameter $\lambda$ with a regret that depends on $\epsilon$ and the variation of perturbations and predictions.

# Summary. An optional shortened abstract.
summary:

tags: [Control Theory, Online Algorithm]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2106.09659'
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
projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: # example
---
