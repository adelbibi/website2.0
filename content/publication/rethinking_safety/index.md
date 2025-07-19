---
title: "Rethinking Safety in LLM Fine-tuning: An Optimization Perspective"


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Minseon Kim
- Jin Myung Kwak
- Lama Alssum
- Bernard Ghanem
- Philip Torr
- David Krueger
- Fazl Barez
- Adel Bibi

# Author notes (optional)
author_notes:
- ""
- ""
- ""

date: "2025-07-08"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Conference on Laguage Modeling
publication_short: Conference on Laguage Modeling (**COLM25**)

abstract: Fine-tuning language models is commonly believed to inevitably harm their safety, even when using harmless datasets, requiring additional safety measures. We challenge this belief through systematic testing, showing that poor optimization choices—not inherent trade-offs—often cause safety problems measured as harmful responses to adversarial prompts. By properly selecting key training hyper parameters—learning rate, batch size, and gradient steps—we reduce unsafe model responses from 16% to approximately 5% as measured by keyword matching and GPT-4 evaluation while maintaining utility performance. Based on this observation, we propose a simple exponential moving average (EMA) momentum technique in parameter space, that can preserve safety by creating a stable optimization path that retains the original model's safety properties. Our experiments on Llama families across multiple datasets (Dolly, Alpaca, ORCA) demonstrate that safety problems during fine-tuning can be largely avoided without specialized interventions, outperforming existing approaches that require additional safety data while offering practical guidelines for maintaining both model performance and safety during adaptation.


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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

