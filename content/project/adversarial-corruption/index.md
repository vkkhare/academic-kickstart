---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Adversarial Corruption"
summary: "This work aims to derive a non-trivial breakdown point for an algorithm for training a single hiddenlayer Neural Network. In pursuit of this goal, we propose two algorithms for training a network with ReLU activations. The first approach utilizes the partitioning property of the ReLU function while the second approach utilizes the convexity of the activation function."
authors: []
tags: ["deep_learning","theory","adversarial_corruption","ReLU"]
categories: ["research"]
date: 2018-04-11T09:57:10+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "image credits to [Ian Goodfellow et al.](https://cacm.acm.org/magazines/2018/7/229030-making-machine-learning-robust-against-adversarial-inputs/fulltext)"
  focal_point: "Center"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: "files/CS777.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Neural Networks have been observed to be robust to even adversarial corruptions. However, only a handful of theoretical results exist which guarantee robustness of NNs. We have made an attempt to address this, using results and techniques from robust statistics.
To measure the robustness of an algorithm, we want to derive its breakdown point which is the largest number of adversarially corrupted points an algorithm can handle and still guarantee recovery. The presence of breakdown point results for simpler learners like linear regression was a primary motivation to pursue this project using robust statistics.

To simplify the problem, we consider the case of regression only single hidden layer neural networks with ReLU activation on each node and an output node with no activation with squared loss function. We analysed two different training procedures and how it can change the training trajectory to affect the final convergence. One apprach utilised the property of **ReLU** of dividing the input space into 2 halves (active and unactive). Another approach split the problem as a difference of convex functions and we used alternating optimization to train it. This training procedure was well behaved in terms of convergence and theoretically sound.

For complete details about these approaches please look in the attached pdf.
