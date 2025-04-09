---
title: "A New Weight Function for Highest Random Weight Scheme and its Efficient Lookup Implementations"
authors:
- Muhammad Waqas
- Sian-Jheng Lin
- Bin Liu
- admin
- Adnan Fazil
date: "2025-03-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-22T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Submitted, IEEE Transactions on Network and Service Management"
publication_short: "Submitted, IEEE TNSM"

abstract: "Cloud infrastructures have become increasingly popular among distributed applications in the modern era due to their efficient failure recovery, global reach, mobility, and service integration. Highest Random Weight (HRW) is one of the Consistent Hashing (CH) schemes that offers indefinite scalability while maintaining consistency, lookup, minimal dispersal, and load balancing for cloud environments. However, current versions of HRW and other CH algorithms offer high memory costs, exchange excessive messages for TCP connections, and sacrifice performance when considering large scalable distributed systems due to extensive rehashing or O(w) comparisons among $w$ working nodes. This paper suggests a weight function for the Highest Random Weight (HRW) scheme, termed as Multiplication Modulo-based Highest Random Weight (MM-HRW) scheme. In the MM-HRW scheme, the entire key range can be divided into several nonoverlapping ranges, and each range corresponds to a working node. By applying binary search on the ranges, we can find out the working node of a key with O(log (w)) comparisons. Additionally, we present the corresponding algorithms, implementations, and mathematical validation to support the experimental findings. The results demonstrate that MM-HRW consistently achieves an optimal memory footprint, validating its scalability across various scenarios. Additionally, by considering large cluster size, MM-HRW scheme achieves the highest lookup rate while maintaining O(log (w)) comparisons across all scenarios."

# Summary. An optional shortened abstract.
summary: "Cloud infrastructures have become increasingly popular among distributed applications in the modern era due to their efficient failure recovery, global reach, mobility, and service integration. Highest Random Weight (HRW) is one of the Consistent Hashing (CH) schemes that offers indefinite scalability while maintaining consistency, lookup, minimal dispersal, and load balancing for cloud environments. However, current versions of HRW and other CH algorithms offer high memory costs, exchange excessive messages for TCP connections, and sacrifice performance when considering large scalable distributed systems due to extensive rehashing or O(w) comparisons among $w$ working nodes. This paper suggests a weight function for the Highest Random Weight (HRW) scheme, termed as Multiplication Modulo-based Highest Random Weight (MM-HRW) scheme. In the MM-HRW scheme, the entire key range can be divided into several nonoverlapping ranges, and each range corresponds to a working node. By applying binary search on the ranges, we can find out the working node of a key with O(log (w)) comparisons. Additionally, we present the corresponding algorithms, implementations, and mathematical validation to support the experimental findings. The results demonstrate that MM-HRW consistently achieves an optimal memory footprint, validating its scalability across various scenarios. Additionally, by considering large cluster size, MM-HRW scheme achieves the highest lookup rate while maintaining O(log (w)) comparisons across all scenarios."

tags:
- Distributed Algorithms

featured: false

links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
url_project: ''
url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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
<div style="display:none">
This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
</div>
