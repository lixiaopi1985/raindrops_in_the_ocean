---
title: Hands-On Nanopore MinION sequencer
subtitle: 

# Summary for listings and search engines
summary: 

# Link this post with a project
projects: [BoxwoodMicrobiome]

# Date published
date: '2022-07-04T00:00:00Z'

# Date updated
lastmod: '2022-07-04T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Loading libraries'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Nanopore MinION Sequencing
  -

categories:
  - Nanopore Sequencing
  - Microbiome
---

Nanopore MinION flowcell is a sequencing device smaller than your cellphone, while more expensive (you are looking at $700-$900 a piece). There are a few pros and cons based on my experience:

**Pros**

1) Very easy to load the library to the flowcell (However, the preparation of the library could be hectic and involves tedious steps). **First**, open the priming port cover and make sure there are no air bubbles in the duct (if there are any, suck the bubbles out following the instructions). **Second**, load 800 ul of the priming mix through the priming port slowly and steadly with a pipette. **Third**, open the SpotON cover, this is where you are going to load your libraries into. **Fourth**, Load another 200 ul of the priming mix through the priming port. **Fifth**, load your library dropwisely to the SpotON port. **Sixth**, put the covers back on, and you are good to go! Here is a video for loading library: [YouTube](https://youtu.be/Pt-iaemrM88).

2) The flowcell connects to the MinKNOW software that you use to control the sequencing process. The MinKNOW software interface is very clean and simple to use.

**Cons**

1) The storage of flowcell is short, only for 3 months, therefore you need to plan the sequencing carefully.
2) During sequencing, the heat produced by the flowcell and other chemical reactions will induced bubbles on the sensor array, which will jeopardize the longevity of the flowcell inevitably. Therefore, the longer the sequencing time, the more bubbles you would observe in the sensor array. And these bubbles can not be removed through following washing steps.
3) Although the MinION interface is simple and easy to navigate, it could be problematic when it connects to GUPPY software, a gigantic helper for faciliate basecalling using GPU powers. Because certain MinKNOW version is only compatible to certain GUPPY version, you need to keep up with the software updates and with some hacking skills in Linux environment to twitch it. These are not done automatically. I hope Nanopore can integrate GUPPY GPU to the MinKNOW software. 


Overall, MinION is a convenient and light weight sequencing devise suitable for many research scenarios. However, the flowcell and related software need improvement.