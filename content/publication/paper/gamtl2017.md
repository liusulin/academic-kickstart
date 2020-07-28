---
title: "Adaptive Group Sparse Multi-task Learning via Trace Lasso"
authors:
- admin
- Sinno Jialin Pan
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
publication: International Joint Conference on Artificial Intelligence (IJCAI)

abstract: In multi-task learning (MTL), tasks are learned jointly so that information among related tasks is shared and utilized to help improve generalization for each individual task. A major challenge in MTL is how to selectively choose what to share among tasks. Ideally, only related tasks should share information with each other. In this paper, we propose a new MTL method that can adaptively group correlated tasks into clusters and share information among the correlated tasks only. Our method is based on the assumption that each task parameter is a linear combination of other tasks’ and the coefficients of the linear combination are active only if there is relatedness between the two tasks. Through introducing trace Lasso penalty on these coefficients, our method is able to adaptively select the subset of coefficients with respect to the tasks that are correlated to the task. Our model frees the process of determining task clustering structure as used in the literature. Efficient optimization method based on alternating direction method of multipliers (ADMM) is developed to solve the problem. Experimental results on both synthetic and real-world datasets demonstrate the effectiveness of our method in terms of clustering related tasks and generalization performance.

# Summary. An optional shortened abstract.
summary:

tags:
- multi-task learning
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://www.ijcai.org/Proceedings/2017/328
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
