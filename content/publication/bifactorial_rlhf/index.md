---
title: "Bi-Factorial Preference Optimization: Balancing Safety-Helpfulness in Language Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Wenxuan Zhang
- Philip H.S. Torr
- Mohamed Elhoseiny
- admin


# Author notes (optional)
author_notes:
- ""
- ""
- "Equal Advising"
- "Equal Advising"

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
publication_short: International Conference on Learning Representations (**ICLR25**) [<span style="color:red">Spotlight</span>]

abstract: Fine-tuning large language models (LLMs) on human preferences, typically through reinforcement learning from human feedback (RLHF), has proven successful in enhancing their capabilities. However, ensuring the safety of LLMs during the fine-tuning remains a critical concern, and mitigating the potential conflicts in safety and helpfulness is costly in RLHF. To address this issue, we propose a supervised learning framework called Bi-Factorial Preference Optimization (BFPO), which re-parameterizes a joint RLHF objective of both safety and helpfulness into a single supervised learning objective. In the supervised optimization, a labeling function is used to capture global preferences ranking to balance both safety and helpfulness. To evaluate BFPO, we develop a benchmark including comprehensive discriminative and generative tasks for helpfulness and harmlessness. The results indicate that our method significantly outperforms existing approaches in both safety and helpfulness. Moreover, BFPO eliminates the need for human prompting and annotation in LLM fine-tuning while achieving the same level of safety as methods that heavily rely on human labor, with less than 10% of the computational resources. The training recipes and models will be released.



# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2408.15313'
url_code: 'https://github.com/wx-zhang/bfpo'
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

