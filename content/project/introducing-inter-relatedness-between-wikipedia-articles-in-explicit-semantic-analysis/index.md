---
title: Introducing Inter-Relatedness between Wikipedia Articles in Explicit
  Semantic Analysis
date: 2022-08-14T11:12:49.521Z
summary: "Course: Natural Language Processing​ | ​Advisor: Dr. Sutanu
  Chakraborti, CSE, IIT Madras"
draft: false
featured: false
links:
  - name: Paper
    url: https://arxiv.org/pdf/2012.00398.pdf
    icon: ""
image:
  filename: ""
  focal_point: Smart
  preview_only: false
---
Explicit Semantic Analysis (ESA) is a technique used to rep-resent a piece of text as a vector in the space of concepts, such as Articlesfound in Wikipedia. We propose a methodology to incorporate knowledgeof Inter-relatedness between Wikipedia Articles to the vectors obtainedfrom ESA using a technique called Retrofitting to improve the perfor-mance  of  subsequent  tasks  that  use  ESA  to  form  vector  embeddings.Especially we use an undirected Graph to represent this knowledge withnodes as Articles and edges as inter relations between two Articles. Here,we also emphasize how the ESA step could be seen as a predominantlybottom-up approach using a corpus to come up with vector representa-tions and the incorporation of top-down knowledge which is the relationsbetween Articles to further improve it. We test our hypothesis on sev-eral smaller subsets of the Wikipedia corpus and show that our proposedmethodology leads to decent improvements in performance measures in-cluding Spearman’s Rank correlation coefficient in most cases.