---
title: "Soil Moisture Prediction from Remote Sensing Images Coupled with Climate, Soil Texture and Topography via Deep Learning"
authors:
- Mehmet Furkan Celik
- admin
- Onur Yuzugullu
- Noura Fajraoui
- Esra Erten
author_notes:
- "Corresponding author"
date: "2022-10-05T00:00:00Z"
doi: "10.3390/rs14215584"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-05T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Remote Sensing, 14*(21)"
publication_short: ""

abstract: Soil moisture (SM) is an important biophysical parameter by which to evaluate water resource potential, especially for agricultural activities under the pressure of global warming. The recent advancements in different types of satellite imagery coupled with deep learning-based frameworks have opened the door for large-scale SM estimation. In this research, high spatial resolution Sentinel-1 (S1) backscatter data and high temporal resolution soil moisture active passive (SMAP) SM data were combined to create short-term SM predictions that can accommodate agricultural activities in the field scale. We created a deep learning model to forecast the daily SM values by using time series of climate and radar satellite data along with the soil type and topographic data. The model was trained with static and dynamic features that influence SM retrieval. Although the topography and soil texture data were taken as stationary, SMAP SM data and Sentinel-1 (S1) backscatter coefficients, including their ratios, and climate data were fed to the model as dynamic features. As a target data to train the model, we used in situ measurements acquired from the International Soil Moisture Network (ISMN). We employed a deep learning framework based on long short-term memory (LSTM) architecture with two hidden layers that have 32 unit sizes and a fully connected layer. The accuracy of the optimized LSTM model was found to be effective for SM prediction with the coefficient of determination (R2) of 0.87, root mean square error (RMSE) of 0.046, unbiased root mean square error (ubRMSE) of 0.045, and mean absolute error (MAE) of 0.033. The model’s performance was also evaluated concerning above-ground biomass, land cover classes, soil texture variations, and climate classes. The model prediction ability was lower in areas with high normalized difference vegetation index (NDVI) values. Moreover, the model can better predict in dry climate areas, such as arid and semi-arid climates, where precipitation is relatively low. The daily prediction of SM values based on microwave remote sensing data and geophysical features was successfully achieved by using an LSTM framework to assist various studies, such as hydrology and agriculture.

# Summary. An optional shortened abstract.
summary: In this research, high spatial resolution Sentinel-1 (S1) backscatter data and high temporal resolution soil moisture active passive (SMAP) SM data were combined to create short-term SM predictions that can accommodate agricultural activities in the field scale.

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
