---
title: "HOOD: Real-Time Human Presence and
Out-of-Distribution Detection Using FMCW Radar"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Muhammet Sami Yavuz
  - Eckehard Steinbach

# Author notes (optional)
author_notes: ""
  #- 'Equal contribution'
  #- 'Equal contribution'
date: "2023-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*arXiv*"
publication_short: ""

abstract: Detecting human presence indoors with millimeter-wave frequency-modulated continuous-wave (FMCW) radar faces challenges from both moving and stationary clutter. This work proposes a robust and real-time capable human presence and out-of-distribution (OOD) detection method using 60 GHz short-range FMCW radar. HOOD solves the human presence and OOD detection problems simultaneously in a single pipeline. Our solution relies on a reconstruction-based architecture and works with radar macro and micro range-Doppler images (RDIs). HOOD aims to accurately detect the presence of humans in the presence or absence of moving and stationary disturbers. Since HOOD is also an OOD detector, it aims to detect moving or stationary clutters as OOD in humans' absence and predicts the current scene's output as “no presence." HOOD performs well in diverse scenarios, demonstrating its effectiveness across different human activities and situations. On our dataset collected with a 60 GHz short-range FMCW radar, we achieve an average AUROC of 94.36%. Additionally, our extensive evaluations and experiments demonstrate that HOOD outperforms state-of-the-art (SOTA) OOD detection methods in terms of common OOD detection metrics. Importantly, HOOD also perfectly fits on Raspberry Pi 3B+ with an ARM Cortex-A53 CPU, which showcases its versatility across different hardware environments. 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2308.02396
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://muskahya.github.io/HOOD/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
