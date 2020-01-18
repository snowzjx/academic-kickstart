---
title: "Rethinking Transport Layer Design for Distributed Machine Learning"
authors:
- Jiacheng XIA
- Gaoxiong ZENG
- admin
- Weiyan WANG
- Wei BAI
- Juncheng JIANG
- Kai CHEN
date: "2019-08-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *APNet 2019*
publication_short: In *APNet 2019*

abstract: 'Motivated by the increasing scale of data, we see a growing need of high performance distributed machine learning systems. Many research works are being proposed to improve distributed machine learning performance.
</br>
In this paper, we call upon this community to rethink transport layer solutions for distributed machine learning due to their stringent network requirements and special algorithmic properties. Distributed machine learning jobs generate bursty traffic when synchronizing parameters and a long tail flow can significantly slow down the complete training process. Meanwhile, in contrast to other distributed system applications, we find that machine learning algorithms are bounded-loss tolerant: randomized network data losses below a certain fraction (typically %10\\%-35\\%) will do little harm to the end to end job performance. Motivated by this observation, we highlight new opportunities to design bounded-loss tolerant transport to optimize the performance of distributed machine learning. By intentionally ignoring some packet losses, we can avoid unnecessary loss retransmissions, thus reducing the tail flow completion time. Following this principle, our preliminary results show that a simplified protocol can give $1.1-2.2\\times$ speedup on different distributed machine learning tasks.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- DCN
- Machine Learning
featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: APNet19.pdf
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

