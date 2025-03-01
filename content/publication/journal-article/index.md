---
title: "π-PrimeNovo: an accurate and efficient non-autoregressive deep learning model for de novo peptide sequencing"
authors:
- admin
- Tianze Ling
- Zhi Jin
- Sheng Xu
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
date: "2015-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Nature Communications 16, No. 267"
publication_short: "NC"

abstract: Peptide sequencing via tandem mass spectrometry (MS/MS) is essential in proteomics. Unlike traditional database searches, deep learning excels at de novo peptide sequencing, even for peptides missing from existing databases. Current deep learning models often rely on autoregressive generation, which suffers from error accumulation and slow inference speeds. In this work, we introduce π-PrimeNovo, a non-autoregressive Transformer-based model for peptide sequencing. With our architecture design and a CUDA-enhanced decoding module for precise mass control, π-PrimeNovo achieves significantly higher accuracy and up to 89x faster inference than state-of-the-art methods, making it ideal for large-scale applications like metaproteomics. Additionally, it excels in phosphopeptide mining and detecting low-abundance post-translational modifications (PTMs), marking a substantial advance in peptide sequencing with broad potential in biological research.

# Summary. An optional shortened abstract.
#summary: A fast and accurate 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.nature.com/articles/s41467-024-55021-3
url_code: 'https://github.com/PHOENIXcenter/pi-PrimeNovo'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
