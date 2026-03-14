---
title: "BiasBusters: Uncovering and Mitigating Tool Selection Bias in Large Language Models"

# Authors
authors:
- Thierry Blankenstein
- Jialin Yu
- Zixuan Li
- Vassilis Plachouras
- Sunando Sengupta
- Philip Torr
- Yarin Gal
- Alasdair Paren
- admin

# Author notes (optional)
author_notes:
- ""
- ""
- ""
- ""
- ""
- ""
- ""
- ""
- ""

date: "2026-01-27"
doi: ""

publishDate: "2026-01-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Learning Representations (**ICLR26**)
publication_short: International Conference on Learning Representations (**ICLR26**)

abstract: "Agents backed by large language models (LLMs) increasingly rely on external tools drawn from marketplaces where multiple providers offer functionally equivalent options. This raises a critical fairness concern: systematic bias in tool selection can degrade user experience and distort competition by privileging certain providers over others. We introduce a benchmark of diverse tool categories, each containing multiple functionally equivalent tools, to systematically evaluate tool-selection bias. Using this benchmark, we evaluate seven LLMs and show that substantial bias persists, with models either fixating on a single provider or disproportionately favoring tools that appear earlier in the context. To uncover the sources of this behavior, we conduct controlled experiments that isolate the effects of tool features, exposed metadata (name, description, and parameters), and pre-training exposure. We find that (1) semantic alignment between user queries and tool metadata is the strongest driver of selection; (2) small perturbations to tool descriptions can significantly shift choices; and (3) repeated pre-training exposure to a single endpoint amplifies provider-level bias. Finally, we propose a lightweight mitigation strategy that first filters tools to a relevant subset and then samples uniformly, substantially reducing selection bias while maintaining strong task coverage. Our results highlight tool-selection bias as a key obstacle to the fair deployment of tool-augmented LLM agents."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2510.00307'
url_code: 'https://github.com/thierry123454/tool-selection-bias'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

projects: []
slides: ''
---
