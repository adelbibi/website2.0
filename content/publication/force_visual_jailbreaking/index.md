---
title: "FORCE: Transferable Visual Jailbreaking Attacks via Feature Over-Reliance CorrEction"

# Authors
authors:
- Runqi Lin
- Alasdair Paren
- Suqin Yuan
- Muyang Li
- Philip Torr
- admin
- Tongliang Liu

# Author notes (optional)
author_notes:
- ""
- ""
- ""
- ""
- ""
- "Equal contribution"
- "Equal contribution"

date: "2026-02-21"
doi: ""

publishDate: "2026-02-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Computer Vision and Pattern Recognition (**CVPR26**)
publication_short: Computer Vision and Pattern Recognition (**CVPR26**)

abstract: "The integration of new modalities enhances the capabilities of multimodal large language models (MLLMs) but also introduces additional vulnerabilities. In particular, simple visual jailbreaking attacks can manipulate open-source MLLMs more readily than sophisticated textual attacks. However, these underdeveloped attacks exhibit extremely limited cross-model transferability, failing to reliably identify vulnerabilities in closed-source MLLMs. In this work, we analyse the loss landscape of these jailbreaking attacks and find that the generated attacks tend to reside in high-sharpness regions, whose effectiveness is highly sensitive to even minor parameter changes during transfer. To further explain the high-sharpness localisations, we analyse their feature representations in both the intermediate layers and the spectral domain, revealing an improper reliance on narrow layer representations and semantically poor frequency components. Building on this, we propose a Feature Over-Reliance CorrEction (FORCE) method, which guides the attack to explore broader feasible regions across layer features and rescales the influence of frequency features according to their semantic content. By eliminating non-generalizable reliance on both layer and spectral features, our method discovers flattened feasible regions for visual jailbreaking attacks, thereby improving cross-model transferability. Extensive experiments demonstrate that our approach effectively facilitates visual red-teaming evaluations against closed-source MLLMs."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2509.21029'
url_code: 'https://github.com/tmllab/2026_CVPR_FORCE'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

projects: []
slides: ''
---
