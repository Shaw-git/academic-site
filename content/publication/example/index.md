---
title: "Accurate Head Pose Estimation Using Image Rectification and Lightweight Convolutional Neural Network"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xiao Li
- Dong Zhang
- Ming Li
- Dah-Jye Lee

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-12-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*

Abstract — Head pose estimation is an important step for many human-computer interaction applications such as face detection, facial recognition, and facial expression classification. Accurate head pose estimation benefits these applications that require face image as the input. Most head pose estimation methods suffer from perspective distortion because the users do not always align their face perfectly with the camera. This paper presents a new approach that uses image rectification to reduce the negative effect of perspective distortion and a lightweight convolutional neural network to obtain highly accurate head pose estimation. The proposed method calculates the angle between the camera optical axis and the projection vector of the face center. The face image is rectified using this estimated angle through perspective transformation. A lightweight network with the size of only 0.88 MB is designed to take the rectified face image as the input to perform head pose estimation. The output of the network, the head pose estimation of the rectified face image, is transformed back to the camera coordinate system as the final head pose estimation. Experiments on public benchmark datasets show that the proposed image rectification and the newly designed lightweight network remarkably improve the accuracy of head pose estimation. Compared with state-of-the-art methods, our approach achieves both higher accuracy and faster processing speed.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
