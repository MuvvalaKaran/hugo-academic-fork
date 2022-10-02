---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Regret games for manipulation reactive synthesis'
event: "Talk at Dr. Moshe Vardi's Group - LAPIS"
# event_url:
# location:
# address:
#   street:
#   city:
#   region:
#   postcode:
#   country:
summary: Gave a talk on my MS Thesis work at Dr. Vardi's group at Rice University
abstract:

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2021-05-04T00:00:00Z'
date_end: '2021-05-04T00:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-07-24T00:00:00Z'

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
url_slides: 'https://drive.google.com/file/d/14OFimNO47gQZceOy9jRBDscSGnSjJzA_/view?usp=sharing'

url_code:
url_pdf:
url_video:

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

From factories to households, robots are rapidly leaving behind their robot-centric environments and entering our society. To be successful in our human-centric world, they must develop the ability to interact with unstructured environments. This includes performing complex tasks in face of changes in the environment and seeking collaborations with humans when possible. Achieving such capabilities is challenging, especially in the robotic manipulation domain, where tasks are complex and crucially require interaction with humans. In this talk, we propose a regret-based reactive synthesis framework to address some of these challenges. Intuitively, regret is a qualitative measure of the current action. If the action is optimal to the human’s response in hindsight, its regret is zero; otherwise, it is a positive value. Our aim is to synthesize strategies that minimize robot's regret. This approach, unlike existing work, allows the robot not to necessarily view the human as an adversary, and hence, enabling it to explore cooperation with humans to accomplish a given task. Our focus is specifically on robotic manipulators with temporal logic task specifications in shared workspaces with humans. We show theoretical guarantees on task completion through reachability analysis by modeling the interaction as a two-player deterministic finite automaton game. We analyze various notions of regret, provide algorithms for their computations, and reason about the emergent behaviors. We illustrate the strengths of this framework through several case studies.