---
title: "EV-Perturb: A Differential-private Events Perturbation Approach for Classification Task Using Dynamic Vision Sensor"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xian Zhang
- Yiran Shen
- Qing Yang
- Hongkai Wen


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Association for the Advancement of Artificial Intelligence*
publication_short: In *AAAI 2022 (under second round review)*

abstract: The dynamic vision sensors or event-cameras are bio-inspired vision platforms with independent and asynchronous pixels. Its unique design enables a number of advantages over traditional RGB cameras including high temporal resolution for capturing high speed motion without blur and high dynamic range for sensing under challenging lighting conditions. As the outputs of the event-cameras are discrete and asynchronous events, termed as event-stream, rather than high-quality video frames, they are regarded as low privacy-intrusive. However, the research on reconstruction from events has revealed that the event-streams can be converted to high quality video frames by sophisticated reconstruction algorithms, so that the claim on privacy-preserving does not hold anymore. In this paper, we focus on the privacy issue of event-streams used in EV-based classification tasks and propose, EV-Perturb, an event-stream perturbation mechanism to protect event-streams from reconstruction attacks. EV-Perturb flips polarities of events in a random manner and the theoretical proof shows it provides differential-private guarantee on the perturbed event-streams. We also evaluate the utility (classification accuracy) and privacy (video reconstruction error) of EV-Perturb on EV-based classification tasks with multiple publicly available datasets using deep learning models. Both the quantitative and qualitative results show that EV-Perturb is able to deteriorate the quality of the reconstructed frames effectively, while the machine learning models can still achieve comparable classification accuracy with heavily perturbed event-streams.
summary: The dynamic vision sensors or event-cameras are bio-inspired vision platforms with independent and asynchronous pixels. Its unique design enables a number of advantages over traditional RGB cameras including high temporal resolution for capturing high speed motion without blur and high dynamic range for sensing under challenging lighting conditions. As the outputs of the event-cameras are discrete and asynchronous events, termed as event-stream, rather than high-quality video frames, they are regarded as low privacy-intrusive. However, the research on reconstruction from events has revealed that the event-streams can be converted to high quality video frames by sophisticated reconstruction algorithms, so that the claim on privacy-preserving does not hold anymore. In this paper, we focus on the privacy issue of event-streams used in EV-based classification tasks and propose, EV-Perturb, an event-stream perturbation mechanism to protect event-streams from reconstruction attacks. EV-Perturb flips polarities of events in a random manner and the theoretical proof shows it provides differential-private guarantee on the perturbed event-streams. We also evaluate the utility (classification accuracy) and privacy (video reconstruction error) of EV-Perturb on EV-based classification tasks with multiple publicly available datasets using deep learning models. Both the quantitative and qualitative results show that EV-Perturb is able to deteriorate the quality of the reconstructed frames effectively, while the machine learning models can still achieve comparable classification accuracy with heavily perturbed event-streams.



tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9337225'
#url_code: 'https://github.com/zhangxiann/TPAMI_Gait_Identification'
#url_dataset: 'https://github.com/zhangxiann/TPAMI_Gait_Identification'
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