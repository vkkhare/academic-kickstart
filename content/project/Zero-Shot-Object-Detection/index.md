---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Zero Shot Object Detection"
summary: "Zero shot detection greatly exacerbates the the problem of zero shot recognition. Not only training the classifiers pose a problem, we have to make the region proposal network learn to detect objects from unseen categories. These during training typically lie in the background. Our novelty lies in exploiting the consistency of the attribute discriptions via learning to detect attributes first and then combining these detections by a combinator module to get final bounding boxes.This is work in progress and we aim to publish our results soon."

authors_list: ["Varun Kumar Khare*", "Harshvardhan*", "Divyat Mahajan*"]
tags: ["object_detection","deep_learning","computer_vision","zero_shot","transformer_networks"]
categories: []
date: 2019-07-11T10:02:51+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "The image has been taken from [Ankan Bansal et al.](http://ankan.umiacs.io/zsd.html)"
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
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Zero shot detection greatly exacerbates the the problem of zero shot recognition. Not only training the classifiers pose a problem, we have to make the region proposal network learn to detect objects from unseen categories. These during training typically lie in the background.

Our novelty lies in exploiting the visual consistency of the attributes via learning to detect attributes first and then combining these detections by a combinator module into final object detections. We employ spatial transformer networks to propagate the gradients across the combinator and RPNs. This was necessary due to unavailability of external bounding box annotations for attributes. It made it impossible to train RPN and combinator independently from classifier unlike faster-RCNN style architectures. 

This is work in progress and we aim to publish our results soon."
