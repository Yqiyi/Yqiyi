---
title: "Vector Database Watermarking"
authors:
- Zhiwen Ren
- admin
- Zehua Ma
- Kejiang Chen
- Wei Fan
- Weiming Zhang
- Nenghai Yu
date: "2024-12-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "In Preparation, Proceedings of the ACM SIGSAC Conference on Computer and Communications Security"
publication_short: "In Preparation, ACM CCS 2025"

abstract: High-dimensional vector data can represent complex objects such as words, images, and videos, essential to machine learning (ML), natural language processing (NLP), and other AI tasks. Vector databases store vector data and serve key functions in AI and ML applications, such as retrieval-augmented generation (RAG), recommendation engines, and vector search. With the rapid increase in relevant AI applications, the use of vector databases has become more frequent, and the value of vector data has also increased. Thus, the issue of data security and copyright protection of vector databases is very important. In operation, the approximate nearest neighbor (ANN) search is commonly adopted to quickly and accurately retrieve and deliver data neighboring the queried vector in one vector database. In various ANN algorithms, the Hierarchical Navigable Small World (HNSW) has become one of the most commonly used due to its excellent performance. In this paper, we propose the Transparent Vector Prioritization watermarking method (\textbf{TVP}), leveraging the characteristics of HNSW to minimize the impact of watermark embedding on vector database queries. Specifically, we define and model the watermarking impact on vector database query and find highly transparent vectors, which have fewer edges in HNSW and are queried much less frequently than others. Then, we analyze the potential causes behind these vectors, design the corresponding detection algorithms, and embed watermarks on them. Experimental results show that the proposed method has fewer query errors, reducing the number of false queries and missed queries by about 70% compared to applying existing database watermarking methods directly to vector databases, and maintains strong robustness.

# Summary. An optional shortened abstract.
summary: High-dimensional vector data can represent complex objects such as words, images, and videos, essential to machine learning (ML), natural language processing (NLP), and other AI tasks. Vector databases store vector data and serve key functions in AI and ML applications, such as retrieval-augmented generation (RAG), recommendation engines, and vector search. With the rapid increase in relevant AI applications, the use of vector databases has become more frequent, and the value of vector data has also increased. Thus, the issue of data security and copyright protection of vector databases is very important. In operation, the approximate nearest neighbor (ANN) search is commonly adopted to quickly and accurately retrieve and deliver data neighboring the queried vector in one vector database. In various ANN algorithms, the Hierarchical Navigable Small World (HNSW) has become one of the most commonly used due to its excellent performance. In this paper, we propose the Transparent Vector Prioritization watermarking method (\textbf{TVP}), leveraging the characteristics of HNSW to minimize the impact of watermark embedding on vector database queries. Specifically, we define and model the watermarking impact on vector database query and find highly transparent vectors, which have fewer edges in HNSW and are queried much less frequently than others. Then, we analyze the potential causes behind these vectors, design the corresponding detection algorithms, and embed watermarks on them. Experimental results show that the proposed method has fewer query errors, reducing the number of false queries and missed queries by about 70% compared to applying existing database watermarking methods directly to vector databases, and maintains strong robustness.

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
