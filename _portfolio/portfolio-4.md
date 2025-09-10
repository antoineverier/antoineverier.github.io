---
title: "Haze removal by He & al."
excerpt: "Implemented the haze removal paper by He, browser-use.<br/><img src='/images/forest.png'>"
collection: portfolio
category: "Image processing"
tags: ["Haze removal", "Image processing", "Dehazing", "OpenCV"]
---

In this project, I implemented with one collegue the haze removal algorithm proposed by Kaiming He and colleagues in their 2009 paper "Single Image Haze Removal Using Dark Channel Prior". The algorithm is based on the observation that in most non-sky patches of haze-free outdoor images, at least one color channel has some pixels with very low intensity values, known as the dark channel. By estimating the transmission map and atmospheric light, the algorithm effectively removes haze from images, enhancing visibility and contrast.

# Link to the github repository :
[Here](https://github.com/antoineverier/implementation-haze-removal)