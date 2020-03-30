---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "KotlinSyft"
summary: "This is the android worker Library for [PySyft](https://github.com/OpenMined/PySyft)

Of course, [PySyft](https://github.com/openmined/pysyft) has the ability to run in its own environment but the training procedure needs to deployed on the mobile workers using Torchscript.This is where KotlinSyft comes. **KotlinSyft employs P2P connectivity for realization of distributed pysyft protocols.** "

tags: ["security","deep_learning","privacy","open_source"]
categories: []
date: 2019-07-11T10:02:51+05:30

# Optional external URL for project (replaces project detail page).
#external_link: "https://github.com/OpenMined/KotlinSyft"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  focal_point: "Center"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/OpenMined/KotlinSyft"
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

PySyft is a Python library for secure and private Deep Learning. PySyft decouples private data from model training, using
[Federated Learning](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html),
[Differential Privacy](https://en.wikipedia.org/wiki/Differential_privacy),
and Encrypted Computation (like
[Multi-Party Computation (MPC)](https://en.wikipedia.org/wiki/Secure_multi-party_computation)
and  [Homomorphic Encryption (HE)](https://en.wikipedia.org/wiki/Homomorphic_encryption))
within the main Deep Learning frameworks like PyTorch and TensorFlow. Join the movement on
[Slack](http://slack.openmined.org/).


KotlinSyft employs P2P connectivity for realization of distributed pysyft protocols on android workers. The local training is performed using PyTorch as a background service. [https://blog.openmined.org/apheris-openmined-pytorch-announcement](The first use case for our andorid worker library is here)
