---
title: Mixture of Experts Made Intrinsically Interpretable


# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:

- Xingyi Yang
- Constantin Venhoff
- Ashkan Khakzar
- Christian Schroeder de Witt
- Puneet K Dokania
- admin
- Philip Torr


author_notes:
- ""
- ""
- ""
- ""


date: "2025-05-05"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Machine Learning
publication_short: International Conference on Machine Learning (ICML25)

abstract: Neurons in large language models often exhibit polysemanticity, simultaneously encoding multiple unrelated concepts and obscuring interpretability. Instead of relying on post-hoc methods, we present MoE-X, a Mixture-of-Experts (MoE) language model designed to be intrinsically interpretable. Our approach is motivated by the observation that, in language models, wider networks with sparse activations are more likely to capture interpretable factors. However, directly training such large sparse networks is computationally prohibitive. MoE architectures offer a scalable alternative by activating only a subset of experts for any given input, inherently aligning with interpretability objectives. In MoE-X, we establish this connection by rewriting the MoE layer as an equivalent sparse, large MLP. This approach enables efficient scaling of the hidden size while maintaining sparsity. To further enhance interpretability, we enforce sparse activation within each expert and redesign the routing mechanism to prioritize experts with the highest activation sparsity. These designs ensure that only the most salient features are routed and processed by the experts. We evaluate MoE-X on chess and natural language tasks, showing that it achieves performance comparable to dense models while significantly improving interpretability. MoE-X achieves a perplexity better than GPT-2, with interpretability surpassing even sparse autoencoder (SAE)-based approaches.



# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2503.07639'
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
