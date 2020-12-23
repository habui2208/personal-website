---
title: Facial Expression Recognition with Deep Learning
summary: In this project, we implemented a face detection model using Detectron2 and several different machine learning algorithms such as k-nearest neighbors (”KNN”), multi-layer perceptron (”MLP”), and convolutional neural net (”CNN”) for the facial expression recognition. Our models are trained on two separate imagebased data sets. We were able to achieve a 70% AP50 with our face detection model and our best facial expression recognition model achieved an accuracy of 65%.
tags:
  - Deep Learning
  - Computer Vision
date: "2020-12-11T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

While there are about 27 different human emotions, in this project, we plan to work with labeled data sets with seven distinct human emotions: happiness, sadness, fear, anger,
surprise, disgust, and neutral. We aim to implement a twostep model: first, localize human faces in an image and second, recognize emotion expressed in those faces.

Our first data set (’Dataset 1’), which is provided and maintained by Dataturks, has about 400 images with a bit more than 1000 faces. The data is available as a JSON file with 2 main components, an URL address of the image, and the face labels and bounding boxes of that image. We extracted those information from the JSON file, made an annotate function, and showed the images with the correct bounding boxes for the faces.
