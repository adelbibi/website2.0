---
title: "Analytic Expressions for Probabilistic Moments of PL-DNN with Gaussian Input"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Modar Alfadly
- Bernard Ghanem

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- ""

date: "2018-03-07"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Conference on Computer Vision and Pattern Recognition (CVPR18), IEEE
publication_short: Conference on Computer Vision and Pattern Recognition (**CVPR18**) [<span style="color:red">Oral</span>]

abstract: The outstanding performance of deep neural networks (DNNs), for the visual recognition task in particular, has been demonstrated on several large-scale benchmarks. This performance has immensely strengthened the line of research that aims to understand and analyze the driving reasons behind the effectiveness of these networks. One impor- tant aspect of this analysis has recently gained much attention, namely the reaction of a DNN to noisy input. This has spawned research on developing adversarial input attacks as well as training strategies that make DNNs more robust against these attacks. To this end, we derive in this paper exact analytic expressions for the first and second moments (mean and variance) of a small piecewise linear (PL) network (Affine, ReLU, Affine) subject to general Gaussian input. We experimentally show that these expressions are tight under simple linearizations of deeper PL-DNNs, especially popular architectures in the literature (e.g. LeNet and AlexNet). Extensive experiments on image classifica- tion show that these expressions can be used to study the behaviour of the output mean of the logits for each class, the interclass confusion and the pixel-level spatial noise sensitivity of the network. Moreover, we show how these expres- sions can be used to systematically construct targeted and non-targeted adversarial attacks.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1qAiIQ7FRYI0nb49RC02McwaGfks2pafe/view?usp=sharing'
url_code: 'https://github.com/ModarTensai/network_moments'
url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1f96rHMMyRSBoQfrwoLgEMmgizZbMXATQ/view?usp=sharing'
url_project: ''
url_slides: 'https://drive.google.com/file/d/1cu2jdYItdPblB_MJoWIL73n_tDtRy0xV/view?usp=sharing'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=op9IBox_TTc&t=945s'

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

Supplementary material can be found [here](https://drive.google.com/file/d/17tGxceooVTT0JFkBsQjsh3h529U7yI1v/view?usp=sharing).
