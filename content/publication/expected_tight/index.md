---
title: "Expected Tight Bounds for Robust Deep Neural Network Training"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Salman Alsubaihi
- admin
- Modar Alfadly
- Abdullah Hamdi
- Bernard Ghanem

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- ""
- ""

date: "2021-03-28"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Robust Machine Learning Workshop at the International Conference on Learning Representations (ICLRW)
publication_short: In *RobustML @ICLR21*

abstract: Training Deep Neural Networks that are robust to norm bounded adversarial attacks remains an elusive problem. While exact and inexact verification-based methods are generally too expensive to train large networks, it was demonstrated that bounded input intervals can be inexpensively propagated from a layer to another through deep networks. This interval bound propagation approach (IBP) not only has improved both robustness and certified accuracy but was the first to be employed on large/deep networks. However, due to the very loose nature of the IBP bounds, the required training procedure is complex and involved. In this paper, we closely examine the bounds of a block of layers composed in the form of Affine-ReLU-Affine. To this end, we propose expected tight bounds (true bounds in expectation), referred to as ETB, which are provably tighter than IBP bounds in expectation. We then extend this result to deeper networks through blockwise propagation and show that we can achieve orders of magnitudes tighter bounds compared to IBP. Furthermore, using a simple standard training procedure, we can achieve impressive robustness-accuracy trade-off on both MNIST and CIFAR10.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/1905.12418'
url_code: 'https://github.com/ModarTensai/ptb'
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
