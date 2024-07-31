---
title: "HAROOD: Human Activity Classification and Out-of-Distribution Detection with Short-Range FMCW Radar"

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

date: "2024-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In IEEE International Conference on Acoustics, Speech, and Signal Processing
publication_short: In ICASSP

abstract: We propose HAROOD as a short-range FMCW radar-based human activity classifier and out-of-distribution (OOD) detector. It aims to classify human sitting, standing, and walking activities and to detect any other moving or stationary object as OOD. We introduce a two-stage network. The first stage is trained with a novel loss function that includes intermediate reconstruction loss, intermediate contrastive loss, and triplet loss. The second stage uses the first stage's output as its input and is trained with cross-entropy loss. It creates a simple classifier that performs the activity classification. On our dataset collected by 60 GHz short-range FMCW radar, we achieve an average classification accuracy of 96.51%. Also, we achieve an average AUROC of 95.04% as an OOD detector. Additionally, our extensive evaluations demonstrate the superiority of HAROOD over the state-of-the-art OOD detection methods in terms of standard OOD detection metrics.

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

url_pdf: https://arxiv.org/pdf/2312.08894
url_code: ''
url_dataset: ''
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
