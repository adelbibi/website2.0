---
title: "Target Response Adaptation for Correlation Filter Tracking"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Matthias Müller
- Bernard Ghanem

# Author notes (optional)
author_notes:
- ""
- ""
- ""


date: "2016-10-08"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: European Conference on Computer Vision (ECCV16), IEEE
publication_short: Spotlight in *ECCV16*

abstract: ​​​​Most correlation filter (CF) based trackers utilize the circulant structure of the training data to learn a linear filter that best regresses this data to a hand-crafted target response. These circularly shifted patches are only approximations to actual translations in the image, which become unreliable in many realistic tracking scenarios including fast motion, occlusion, etc. In these cases, the traditional use of a single centered Gaussian as the target response impedes tracker performance and can lead to unrecoverable drift. To circumvent this major drawback, we propose a generic framework that can adaptively change the target response from frame to frame, so that the tracker is less sensitive to the cases where circular shifts do not reliably approximate translations. To do that, we reformulate the underlying optimization to solve for both the filter and target response jointly, where the latter is regularized by measurements made using actual translations. This joint problem has a closed form solution and thus allows for multiple templates, kernels, and multi-dimensional features. Extensive experiments on the popular OTB100 benchmark [19] show that our target adaptive framework can be combined with many CF trackers to realize significant overall performance improvement (ranging from 3%-13.5% in precision and 3.2%-13% in accuracy), especially in categories where this adaptation is necessary (e.g. fast motion, motion blur, etc.).


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1d6F5kXbXdR5QMMtolHveyULC2VnvBA6c/view?usp=sharing'
url_code: 'https://github.com/adelbibi/Target-Response-Adaptation-for-Correlation-Filter-Tracking'
url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1Wn-oj8iurZcyZw2ZJCsVxnUKqrNFw_3Q/view?usp=sharing'
url_project: ''
url_slides: 'https://drive.google.com/file/d/1MfGxjh651z9rX36ecSkkgWqYY1XzhZXd/view?usp=sharing'
url_source: ''
url_video: 'http://videolectures.net/eccv2016_bibi_target_response/?q=adel%20bibi'

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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

Supplementary material can be found [here](https://drive.google.com/file/d/1M46DLI4SSlqPI8uiw2DjhPO7rp9EIaiS/view?usp=sharing).
