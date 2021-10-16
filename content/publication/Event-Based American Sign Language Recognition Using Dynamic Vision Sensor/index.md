---
title: " Event-Based American Sign Language Recognition Using Dynamic Vision Sensor"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yong Wang
- Xian Zhang
- Yanxiang Wang
- Hongbin Wang
- Chanying Huang
- Yiran Shen


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Wireless Algorithms, Systems, and Applications*
publication_short: In *WASA 2021*

abstract: American Sign language (ASL) is one of the most effective communication tools for people with hearing difficulties. However, most of people do not understand ASL. To bridge this gap, we propose EVASL, an automatic ASL interpretation system based on dynamic vision sensor (DVS). Compared to the traditional RGB-based approach, DVS consumes significantly less resources (energy, computation, bandwidth) and it outputs the moving objects only without the need of background subtraction due to its event-based nature. At last, because of its wide dynamic response range, it enables the EV-ASL to work under a variety of lighting conditions. EV-ASL proposes novel representation of event streams and facilitates deep convolutional neural network for sign recognition. In order to evaluate the performance of EV-ASL, we recruited 10 participants and collected 11,200 samples from 56 different ASL words. The evaluation shows that EV-ASL achieves a recognition accuracy of 93.25%.
# Summary: This work focus on the human gait identification task using event camera, which has much higher temporal resolution and larger dynamic range. A large real-world gait recognition dataset recorded by event camera is released to the community to further facilitate the research on event-based gait recognition. To deal with the unique output of event cameras, a converting method is used to group events into frame forms, thus conventional CNN can be adopted on this representation. To better capture spatial temporal information from events, a new 3D-Graph method is proposed to represent events, and graph neural network is applied to learn to feature embeddding of graph. The proposed graph based approach outperforms CNN-based counterpart by 7.6%.
summary: A dataset of sign language words consisted of 11200 samples using DVS sensor is published. In order to further utilize both the spatial and temporal distribution of the events, a new image-like representation of event stream is proposed which consider neighborhood events for frame generating. The proposed frame representation achieves a recognition accuracy of 93.25%.



tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-86137-7_1'
#url_code: 'https://github.com/zhangxiann/TPAMI_Gait_Identification'
#url_dataset: 'https://github.com/zhangxiann/TPAMI_Gait_Identification'
url_poster: ''
url_project: ''
url_slides: 'https://image.zhangxiann.com/WASA_PAPER16.pptx'
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