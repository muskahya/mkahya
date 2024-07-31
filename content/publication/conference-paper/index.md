---
title: "FOOD: Real-Time Human Presence and Out-of-Distribution Detection Using FMCW Radar"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Boran Hamdi Sivrikaya
  - Muhammet Sami Yavuz
  - Eckehard Steinbach

# Author notes (optional)
author_notes: ""
  #- 'Equal contribution'
  #- 'Equal contribution'

date: "2024-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Image Processing*
publication_short: In *ICIP*

abstract: This paper proposes a short-range FMCW radar-based facial authentication and out-of-distribution (OOD) detection framework. Our pipeline jointly estimates the correct classes for the in-distribution (ID) samples and detects the OOD samples to prevent their inaccurate prediction. Our reconstruction-based architecture consists of a main convolutional block with one encoder and multi-decoder configuration, and intermediate linear encoder-decoder parts. Together, these elements form an accurate human face classifier and a robust OOD detector. For our dataset, gathered using a 60 GHz short-range FMCW radar, our network achieves an average classification accuracy of 98.07% in identifying in-distribution human faces. As an OOD detector, it achieves an average Area Under the Receiver Operating Characteristic (AUROC) curve of 98.50% and an average False Positive Rate at 95% True Positive Rate (FPR95) of 6.20%. Also, our extensive experiments show that the proposed approach outperforms previous OOD detectors in terms of common OOD detection metrics.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/pdf/2406.04546
url_code: ''
url_dataset: 'https://syncandshare.lrz.de/getlink/fiQoBoPTK8npvXzYdTfr6a'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
