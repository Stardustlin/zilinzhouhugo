---
title: "Form Finding Via Machine Learning"
date: 2019-07-10T15:40:24+06:00
# Project thumb
image : "images/projects/Project5/cover_new.jpg"
draft: false
# description
description: "This is meta description"

# links
links:
  - label : "PDF"
    link : "images/projects/Project5/Form_finding_via_machine_learning_portfolio.pdf"
---

<div style="text-align: center; font-size: 1em">
The 9th DigitalFUTUREs International Workshop<br>
Advisor: Hao Zheng<br>
Shanghai, China<br>
Jul 2019
</div>

---
**This is a collaboration between computer science and architecture to complete an exploratory revolution in structure and space.**

If one day, the computer can replace the architect to complete the intellectual level of architectural design, then where should the architecture go? Can architecture open up new design strategies and design areas in the highly computational future?

This project focuses on how designers use computational thinking to redefine designs and recreate designs. By using machine learning, we try to let computers learn the generation of architectural forms in three-dimensional space and explore the prospects of machine learning in the field of architectural form generation. Through data collection and data training in neural network, new architectural forms are created depending on the training output. These machine-designing forms are collected to form the future city scenarios.

---
---
**Methodology**<br>
Through machine learning of big data, the design logic hidden behind data will be revealed, thus creating an artificial intelligence model to predict the architectural forms that match the form-finding goals. This neural network model concludes design strategies from learning procedure, storeing design rules, and generating architectural forms by recalling the parameters.<br>
**Data Preperation**<br>
To match with the feasible data structure for machine learning. Details that have little effects on the overall forms will be removed. Simplified models can be built by extracting the main section curves and lofting them together. The basic idea is to translate a surface into a series of real number by extracting the coordinates of the controlling points to match the data structure of the machine learning network. The collection of the real numbers together represent the form of the tower, showing a more efficient data structure than 3D volumes with a large number of voxels.

<p align="center">
  <img width=90% src="/images/projects/Project5/1.jpg">
</p>

---
---
**Collecting Process** <br>
In order to test the performance of the idea of the network with real-world forms, 300 models of the towers built by different designers were collected and used as a dataset for training in the next step. Similarly to the designed methodology, the real-data of the coordinate system were extracted from the collected models.<br>
**Data Training** <br>
The input neurons contain the required information to start a design. In this case, the input data is the boundary curvature and the height of the building, and the feature parameters showing the design style. The output data is the generated form under the input condition, showing the predicted design outcome from a given architect or a combination of styles from different architects. The hidden layer works to map the input and output data, mathematically expressing the design rules.

<p align="center">
  <img width=90% src="/images/projects/Project5/2.jpg">
</p>

---
---
**Testing Process**<br>
To test the performance of the network, the testing dataset was generated and inputted to the network. In the training process, the network will only update itself by learning the training dataset without loading the testing dataset, so comparing the expected forms and the predicted forms of the testing dataset is the best way to evaluate the performance of the network.

<p align="center">
  <img width=90% src="/images/projects/Project5/3.jpg">
</p>
