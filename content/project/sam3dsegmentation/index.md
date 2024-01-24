---
title:  3D Point Cloud Segmentation using Segment Anything Model (SAM)
summary: Segment Anything Model (SAM) is designed and trained to be promptable and shows strong zero-shot image segmentation capability. 3D point cloud segmentation is a challenging task due to the lack of labeled data. We designed a SAM-based 3D point cloud segmentation workflow and it improves the efficiency of 3D point cloud segmentation. High quality 3D point cloud is projected into 2D images using intensity or RGB information of the point cloud. Image embeddings are extracted using the image encoder of the Mobile SAM, a lightweight version of SAM suitable for mobile applications, and can be queried by prompts to generate segmentation masks. The segmentation masks are then projected back to the 3D point cloud to generate the final segmentation results.
tags:
  - Dashboard
date: '2021-09-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: video
    icon_pack: custom
    name: paper (under review)
    url: 

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---