---
title: Efficient Lifelong Model Evaluation in an Era of Rapid Progress


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ameya Prabhu
- Vishaal Udandarao
- Philip H.S. Torr
- Matthias Bethge
- admin
- Samuel Albanie

author_notes:
- "Equal Contribution"
- "Equal Contribution"
- ""
- ""
- "Equal Advising"
- "Equal Advising"

date: "2024-12-30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Neural Information Processing Systems
publication_short: Neural Information Processing Systems (**NeurIPS24**)

abstract: Standardized benchmarks drive progress in machine learning. However, with repeated testing, the risk of overfitting grows as algorithms over-exploit benchmark idiosyncrasies. In our work, we seek to mitigate this challenge by compiling ever-expanding large-scale benchmarks called Lifelong Benchmarks. These benchmarks introduce a major challenge; the high cost of evaluating a growing number of models across very large sample sets. To address this challenge, we introduce an efficient framework for model evaluation, Sort & Search (S&S)}, which reuses previously evaluated models by leveraging dynamic programming algorithms to selectively rank and sub-select test samples. To test our approach at scale, we create Lifelong-CIFAR10 and Lifelong-ImageNet, containing 1.69M and 1.98M test samples for classification. Extensive empirical evaluations across over 31,000 models demonstrate that S&S achieves highly-efficient approximate accuracy measurement, reducing compute cost from 180 GPU days to 5 GPU hours (about 1000x reduction) on a single A100 GPU, with low approximation error and memory cost of <100MB. Our work also highlights issues with current accuracy prediction metrics, suggesting a need to move towards sample-level evaluation metrics. We hope to guide future research by showing our method's bottleneck lies primarily in generalizing Sort beyond a single rank order and not in improving Search.




# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2402.19472'
url_code: 'https://github.com/bethgelab/sort-and-search'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary material can be found [here](https://drive.google.com/file/d/17tGxceooVTT0JFkBsQjsh3h529U7yI1v/view?usp=sharing). -->
