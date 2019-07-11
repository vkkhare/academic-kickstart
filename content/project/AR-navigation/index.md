---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "AR Navigation"
summary: "This is an android app that relays computer graphics like arrows on real time camera feed for navigation. The app uses data from in-mobile sensors and google maps API to identify roads on the screen."
authors: ["varun"]
tags: [augmented_reality]
categories: [project]
date: 2016-07-06 16:42:00 +0530 

# Optional external URL for project (replaces project detail page).
external_link: ""

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

url_code: "https://github.com/vkkhare/augmented-reality-app"
url_pdf: ""
url_slides: ""
url_video: "https://youtu.be/Cnm6HZRYHeg"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
### About The Project
We tried out experimenting Augmented Reality as a summer project. Our aim was to design a navigation app which instead of showing top view of map shows directions on real time camera feed. This will have two fold benefits: 

* The users will not have to match roads and adjust map to understand where to go
* Since it shows real time camera feed the user can remain in real world while looking for directions preventing accidents
* Received the **Best Programming Club Project** during the Science & Technology Summer Camp 2016.

### Approach to inculcate AR in android app
Unlike infrared sensors we didn't have any means to calculate the exact distance of the real time objects in the mobiles so we switched to MATHEMATICS for our answers. OH! Technical Arts also played a key role in devising our strategy.

* We used GPS data combiined with mobiles orientation from Magnetic Compass to detect roads. Here Google Directions API came in handy to give the precise coordinates of the roads.

* We measured the relative motion of the user via gyroscope, accelerometer and GPS coordinates

* The Unity graphics were relayed on the camera feed via UNITY GAME ENGINE giving the graphics (navigating arrows) a psuedo-acceleration to look static on the ground.

### References
* [https://www.sitepoint.com/how-to-build-an-ar-android-app-with-vuforia-and-unity/](https://www.sitepoint.com/how-to-build-an-ar-android-app-with-vuforia-and-unity/)
* Android Documentation

