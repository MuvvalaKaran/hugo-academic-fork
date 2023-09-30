---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Efficient Symbolic Approaches for Quantitative Reactive Synthesis with Finite Tasks'
event: "Talk at Dr. Moshe Vardi's Group - LAPIS"
# event_url:
# location:
# address:
#   street:
#   city:
#   region:
#   postcode:
#   country:
summary: Gave a talk on my Symbolic Reactive Synthesis work (IROS 23) at Dr. Vardi's group at Rice University
abstract:

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-04-26T00:00:00Z'
date_end: '2023-04-26T00:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-09-29T00:00:00Z'

authors: [admin]
tags: []

# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: 'https://drive.google.com/file/d/1tGaAKBsDlWdC6GP8vTVyH6907puHhoUR/view?usp=sharing'
url_code: 'https://github.com/aria-systems-group/sym_quant_reactive_synth'
url_pdf: 'https://arxiv.org/abs/2303.03686'
url_video: 'https://riceuniversity.zoom.us/rec/play/EH1-r6IVZd_rvUTT3rfYK-PRY4M5CttOJyzkTzt1RCJRgjfffSJcDFUanSiSXkV9Y5XkvXHXwX4kzmPa.2cUH7mK5gYc79tZf?canPlayFromShare=true&from=share_recording_detail&continueMode=true&componentName=rec-play&originRequestUrl=https%3A%2F%2Friceuniversity.zoom.us%2Frec%2Fshare%2Fh---5zus6VxugyhnmGdgwKlm9_fhxELSqqhRaYSlGV5972qP8Zq2gLARmfPYxVur.hzA27L5YLTzEuhrj'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

In this talk, we will introduce efficient symbolic algorithms for quantitative reactive synthesis using Algebraic Decision Diagrams (ADDs). We consider resource-constrained robotic manipulators that need to interact with a human to achieve a complex task expressed in linear temporal logic over finite trace (LTLf). Our framework generates reactive strategies that not only guarantee task completion but also seek cooperation with the human when possible. 

We model the interaction as a two-player game and consider regret-minimizing strategies to encourage cooperation. We use symbolic representation of the game to enable scalability. For synthesis, we first introduce value iteration algorithms for such games with min-max objectives. Then, we extend our method to the regret-minimizing objectives. Our benchmarks reveal that our symbolic framework not only significantly improves computation time (up to an order of magnitude) but also can scale up to much larger instances of manipulation problems with up to 2x the number of objects and locations than the state of the art.
