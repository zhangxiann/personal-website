---
title: " Event-Stream Representation for Human Gaits Identification Using Deep Neural Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yanxiang Wang
- Xian Zhang
- Yiran Shen
- Bowen Du
- Guangrong Zhao
- Lizhen Cui
- Hongkai Wen


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Pattern Analysis and Machine Intelligence*
publication_short: In *TPAMI 2021*

abstract: Dynamic vision sensors (event cameras) have recently been introduced to solve a number of different vision tasks such as object recognition, activities recognition, tracking, etc. Compared with the traditional RGB sensors, the event cameras have many unique advantages such as ultra low resources consumption, high temporal resolution and much larger dynamic range. However, these cameras only produce noisy and asynchronous events of intensity changes, i.e., event-streams rather than frames, where conventional computer vision algorithms can’t be directly applied. In our opinion the key challenge for improving the performance of event cameras in vision tasks is finding the appropriate representations of the event-streams so that cutting-edge learning approaches can be applied to fully uncover the spatio-temporal information contained in the event-streams. In this paper, we focus on the event-based human gait identification task and investigate the possible representations of the event-streams when deep neural networks are applied as the classifier. We propose new event-based gait recognition approaches basing on two different representations of the event-stream, i.e., graph and image-like representations, and use Graph-based Convolutional Network (GCN) and Convolutional Neural Networks (CNN) respectively to recognize gait from the event-streams. The two approaches are termed as EV-Gait-3DGraph and EV-Gait-IMG. To evaluate the performance of the proposed approaches, we collect two event-based gait datasets, one from real-world experiments and the other by converting the publicly available RGB gait recognition benchmark CASIA-B. Extensive experiments show that EV-Gait-3DGraph achieves significantly higher recognition accuracy than other competing methods when sufficient training samples are available. However, EV-Gait-IMG converges more quickly than graph-based approaches while training and shows good accuracy with only few number of training samples (less than 10). So image-like presentation is preferable when the amount of training data is limited.
summary: This work focus on the human gait identification task using event camera, which has much higher temporal resolution and larger dynamic range. A large real-world gait recognition dataset recorded by event camera is released to the community to further facilitate the research on event-based gait recognition. To deal with the unique output of event cameras, a converting method is used to group events into frame forms, thus conventional CNN can be adopted on this representation. To better capture spatial temporal information from events, a new 3D-Graph method is proposed to represent events, and graph neural network is applied to learn to feature embeddding of graph. The proposed graph based approach outperforms CNN-based counterpart by 7.6%.
# summary: We propose new event-based gait recognition approaches basing on two different representations of the event-stream, i.e., graph and image-like representations, and use Graph-based Convolutional Network (GCN) and Convolutional Neural Networks (CNN) respectively to recognize gait from the event-streams.



tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9337225'
url_code: 'https://github.com/zhangxiann/TPAMI_Gait_Identification'
url_dataset: 'https://github.com/zhangxiann/TPAMI_Gait_Identification'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

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

<!-- {{% callout note %}} -->
<!--Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.-->
<!--{{% /callout %}}-->

<!--{{% callout note %}}-->
<!--Create your slides in Markdown - click the *Slides* button to check out the example.-->
<!--{{% /callout %}}-->

<!--Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).-->