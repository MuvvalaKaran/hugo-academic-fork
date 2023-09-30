---
title: "Efficient Symbolic Approaches for Quantitative Reactive Synthesis with Finite Tasks (IROS 23)"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Morteza Lahijanian 

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-09-129T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-29T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
# publication: submitted to *Advances in Neural Information Processing Systems*
publication_short: Accepted to *IROS 23*

abstract: This work introduces efficient symbolic algorithms for quantitative reactive synthesis. We consider resource-constrained robotic manipulators that need to interact with a human to achieve a complex task expressed in linear temporal logic. Our framework generates reactive strategies that not only guarantee task completion but also seek cooperation with the human when possible. We model the interaction as a two-player game and consider regret-minimizing strategies to encourage cooperation. We use symbolic representation of the game to enable scalability. For synthesis, we first introduce value iteration algorithms for such games with min-max objectives. Then, we extend our method to the regret-minimizing objectives. Our benchmarks reveal that our symbolic framework not only significantly improves computation time (up to an order of magnitude) but also can scale up to much larger instances of manipulation problems with up to 2x number of objects and locations than the state of the art.

# Summary. An optional shortened abstract.
summary: In this work, we introduce a method of symbolic value iteration for quantitative tow-player games with reachability objectives and with resource constraints.
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Experiments
  url: https://youtu.be/U8OcLttQ3Hk

url_pdf: 'https://arxiv.org/abs/2303.03686'
url_code: 'https://github.com/aria-systems-group/sym_quant_reactive_synth'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/uy88Cc8DFfQ'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
