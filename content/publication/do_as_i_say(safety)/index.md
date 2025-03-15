---
title: "Do as I do (Safely): Mitigating Task-Specific Fine-tuning Risks in Large Language Models"


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Francisco Eiras
- Aleksandar Petrov
- Philip H.S. Torr
- M. Pawan Kumar
- admin

# Author notes (optional)
author_notes:
- ""
- ""
- ""

date: "2025-04-22"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Learning Representations
publication_short: International Conference on Learning Representations (**ICLR25**)

abstract: Recent research shows that fine-tuning on benign instruction-following data can inadvertently undo the safety alignment process and increase a model's propensity to comply with harmful queries. While instruction-following fine-tuning is important, task-specific fine-tuning - where models are trained on datasets with clear ground truth answers (e.g., multiple choice questions) - can enhance model performance on specialized downstream tasks. Understanding and mitigating safety risks in the task-specific setting remains distinct from the instruction-following context due to structural differences in the data. Our work demonstrates how malicious actors can subtly manipulate the structure of almost any task-specific dataset to foster significantly more dangerous model behaviors, while maintaining an appearance of innocuity and reasonable downstream task performance. To address this issue, we propose a novel mitigation strategy that mixes in safety data which mimics the task format and prompting style of the user data, showing this is significantly more effective and efficient than existing baselines at re-establishing safety alignment while maintaining similar task performance.


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2406.10288'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# # image:
# #   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
# #   focal_point: ""
# #   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
# - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

