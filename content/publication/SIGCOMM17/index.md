---
title: "Resilient datacenter load balancing in the wilds"
authors:
- Hong ZHANG
- admin
- Wei BAI
- Kai CHEN
- Chowdhury Mosharaf
date: "2017-08-20T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *SIGCOMM 2017*
publication_short: In *SIGCOMM 2017*

abstract: 'Production datacenters operate under various uncertainties such as traffic dynamics, topology asymmetry, and failures. Therefore, datacenter load balancing schemes must be resilient to these uncertainties; i.e., they should accurately sense path conditions and timely react to mitigate the fallouts. Despite significant efforts, prior solutions have important drawbacks. On the one hand, solutions such as Presto and DRB are oblivious to path conditions and blindly reroute at fixed granularity. On the other hand, solutions such as CONGA and CLOVE can sense congestion, but they can only reroute when flowlets emerge; thus, they cannot always react timely to uncertainties. To make things worse, these solutions fail to detect or handle failures such as blackholes and random packet drops, which greatly degrades their performance.
<br/>
In this paper, we introduce Hermes, a datacenter load balancer that is resilient to the aforementioned uncertainties. At its heart, Hermes leverages comprehensive sensing to detect path conditions including failures unattended before, and it reacts using timely yet cautious rerouting. Hermes is a practical edge-based solution with no switch modification. We have implemented Hermes with commodity switches and evaluated it through both testbed experiments and large-scale simulations. Our results show that Hermes achieves comparable performance to CONGA and Presto in normal cases, and well handles uncertainties: under asymmetries, Hermes achieves up to $10\\%$ and $20\\%$ better flow completion time (FCT) than CONGA and CLOVE; under switch failures, it outperforms all other schemes by over $32\\%$.
'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- DCN
- Load Balance
featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: http://www.cse.ust.hk/~kaichen/papers/hermes-sigcomm17.pdf
url_code: 'https://github.com/snowzjx/ns3-load-balance'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
url_slides: 'https://conferences.sigcomm.org/sigcomm/2017/files/program/ts-6-3-resilient-load-balancing.pptx'
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

