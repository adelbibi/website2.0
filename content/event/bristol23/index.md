---
title: Offline/Online Computationally Budgeted Continual Learning


event: Bristol
event_url: 

location: Bristol, United Kingdom
# address:
#   street: 
#   city: 
#   region: 
#   postcode:
#   country: 

summary: My host was Dima Damen
abstract: Continual learning literature is focused on learning from streams under limited access to previously seen data with no restriction on the computational budget. On the contrary, in this talk, we particularly study continual learning under budgeted computation in both offline and online settings. In offline settings, we study, at scale, various previously proposed components, e.g., distillation, sampling strategies, novel loss functions, for when the computational budget is restricted per time step. Moreover, in the online setting, we consider the computational budget through delayed real-time evaluations. That is to say, continual learners that are twice as expensive to train will end up having the model parameters updated half the number of times while being evaluated on every stream sample. Our experiments suggest that the majority of current evaluations were not carried fairly to account for normalized computation. Surprisingly, simple efficient methods outperform the majority of recently proposed, but computationally involved algorithms, in both online and offline. This observation holds on several datasets and experimental settings, i.e., class incremental, data incremental, time distributed settings. This hints that evaluations that do not factor the relative computation between methods can inadequately mislead to incorrect conclusions on the performance.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-09-05'
date_end: '2023-09-05'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: "https://drive.google.com/file/d/1yVE_5Xu7P6pa7LIDdSmbzoTxRZOeiBlR/view?usp=sharing"
url_slides: ""
url_video: ""

# # Markdown Slides (optional).
# #   Associate this talk with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
# #   Otherwise, set `slides = ""`.
# slides: example

# # Projects (optional).
# #   Associate this post with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
# #   Otherwise, set `projects = []`.
# projects:
# - example
---
