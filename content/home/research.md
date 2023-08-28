+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 35  # Order that this section will appear.

title = "Research"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "gray"
  
  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "LightGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  # padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++


## Graph machine learning
  - Actively working on graph information influence analysis under supervision of [Dr. Erich Baker](https://www.linkedin.com/in/erich-baker-34bb544/) and [Dr. Mary Lauren Benton](https://onlinecs.baylor.edu/faculty/dr-mary-lauren-benton) in [Bioinformatics lab](https://www.notion.so/Benton-Lab-1503c1f6fde342ecbda5da25f1d48353).
  - Developing methodology for generating graph's topological embedding disregarding node feature information.
  - Predicting p-values in Alzheimer's disease gene graphs employing topological embedding.
  - Detecting gene and genesets relations for multiple disease from GeneWeaver. 
  - Anlyzing edge feature and k-hopped topological and feature information for node attribute prediction with graph embedding.
  - Published an articles and submitted two more (pending decision). 

## Sign language similarity analysis
  - Supervised by [Dr. Pablo Rivas](https://onlinecs.baylor.edu/faculty/dr-pablo-rivas) and collaborated with [Dr. Gissella Bejarano](https://www.marist.edu/computer-science-math/faculty/gissella-bejarano) in [Baylor AI lab](https://baylor.ai/).
  - Automated Sign Language (SL) similarity analysis with a 3D multi-stage convolutional neural network method. 
  - Verified method's credibility comparing with SL similarity scores from Lexicostatistics (considering four features: Handshape, Orientation, Movement, Location) method. 
  - Employed annotations analysis with segmentation approach for automation. 
  - Published an article. 

## Quantum Machine Learning
  - Supervised by [Dr. Pablo Rivas](https://onlinecs.baylor.edu/faculty/dr-pablo-rivas) and [Dr. Javier Orduz](https://earlham.edu/faculty-staff/javier-orduz/).
  - Employed quantum classifiers with quantum kernals for analyzing classification performance compared to traditional classifiers. 
  - Employed quantum adversarial autoencoder for identigying DDoS attacks.
  - Published an article and submitted another article (pending decision). 

## AI Ethics 
  - Supervised by [Dr. Pablo Rivas](https://onlinecs.baylor.edu/faculty/dr-pablo-rivas) in [Baylor AI lab](https://baylor.ai/).
  - Proposed classification of fairness issues and generalized the methods to solve them and their challanges according to the issue classes.
  - Implemented systematic mapping study approach to analyze biases and the fairness of AI, ML methods
  - Developed search queries (for IEEE, ACM, SpringerLink, Google Scholar, Science Directory) and research questions.
  - Published a Book Chapter, submitted an article (pending decision) and collaborated in a NSF funding proposal write-up.

<!-- #### Graph information influence
Graphs from various fields offer various information such as topological information, node contents, edge features, node properties indicating data flow within each nodes (like degre centrality, edge betweenness etc.). As graph data provides these information in unstructured manner and also in enormous size, data wrangling methods to prepare these information for downstream machine learning techniques (such as SVM classification, random forest regression etc.) become troublesome and time-consuming but essential. We analyze the influence of these various graph information for node attribute prediction and generalize their performance across various datasets (such as, transactional datasets, social datasets, citation datasets etc.).

#### Graph's topological embedding
Due to scarce data in real-world situations, such as unavailability of node contents in Alzheimer's disease gene dataset, requires development of embedding independent of node features. To facilitate with embedding techniques in scarce inforation, we develop a methodology to manipulate graph embedding techniques that are developed from node content and topology, to produce credible performance from manipulating edge information individually.

#### k-hopped feature and topological information influence
We develop an algorithm to generate k-hopped feature and topological information given a graph and analyze the influence of these inforation in graph embedding generation. 

#### Real-world 
We are currently working on datasets from Alzheimer's disease genes and GeneWeaver datasets. P-value prediction from diseased genes is a real-world problem and we analyze and experiment with Alzheimer's disease dataset for P-value prediction. As Alzheimer's disease dataset lack node feature, we develop topological embedding representation from Azheimer's gene's ontological inter-relations, disregarding node contents and verify our method's efficacy. Moreoevr, GeneWeaver dataset lacks node contents in similar fashion and we employ the topological embedding for clustering the genes and genesets for certain diseases. 

- ## Sign language similarity analysis
Machine learning methods for sign language similarity measurement, where we have developed a mathod for measuring similarities between sign languages instead of Lexicostatistics. Previously, linguists used Lexicostatistics that referes to a manual process of measuring distances between isolated signs considering four features: Handshape, Orientation, Movement, Location. Segmentation based machine learning model for comparing between their annotations is a more automatic approach. 
- ## Quantum Machine Learning
Machine learning methods for sign language similarity measurement, where we have developed a mathod for measuring similarities between sign languages instead of Lexicostatistics. Previously, linguists used Lexicostatistics that referes to a manual process of measuring distances between isolated signs considering four features: Handshape, Orientation, Movement, Location. Segmentation based machine learning model for comparing between their annotations is a more automatic approach. 
- ## AI Ethics 
Implementation of AI, ML in real-world application, such as in Risk Assessment Instruments (RAIs) are questioned with fairness issues of these methods. We adopted systematic method to analyze biases and the fairness of these methods by proposing search queries (for databases like, IEEE, ACM etc.) and research questions, where we proposed classification of fairness issues and generalized the methods to solve them and their challanges according to the classification. -->
<!-- - #### 3D model generation from 2D information
Undergraduate thesis on, [3D-Model-Generation](https://en.wikipedia.org/wiki/3D_modeling) of Real-Objects Using Depth and Color Information, where we designed an algorithm to generate a 3D model from 2D pictures after abstracting input RGB and depth data and implemented the algorithm to generate a 3D view to represent clear distancing of multiple objects from a 2D picture. -->