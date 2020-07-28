---
title: "Data poisoning attacks on multi-task relationship learning"
authors:
- Mengchen Zhao
- Bo An
- Yaodong Yu
- admin
- Sinno Jialin Pan
date: "2018-04-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: AAAI Conference on Artificial Intelligence (AAAI)

abstract: Multi-task learning (MTL) is a machine learning paradigm that improves the performance of each task by exploiting useful information contained in multiple related tasks. However, the relatedness of tasks can be exploited by attackers to launch data poisoning attacks, which has been demonstrated a big threat to single-task learning. In this paper, we provide the first study on the vulnerability of MTL. Specifically, we focus on multi-task relationship learning (MTRL) models, a popular subclass of MTL models where task relationships are quantized and are learned directly from training data. We formulate the problem of computing optimal poisoning attacks on MTRL as a bilevel program that is adaptive to arbitrary choice of target tasks and attacking tasks. We propose an efficient algorithm called PATOM for computing optimal attack strategies. PATOM leverages the optimality conditions of the subproblem of MTRL to compute the implicit gradients of the upper level objective function. Experimental results on real-world datasets show that MTRL models are very sensitive to poisoning attacks and the attacker can significantly degrade the performance of target tasks, by either directly poisoning the target tasks or indirectly poisoning the related tasks exploiting the task relatedness. We also found that the tasks being attacked are always strongly correlated, which provides a clue for defending against such attacks.

# Summary. An optional shortened abstract.
summary:

tags:
- multi-task learning
- data poisoning attack
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/16073
#url_code: '#'
#url_dataset: '#'
#url_poster: https://www.automl.org/wp-content/uploads/2020/07/AutoML_2020_paper_54_poster.pdf
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: https://www.youtube.com/watch?v=az3jbBl-zXI

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
