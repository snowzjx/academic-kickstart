---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "NS3 DCN"
summary: "NS3 DCN support simulating data center networking facilities, including DCTCP, Conga, Heremes..."
authors: []
tags: []
categories: []
date: 2019-12-13T14:01:48+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Center"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
We have maintained several different repos for this simulator:

1. Github repo maintained by iSINGLab group: [link](https://github.com/HKUST-SING/ns3-dcn)

2. Github repo for my CoNEXT paper: [link](https://github.com/snowzjx/ns3-ecn-sharp)

3. Github repo for Hong's SIGCOMM paper: [link](https://github.com/snowzjx/ns3-load-balance)

This simulator has been used in several top-tier conference papers:

1. [Enabling ECN for Datacenter Networks with RTT Variations (CoNEXT 19)](https://dl.acm.org/authorize.cfm?key=N690741)

2. [Resilient Datacenter Load Balancing in the Wild (SIGCOMM 17)](http://www.cse.ust.hk/~kaichen/papers/hermes-sigcomm17.pdf)

3. [PURR: a primitive for reconfigurable fast reroute: hope for the best and program for the worst (CoNEXT 19)](https://dl.acm.org/authorize?N690721)

Please cite either of the following papers if you are using our simulator. Thanks! :P

```
@inproceedings{zhang2017resilient,
  title={Resilient datacenter load balancing in the wild},
  author={Zhang, Hong and Zhang, Junxue and Bai, Wei and Chen, Kai and Chowdhury, Mosharaf},
  booktitle={Proceedings of the Conference of the ACM Special Interest Group on Data Communication},
  pages={253--266},
  year={2017},
  organization={ACM}
}
```

```
@inproceedings{zhang2019enabling,
  title={Enabling ECN for datacenter networks with RTT variations},
  author={Zhang, Junxue and Bai, Wei and Chen, Kai},
  booktitle={Proceedings of the 15th International Conference on Emerging Networking Experiments And Technologies},
  pages={233--245},
  year={2019},
  organization={ACM}
}
```

