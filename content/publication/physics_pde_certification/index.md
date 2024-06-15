---
title: Efficient Error Certification for Physics-Informed Neural Networks

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Francisco Eiras
- admin 
- Rudy Bunel
- Krishnamurthy Dvijotham
- Philip H.S. Torr
- M. Pawan Kumar




author_notes:
- ""
- ""
- ""
- ""


date: "2024-06-15"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Machine Learning
publication_short: International Conference on Machine Learning (**ICML24**)

abstract: Recent work provides promising evidence that Physics-Informed Neural Networks (PINN) can efficiently solve partial differential equations (PDE). However, previous works have failed to provide guarantees on the *worst-case* residual error of a PINN across the spatio-temporal domain - a measure akin to the tolerance of numerical solvers - focusing instead on point-wise comparisons between their solution and the ones obtained by a solver on a set of inputs. In real-world applications, one cannot consider tests on a finite set of points to be sufficient grounds for deployment, as the performance could be substantially worse on a different set. To alleviate this issue, we establish guaranteed error-based conditions for PINNs over their *continuous* applicability domain. To verify the extent to which they hold, we introduce ∂-CROWN; a general, efficient and scalable post-training framework to bound PINN residual errors. We demonstrate its effectiveness in obtaining tight certificates by applying it to two classically studied PINNs -- Burgers' and Schrödinger's equations --, and two more challenging ones with real-world applications -- the Allan-Cahn and Diffusion-Sorption equations.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2305.10157'
url_code: ''
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
