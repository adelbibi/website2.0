---
title: "Illusory Attacks: Detectability Matters in Adversarial Attacks on Sequential Decision-Makers"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tim Franzmeyer 
- Stephen Marcus McAleer
- Joao F. Henriques
- Jakob Nicolaus Foerster
- Philip H.S. Torr
- admin
- Christian Schroeder de Witt


author_notes:
- ""
- ""
- ""
- ""


date: "2024-01-21"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Learning Representations
publication_short: International Conference on Learning Representations (**ICLR24**) [<span style="color:red">Spotlight</span>]

abstract: Autonomous agents deployed in the real world need to be robust against adversarial attacks on sensory inputs. Robustifying agent policies requires anticipating the strongest attacks possible. We demonstrate that existing observation-space attacks on reinforcement learning agents have a common weakness; while effective, their lack of information-theoretic detectability constraints makes them detectable using automated means or human inspection. Detectability is undesirable to adversaries as it may trigger security escalations. We introduce illusory attacks, a novel form of adversarial attack on sequential decision-makers that is both effective and of bounded statistical detectability. We propose a novel dual ascent algorithm to learn such attacks end-to-end. Compared to existing attacks, we empirically find illusory attacks to be significantly harder to detect with automated methods, and a small study with human subjects suggests they are similarly harder to detect for humans. Our findings suggest the need for better anomaly detectors, as well as effective hardware and system-level defenses.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2207.10170'
url_code: 'https://github.com/fratim/Illu-Attacks-Jax'
url_dataset: ''
url_poster: ''
url_project: 'https://www.robots.ox.ac.uk/~vgg/research/illusory-attacks/'
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
