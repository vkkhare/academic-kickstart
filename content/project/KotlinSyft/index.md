---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "KotlinSyft"
summary: "KotlinSyft makes it easy for you to **train and execute PySyft models on Android devices**. This allows you to utilize training data located directly on the device itself, bypassing the need to send a user's data to a central server.

[The first use case for our library is here](https://blog.openmined.org/apheris-openmined-pytorch-announcement)"

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
KotlinSyft makes it easy for you to **train and execute PySyft models on Android devices**. This allows you to utilize training data located directly on the device itself, bypassing the need to send a user's data to a central server. This is known as [federated learning](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html).

- :gear: **Training and inference** of any PySyft model written in PyTorch or TensorFlow
- :bust_in_silhouette: Allows all data to stay on the user's device
- :zap: Support for full multi-threading / background service execution
- :key: Support for **JWT authentication** to protect models from Sybil attacks
- :+1: A set of **inbuilt best practices** to prevent apps from over using device resources.
  - :electric_plug: **Charge detection** to allow background training only when device is connected to charger
  - :zzz: **Sleep and wake detection** so that the app does not occupy resource when user starts using the device
  - :money_with_wings: **Wifi and metered network detection** to ensure the model updates do not use all the available data quota
  - :no_bell: All of these smart defaults are easily are **overridable**
- :mortar_board: Support for both reactive and callback patterns so you have your freedom of choice (_in progress_)
- :lock: Support for **secure multi-party computation** and **secure aggregation** protocols using **peer-to-peer WebRTC** connections (_in progress_).

There are a variety of additional privacy-preserving protections that may be applied, including [differential privacy](https://towardsdatascience.com/understanding-differential-privacy-85ce191e198a), [muliti-party computation](https://www.inpher.io/technology/what-is-secure-multiparty-computation), and [secure aggregation](https://research.google/pubs/pub45808/).

[OpenMined](https://openmined.org) set out to build the **world's first open-source ecosystem for federated learning on web and mobile**. KotlinSyft is a part of this ecosystem, responsible for bringing secure federated learning to Android devices. You may also train models on iOS devices using [SwiftSyft](https://github.com/OpenMined/SwiftSyft) or in web browsers using [syft.js](https://github.com/OpenMined/syft.js).

If you want to know how scalable federated systems are built, [Towards Federated Learning at Scale](https://arxiv.org/pdf/1902.01046.pdf) is a fantastic introduction! 

Join us in the movement at [Slack](http://slack.openmined.org/)!
