---
title: "k-Hopped Link Prediction With Graph Embedding"
authors:
- admin
- Erich Baker
- Mary Lauren Benton
date: "2023-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 2023 World Congress in Computer Science, Computer Engineering, & Applied Computing*
publication_short: In *CSCE'23*

abstract: Graph embedding approaches aim to provide a low-dimensional latent representation of the graph with minimal reconstruction error. In addition, these approaches attempt to capture local and global topological neighborhood information and data distribution in the latent representation. The primary purpose of the graph's latent representation is simply implementing them into various straightforward machine learning models for graph prediction tasks such as link prediction, clustering, and visualization. Among these tasks, link prediction is a critical task in which researchers mainly analyze the performance of the embeddings on the information of adjacent nodes. Although many embedding techniques claim to capture the hopped neighborhood into the embedding, researchers need to pay more attention to analyzing the performance of the graph embeddings on hopped link prediction. Hopped link prediction demonstrates the performance of capturing a global view of the neighborhood. Our proposed framework develops $k$-hopped graph topological and feature information to analyze six widely recognized graph embeddings, ARGE, ARVGE, Node2vec, Attri2Vec, GraphSage, and GCN with $k$-hopped link prediction. We experiment with three graph datasets and show that $k$-hopped link prediction performance significantly increases for $1$-hopped graph information and continuously depletes after $1$-hop, demonstrating the importance of embedding performance analysis with $k$-hopped link prediction.

# Summary. An optional shortened abstract.
summary: The paper offers an algorithm to generate k-hopped topological and feature information in graphs. It highlights the need for in-depth analysis of graph embedding techniques' performance in capturing hopped neighborhood information for link prediction. The proposed framework evaluates six prominent graph embeddings (ARGE, ARVGE, Node2vec, Attri2Vec, GraphSage, and GCN) using $k$-hopped link prediction on diverse graph datasets. The results reveal a notable increase in link prediction performance for $1$-hopped graph information, followed by a continuous decline beyond $1$-hop. This underscores the significance of embedding performance assessment using $k$-hopped link prediction.

tags:
- 

# This is the variable that is needed to be set as false to make this page visible, or true to avoid it 
featured: false

links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/tonnidas/LinkPrediction_Comparison_Hop'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: true

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

<!-- # {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
