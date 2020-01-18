---
title: "Bridging the Edge-cloud Barrier for Real-time Advanced Vision Analytics"
authors:
- Yiding WANG
- Weiyan WANG
- admin
- Juncheng JIANG
- Kai CHEN
date: "2019-07-08T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *HotCloud 2019*
publication_short: In *HotCloud 2019*

abstract: 'Advanced vision analytics plays a key role in a plethora of real-world applications. Unfortunately, many of these applications fail to leverage the abundant compute resource in cloud services, because they require high computing resources {\\em and} high-quality video input, but the (wireless) network connections between visual sensors (cameras) and the cloud/edge servers do not always provide sufficient and stable bandwidth to stream high-fidelity video data in real time.
</br>
This paper presents CloudSeg, an edge-to-cloud framework for advanced vision analytics that co-designs the cloud-side inference with real-time video streaming, to achieve both low latency and high inference accuracy. The core idea is to send the video stream in low resolution, but recover the high-resolution frames from the low-resolution stream via a {\\em super-resolution} procedure tailored for the actual analytics tasks. In essence, CloudSeg trades additional cloud-side computation (super-resolution) for significantly reduced network bandwidth. Our initial evaluation shows that compared to previous work, CloudSeg can reduce bandwidth consumption by $\\sim$6.8$\\times$ with negligible drop in accuracy.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Machine Learning
- Video Streaming
featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: HotCloud19.pdf
# url_code: 'https://github.com/snowzjx/ns3-ecn-sharp'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

<!-- {{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}} -->

<!-- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

