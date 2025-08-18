---
title: "Vector Database Watermarking"
authors:
- Zhiwen Ren
- admin
- Wei Fan
- Jing Qiu
- Weiming Zhang
- Nenghai Yu
date: "2025-01-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Submitted, The Thirty-Ninth Annual Conference on Neural Information Processing Systems"
publication_short: "Submitted, NeurIPS 2025"

abstract: "Vector databases support machine learning tasks using Approximate Nearest Neighbour (ANN) query functionality, making them highly valuable digital assets. However, they also face security threats like unauthorized replication. By embedding stealth information, watermarking technology can be used for ownership authentication. This paper introduces a watermarking scheme specifically designed for vector databases. The scheme consists of four steps: generating identifiers, grouping, cryptographic mapping, and modification. Since watermark embedding requires modification of certain vectors, it may negatively affect the ANN query results. Further investigation reveals that in the widely used Hierarchical Navigable Small World (HNSW) indexing structure for vector databases, heuristic edge selection and pruning strategies result in some vectors having fewer edges or even none at all. These vectors exhibit significantly lower query frequencies than others, which means that modifying these vectors incurs less impact on query results. Based on this observation, we propose the Transparent Vector Priority (TVP) watermarking scheme, which prioritizes embedding the watermark in these low-query-frequency “transparent” vectors to minimize the impact of watermark embedding on query results. Experimental results show that compared to the current most effective and relevant watermarking schemes, the TVP scheme can significantly reduce the number of missed and false queries by approximately 75%."

# Summary. An optional shortened abstract.
summary: "Vector databases support machine learning tasks using Approximate Nearest Neighbour (ANN) query functionality, making them highly valuable digital assets. However, they also face security threats like unauthorized replication. By embedding stealth information, watermarking technology can be used for ownership authentication. This paper introduces a watermarking scheme specifically designed for vector databases. The scheme consists of four steps: generating identifiers, grouping, cryptographic mapping, and modification. Since watermark embedding requires modification of certain vectors, it may negatively affect the ANN query results. Further investigation reveals that in the widely used Hierarchical Navigable Small World (HNSW) indexing structure for vector databases, heuristic edge selection and pruning strategies result in some vectors having fewer edges or even none at all. These vectors exhibit significantly lower query frequencies than others, which means that modifying these vectors incurs less impact on query results. Based on this observation, we propose the Transparent Vector Priority (TVP) watermarking scheme, which prioritizes embedding the watermark in these low-query-frequency “transparent” vectors to minimize the impact of watermark embedding on query results. Experimental results show that compared to the current most effective and relevant watermarking schemes, the TVP scheme can significantly reduce the number of missed and false queries by approximately 75%."

tags:
- Watermarking

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
slides: example
---
<div style="display:none">
This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
</div>
