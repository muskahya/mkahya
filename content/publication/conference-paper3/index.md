---
title: "FARE: A Deep Learning-Based Framework for Radar-Based Face Recognition and Out-of-Distribution Detection"

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

date: "2025-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Acoustics, Speech and Signal Processing*
publication_short: In *ICASSP*

abstract: In this work, we propose a novel pipeline for face recognition and out-of-distribution (OOD) detection using shortrange FMCW radar. The proposed system utilizes RangeDoppler and micro Range-Doppler Images. The architecture features a primary path (PP) responsible for the classification of in-distribution (ID) faces, complemented by intermediate paths (IPs) dedicated to OOD detection. The network is trained in two stages; first, the PP is trained using triplet loss to optimize ID face classification. In the second stage, the PP is frozen, and the IPs—comprising simple linear autoen-coder networks—are trained specifically for OOD detection. Using our dataset generated with a 60 GHz FMCW radar, our method achieves an ID classification accuracy of 99.30% and an OOD detection AUROC of 96.91%.
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

url_pdf: https://ieeexplore.ieee.org/abstract/document/10889758
url_code: ''
url_dataset: 'https://syncandshare.lrz.de/getlink/fiJ1ZPazuTkCGgUGnQAGVG/'
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
