---
title: FedMedICL; Towards Holistic Evaluation of Distribution Shifts in Federated Medical Imaging


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Kumail Alhamoud
- Yasir Ghunaim
- Motasem Alfarra
- Thomas Hartvigsen
- Philip H.S. Torr
- Bernard Ghanem
- admin
- Marzyeh Ghassemi

author_notes:
- "Equal contribution"
- "Equal contribution"
- ""
- ""


date: "2024-07-07"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The Medical Image Computing and Computer Assisted Intervention Society 
publication_short: The Medical Image Computing and Computer Assisted Intervention Society (**MICCAI24**)

abstract: For medical imaging AI models to be clinically impactful, they must generalize. However, this goal is hindered by (i) diverse types of distribution shifts, such as temporal, demographic, and label shifts, and (ii) limited diversity in datasets that are siloed within single medical institutions. While these limitations have spurred interest in federated learning, current evaluation benchmarks fail to evaluate different shifts simultaneously. However, in real healthcare settings, multiple types of shifts co-exist, yet their impact on medical imaging performance remains unstudied. In response, we introduce FedMedICL, a unified framework and benchmark to holistically evaluate federated medical imaging challenges, simultaneously capturing label, demographic, and temporal distribution shifts. We comprehensively evaluate several popular methods on six diverse medical imaging datasets (totaling 550 GPU hours). Furthermore, we use FedMedICL to simulate COVID-19 propagation across hospitals and evaluate whether methods can adapt to pandemic changes in disease prevalence. We find that a simple batch balancing technique surpasses advanced methods in average performance across FedMedICL experiments. This finding questions the applicability of results from previous, narrow benchmarks in real-world medical settings.


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2407.08822'
url_code: 'https://github.com/m1k2zoo/FedMedICL'
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
