---
title: "Computer Vision based First Floor Elevation Estimation from Mobile LiDAR Data"
authors:
- Jiahao Xia
- Jie Gong
date: "2023-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Automation in Construction"
publication_short: ""

abstract: First Floor Elevation (FFE) of a house is crucial information for flood management and for accurately assessing the flood exposure risk of a property. However, the lack of reliable FFE data on a large geographic scale significantly limits efforts to mitigate flood risk, such as decision on elevating a property. The traditional method of collecting elevation data of a house relies on time-consuming and labor-intensive on-site inspections conducted by licensed surveyors or engineers. In this paper, we propose an automated and scalable method for extracting FFE from mobile LiDAR point cloud data. The fine-tuned yolov5 model is employed to detect doors, windows, and garage doors on the intensity-based projection of the point cloud, achieving an mAP@0.5:0.95 of 0.689. Subsequently, FFE is estimated using detected objects. We evaluated the Median Absolute Error (MAE) metric for the estimated FFE in Manville, Ventnor, and Longport, which resulted in values of 0.2 feet, 0.27 feet, and 0.24 feet, respectively. The availability of FFE data has the potential to provide valuable guidance for setting flood insurance premiums and facilitating benefit-cost analyses of buyout programs targeting residential buildings with a high flood risk.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

links:
# - name:
#   url:
# url_pdf:
# url_code: 
# url_dataset:
# url_poster: 
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption:
#   focal_point:
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides:
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
