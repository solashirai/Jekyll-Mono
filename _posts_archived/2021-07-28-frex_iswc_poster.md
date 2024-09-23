---
title: ISWC Poster - Healthy Food Recommendation and Explanation Generation using a Semantically-Enabled Framework
categories: [personalization, knowledge_graph, recommendation_systems, context]
comments: true
---

My submission for the poster & demo track at the 2021 [International Semantic Web Conference](https://iswc2021.semanticweb.org/),
 titled "Healthy Food Recommendation and Explanation Generation using a Semantically-Enabled Framework", was accepted.

The content of this poster covers ongoing progress on the development of a framework, which I've named
FREx (the **F**ramework for **R**ecommendations with **Ex**planations). The goal of FREx is to enable
object oriented programming workflows to develop knowledge-driven recommendation systems, providing support
for converting RDF data into python objects for more streamlined development.

Another important feature of FREx is that it integrates information about "context" and "explanations" 
at each step of the way when producing recommendations. The recommendation system itself is
build as a pipeline, enabling flexible reuse and combinations of common components.
 
Compared to the content that was accepted at ISWC's poster session, my more recent work on
this project has started to further support automation of generating python 
[dataclasses](https://docs.python.org/3/library/dataclasses.html) based on class definitions from 
ontologies. The main repository for FREx is available [here](https://github.com/solashirai/FREx),
and additional documentation about some examples that I implemented for the ISWC poster session are
available [here](https://tetherless-world.github.io/FREx/).