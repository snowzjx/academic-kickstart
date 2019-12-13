---
title: "Enabling ECN for Datacenter Networks with RTT Variations"
authors:
- admin
- Wei BAI
- Kai CHEN
date: "2019-12-09T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *CoNEXT 2019*
publication_short: In *CoNEXT 2019*

abstract:
ECN has been widely employed in production datacenters to deliver high throughput low latency communications. Despite being successful, prior ECN-based transports have an important drawback\: they adopt a fixed RTT value in calculating instantaneous ECN marking threshold while overlooking the RTT variations in practice. 

In this paper, we reveal that the current practice of using a fixed high-percentile RTT for ECN threshold calculation can lead to persistent queue buildups, significantly increasing packet latency. On the other hand, directly adopting lower percentile RTTs results in throughput degradation. To handle the problem, we introduce ECN$^\\sharp$\\xspac, a simple yet effective solution to enable ECN for RTT variations. At its heart, \sys inherits the current instantaneous ECN marking (based on a high-percentile RTT) to achieve high throughput and burst tolerance, while further marking packets (conservatively) upon detecting long-term queue buildups to eliminate unnecessary queueing delay without degrading throughput. We implement ECN$^\\sharp$\\xspac on a Barefoot Tofino switch and evaluate it through extensive testbed experiments and large-scale simulations. Our evaluation confirms that ECN$^\\sharp$\\xspac can effectively reduce latency without hurting throughput. For example, compared to the current practice, ECN$^\\sharp$\\xspac achieves up to $23.4\\%$ ($31.2\\%$) lower average (99th percentile) flow completion time (FCT) for short flows while delivering similar FCT for large flows under production workloads.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- DCN
- ECN
- P4
featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: CoNEXT19.pdf
url_code: 'https://github.com/snowzjx/ns3-ecn-sharp'
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

