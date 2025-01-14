---
title: One paper was accepted at the NeurIPS 2022 conference. Click here for more info.
# subtitle: Welcome 👋 We know that first impressions are important, so we've populated your new ite with some initial content to help you get familiar with everything in no time.

# Summary for listings and search engines
# summary: Welcome 👋 We know that first impressions are important, so we've populatReceived the Diversity and Inclusion Scholarship from the ME Department at CU Bouldered your new site with some initial content to help you get familiar with everything in no time.

# Link this post with a project
projects: []

# Date published
date: '2022-09-14T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

reading_time: false

authors:
  - admin

links:
- name: arXiv
  url: https://arxiv.org/abs/2206.07811

url_pdf: 'https://arxiv.org/abs/2206.07811'
url_code: 'https://github.com/aria-systems-group/NeuralNetControlBarrier'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://neurips.cc/virtual/2022/poster/52992'

summary: "TL;DR: In this work, we introduce a method of safety certification and control for neural network dynamic systems via stochastic barrier functions."

# authors:
#   - admin

# tags:
#   - Academic

# categories:
#   - Demo
---
**Paper Title**: Safety Guarantees for Neural Network Dynamic Systems via Stochastic Barrier Functions


**Abstract**: Neural Networks (NNs) have been successfully employed to represent the state evolution of complex dynamical systems.  Such models, referred to as NN dynamic models (NNDMs), use iterative noisy predictions of NN to estimate a distribution of system trajectories over time. Despite their accuracy, safety analysis of NNDMs is known to be a challenging problem and remains largely unexplored.  To address this issue, in this paper, we introduce a method of providing safety guarantees for NNDMs.  Our approach is based on stochastic barrier functions, whose relation with safety are analogous to that of Lyapunov functions with stability.  We first show a method of synthesizing stochastic barrier functions for NNDMs via a convex optimization problem, which in turn provides a lower bound on the system's safety probability.  A key step in our method is the employment of the recent convex approximation results for NNs to find piece-wise linear bounds, which allow the formulation of the barrier function synthesis problem as a sum-of-squares optimization program.  If the obtained safety probability is above the desired threshold, the system is certified.  Otherwise, we introduce a method of generating controls for the system that robustly minimize the unsafety probability in a minimally-invasive manner.  We exploit the convexity property of the barrier function to formulate the optimal control synthesis problem as a linear program.  Experimental results illustrate the efficacy of the method. Namely, they show that the method can scale to multi-dimensional NNDMs with multiple layers and hundreds of neurons per layer, and that the controller can significantly improve the safety probability.