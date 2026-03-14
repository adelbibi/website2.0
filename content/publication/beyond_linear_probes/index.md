---
title: "Beyond Linear Probes: Dynamic Safety Monitoring for Language Models"

# Authors
authors:
- James Oldfield
- Philip Torr
- Ioannis Patras
- admin
- Fazl Barez

# Author notes (optional)
author_notes:
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

abstract: "Monitoring large language models' (LLMs) activations is an effective way to detect harmful requests before they lead to unsafe outputs. However, traditional safety monitors often require the same amount of compute for every query. This creates a trade-off: expensive monitors waste resources on easy inputs, while cheap ones risk missing subtle cases. We argue that safety monitors should be flexible--costs should rise only when inputs are difficult to assess, or when more compute is available. To achieve this, we introduce Truncated Polynomial Classifiers (TPCs), a natural extension of linear probes for dynamic activation monitoring. Our key insight is that polynomials can be trained and evaluated progressively, term-by-term. At test-time, one can early-stop for lightweight monitoring, or use more terms for stronger guardrails when needed. TPCs provide two modes of use. First, as a safety dial: by evaluating more terms, developers and regulators can buy stronger guardrails from the same model. Second, as an adaptive cascade: clear cases exit early after low-order checks, and higher-order guardrails are evaluated only for ambiguous inputs, reducing overall monitoring costs. On two large-scale safety datasets (WildGuardMix and BeaverTails), for 4 models with up to 30B parameters, we show that TPCs compete with or outperform MLP-based probe baselines of the same size, all the while being more interpretable than their black-box counterparts."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2509.26238'
url_code: 'https://github.com/james-oldfield/tpc'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

projects: []
slides: ''
---
