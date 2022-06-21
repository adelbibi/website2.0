---
title: Target Response Adaptation for Correlation Filter Tracking

event: European Conference on Computer Vision (ECCV16)
event_url: http://www.eccv2016.org/

location: Amsterdam, The Netherlands
# address:
#   street: 
#   city: 
#   region: 
#   postcode:
#   country: 

summary: 
abstract: Most correlation filter (CF) based trackers utilize the circulant structure of the training data to learn a linear filter that best regresses this data to a hand-crafted target response. These circularly shifted patches are only approximations to actual translations in the image, which become unreliable in many realistic tracking scenarios including fast motion, occlusion, etc. In these cases, the traditional use of a single centered Gaussian as the target response impedes tracker performance and can lead to unrecoverable drift. To circumvent this major drawback, we propose a generic framework that can adaptively change the target response from frame to frame, so that the tracker is less sensitive to the cases where circular shifts do not reliably approximate translations. To do that, we reformulate the underlying optimization to solve for both the filter and target response jointly, where the latter is regularized by measurements made using actual translations. This joint problem has a closed form solution and thus allows for multiple templates, kernels, and multi-dimensional features. Extensive experiments on the popular OTB100 benchmark show that our target adaptive framework can be combined with many CF trackers to realize significant overall performance improvement (ranging from 3 %–13.5 % in precision and 3.2 %–13 % in accuracy), especially in categories where this adaptation is necessary (e.g. fast motion, motion blur, etc.).

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2016-10-01T13:00:00Z'
date_end: '2016-10-02T13:00:00Z'
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
url_pdf: ""
url_slides: "https://docs.google.com/presentation/d/1MfGxjh651z9rX36ecSkkgWqYY1XzhZXd/edit?usp=sharing&ouid=105085779370076248797&rtpof=true&sd=true"
url_video: "https://www.youtube.com/watch?v=7GO0Srxxxw8&ab_channel=AdelBibi"

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

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
