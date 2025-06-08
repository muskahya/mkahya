---
title: "RFOOD: Real-time Facial Authentication and Out -of-distribution Detection with Short-range FMCW Radar"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Muhammet Sami Yavuz
  - Boran Hamdi Sivrikaya
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
publication: In *International Conference on Machine Learning and Applications*
publication_short: In *ICMLA*

abstract: Out-of-distribution (OOD) detection is critical for the safe deployment of modern neural network architectures, as it aims to identify samples outside the training domain. In this paper, we introduce RFOOD, a novel OOD detection framework designed for real-time, privacy-preserving facial authentication using low-cost frequency-modulated continuous-wave (FMCW) radar. RFOOD employs both range-Doppler and micro range- Doppler images to enhance the detection accuracy. The architecture consists of a multi-encoder multi-decoder Body Part (BP) and Intermediate Linear Encoder-Decoder (ILED) components. This design allows the system to accurately classify a single individual's face as in-distribution (ID) while identifying all other faces as OOD. On our dataset collected with 60 GHz short-range FMCW radar, RFOOD achieves an Area Under the Receiver Operating Characteristic (AUROC) curve of 94.13 % and a False Positive Rate of 18.12% at a True Positive Rate of 95 % (FPR95). Additionally, RFOOD outperforms state-of-the-art OOD detection methods in common OOD detection metrics and operates in real-time.

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

url_pdf: https://ieeexplore.ieee.org/abstract/document/10903348
url_code: ''
url_dataset: 'https://syncandshare.lrz.de/getlink/fiVXWNxoYss8rRk2kZTUws/'
url_poster: ''
url_project: 'https://youtu.be/PI6bkqvjn28'
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
