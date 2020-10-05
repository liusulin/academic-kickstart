---
title: "Communication-Efficient Distributed Primal-Dual Algorithm for Saddle Point Problems"
authors:
- Yaodong Yu
- admin
- Sinno Jialin Pan
author_notes:
- "Equal contribution"
- "Equal contribution"
- ""
date: "2017-08-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Conference on Uncertainty in Artificial Intelligence (UAI)

abstract: Primal-dual algorithms, which are proposed to solve reformulated convex-concave saddle point problems, have been proven to be effective for solving a generic class of convex optimization problems, especially when the problems are ill-conditioned. However, the saddle point problem still lacks a distributed optimization framework where primal-dual algorithms can be employed. In this paper, we propose a novel communication-efficient distributed optimization framework to solve the convex-concave saddle point problem based on primal-dual methods. We carefully design local subproblems and a central problem such that our proposed distributed optimization framework is communication-efficient. We provide a convergence analysis of our proposed algorithm, and extend it to address non-smooth and non-strongly convex loss functions. We conduct extensive experiments on several real-world datasets to demonstrate competitive performance of the proposed method, especially on ill-conditioned problems.

# Summary. An optional shortened abstract.
summary:

tags:
- distributed learning
- optimization
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: http://auai.org/uai2017/proceedings/papers/286.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: https://www.automl.org/wp-content/uploads/2020/07/AutoML_2020_paper_54_poster.pdf
#url_project: ''
#url_slides: ''
#url_source: '#'
# url_video: https://www.youtube.com/watch?v=az3jbBl-zXI

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
