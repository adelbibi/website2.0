---
title: "ANCER: Anisotropic Certification via Sample-wise Volume Maximization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Francisco Eiras
- Motasem Alfarra
- Philip H.S. Torr
- Pawan Kumar
- Puneet K. Dokania
- Bernard Ghanem
- admin

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- ""
- ""
- ""
- ""
- "Equal contribution"

date: "2022-08-28"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Transactions of Machine Learning Research
publication_short: Transactions of Machine Learning Research (**TMLR22**)

abstract: Randomized smoothing has recently emerged as an effective tool that enables certification of deep neural network classifiers at scale. All prior art on randomized smoothing has focused on isotropic $\ell_p$ certification, which has the advantage of yielding certificates that can be easily compared among isotropic methods via $\ell_p$-norm radius. However, isotropic certification limits the region that can be certified around an input to worst-case adversaries, i.e., it cannot reason about other "close", potentially large, constant prediction safe regions. To alleviate this issue, (i) we theoretically extend the isotropic randomized smoothing $\ell_1$ and $\ell_2$ certificates to their generalized anisotropic counterparts following a simplified analysis. Moreover, (ii) we propose evaluation metrics allowing for the comparison of general certificates - a certificate is superior to another if it certifies a superset region - with the quantification of each certificate through the volume of the certified region. We introduce ANCER, a framework for obtaining anisotropic certificates for a given test set sample via volume maximization. We achieve it by generalizing memory-based certification of data-dependent classifiers. Our empirical results demonstrate that ANCER achieves state-of-the-art $\ell_1$ and $\ell_2$ certified accuracy on CIFAR-10 and ImageNet in the data-dependence setting, while certifying larger regions in terms of volume, highlighting the benefits of moving away from isotropic analysis.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/forum?id=7j0GI6tPYi'
url_code: 'https://github.com/MotasemAlfarra/ANCER'
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
