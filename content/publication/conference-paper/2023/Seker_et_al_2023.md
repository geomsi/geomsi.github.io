---
title: 'Feature-wise Fusion of Optical Satellite Images and LiDAR Data: Pathway to Enhance Road Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dursun Zafer Seker
  - Ozan Ozturk
  - admin
  - Martin Kada
# Author notes (optional)
author_notes:
  - 'Corresponding author'

date: '2023-12-10T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-10T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *American Geophysics Union Annual Meeting 2023*
publication_short: In *AGU Annual Meeting 2023*

abstract: Road segmentation based on optical images is still challenging due to the caused by occlusion, object blockage, and shadows. To address these challenges, integrating LiDAR data, which provides valuable geometric relationships for extracting road information, comes to the forefront as an optimal solution. The fusion of 2D and 3D information from optical images and LiDAR provide potential advantages for road segmentation, especially in cases where optical satellite images lack comprehensive road information. In this study, we present a novel approach to enhance the road segmentation performance of a deep learning model. The method involves the fusion of high-resolution optical satellite images and LiDAR point clouds through a feature-wise strategy. The satellite images were generated via Static Map API of Google Maps platform using python-based tool. As the LiDAR point cloud, airborne LiDAR data collected by U.S. Geological Survey over Florida, USA, were used. We calculated eigenvalue-based and geometric 3D property-based features from the LiDAR data and combined them with the optical satellite images to train an end-to-end deep residual U-Net architecture. The combined feature set was used for training the deep residual U-Net model with different sizes of ResNet backbones, hence the consistency of the proposed approach was tested in varying architectural structure of U-Net model. The proposed strategy involves concatenating the high-level features generated from the optical images through U-Net architecture together with the LiDAR-based features before the final convolution layer of the model. The results demonstrated that the fusion strategy significantly improved the prediction capacity of the U-Net models regardless of which ResNet backbone was adopted. By combining optical images and LiDAR point cloud data, the deep learning model achieved improved prediction performance and ensured the accurate representation of road geometry in areas where the road pixels are blocked by tree cover and shadows of the objects in scenery. Obtained results demonstrate the potential of the fusion strategy and the benefit of combining data from various sources in developing more reliable road segmentation models that can accurately detect road pixels even in challenging areas.


# Summary. An optional shortened abstract.
summary: ''

tags: ['Road Segmentation','Deep learning','LiDAR']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
