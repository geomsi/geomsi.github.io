---
title: "Improving Road Segmentation by Combining Satellite Images and LiDAR Data with a Feature-Wise Fusion Strategy"
authors:
- Ozan Ozturk
- admin
- Martin Kada
- Dursun Zafer Seker
author_notes:
- "Corresponding author"
date: "2023-05-17T00:00:00Z"
doi: "10.3390/app13106161"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-17T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Applied Sciences, 13*(10)"
publication_short: ""

abstract: Numerous deep learning techniques have been explored in pursuit of achieving precise road segmentation; nonetheless, this task continues to present a significant challenge. Exposing shadows and the obstruction of objects are the most important difficulties associated with road segmentation using optical image data alone. By incorporating additional data sources, such as LiDAR data, the accuracy of road segmentation can be improved in areas where optical images are insufficient to segment roads properly. The missing information in spectral data due to the object blockage and shadow effect can be compensated by the integration of 2D and 3D information. This study proposes a feature-wise fusion strategy of optical images and point clouds to enhance the road segmentation performance of a deep learning model. For this purpose, high-resolution satellite images and airborne LiDAR point cloud collected over Florida, USA, were used. Eigenvalue-based and geometric 3D property-based features were calculated based on the LiDAR data. These optical images and LiDAR-based features were used together to train, end-to-end, a deep residual U-Net architecture. In this strategy, the high-level features generated from optical images were concatenated with the LiDAR-based features before the final convolution layer. The consistency of the proposed strategy was evaluated using ResNet backbones with a different number of layers. According to the obtained results, the proposed fusion strategy improved the prediction capacity of the U-Net models with different ResNet backbones. Regardless of the backbone, all models showed enhancement in prediction statistics by 1% to 5%. The combination of optical images and LiDAR point cloud in the deep learning model has increased the prediction performance and provided the integrity of road geometry in woodland and shadowed areas.

# Summary. An optional shortened abstract.
summary: This study proposes a feature-wise fusion strategy of optical images and point clouds to enhance the road segmentation performance of a deep learning model.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

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
slides: ''
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
