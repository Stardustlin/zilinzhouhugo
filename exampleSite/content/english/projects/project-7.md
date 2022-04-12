---
title: "Form Follows Force"
date: 2020-06-10T15:40:24+06:00
# Project thumb
image : "images/projects/Project7/cover2.jpg"
draft: false
# description
description: "This is meta description"

# links
links:
  - label : ""
    link : ""
---

<div style="text-align: center; font-size: 1em">
Individual Undergraduate Graduation Project<br>
Shanghai, China<br>
Jun 2020
</div>


---
---

**Performance-based Design** and **Intelligent Fabrication** are the two major elements leading the future architectural design. The research areas include the improvement of material performance, the rational optimization of the structure and the intelligence of the fabrication process. However, the traditional construction mode is still in a relatively separated state of design, structure, and construction, which shows in the disparity between the design form and the structural performance, the misalignment of the optimized structure and the construction details, etc.

The purpose of this research is to coordinate materials, structure, and fabrication to realize the integration of design and construction and the systematization of data flow, so as to explore the future digital architectural design mode. This project is a systematic design research of engineering wood, structural performance optimization and robotic fabrication through the design and construction of a wooden pavilion.

---

<p align="center">
  <img width=90% src="/images/projects/Project7/1.jpg">
</p>

---
---

I'm inspired by the skeletal shell structure of nautilus, which achieves stable performance by itself. Similar to the shell structure, a plane prototype is generated with an equiangular spiral. Then through parametric design, the plane UV grid is divided, and the height is raised and offset to form the original shell structure. 

---

<p align="center">
  <img width=90% src="/images/projects/Project7/2.jpg">
</p>

---
---

The second step is to analyze and optimize the shell structure. By setting the optimization parameters for the change of the shell form, such as the offset of the inner and outer bumps, the lifting height, etc. Karamba is used to analyze the shell structure, and the genetic algorithm is used for iterative analysis to reduce the strain energy and offset of the structure. The overall optimized structure can be seen that the shell is gradually optimized from a smooth curved surface to a stable structure with uneven cross-sections. 

---

{{< youtube id="hNX37lui4ZY" autoplay="false" >}}

---
---

The third step is to perform the topological shaping from the shell to the reticulated shell rod. It is divided into supported curved beams and ring beams, as well as internal supporting rods. At the same time, the complex node generation of the end connection is carried out. On this basis, karamba is used to optimize the distribution position of the rods and the number of layers to achieve the minimum strain energy. At the same time, karamba's cross-section selection algorithm was optimized to obtain the optimal cross-section of the member. 

---

{{< youtube id="60z23CJTFm0" autoplay="false" >}}


---
---

The fourth step is to carry out design deepening and digital construction on the basis of design. I divided the built components into three categories, including wood node milling, straight wood rods and curved wood rods, to correspond to different processing methods and processes. 

I made a 1:10 partial scale model, to verify the stability of the connection between the node and the bar, and to adjust the length of the node and the depth of the concave-convex mortise and tenon. This adjustment is also fed back to the previous design and optimization process. 

---

<p align="center">
  <img width=90% src="/images/projects/Project7/3.jpg">
</p>

---
---

The construction of 120 nodes will be milled with a six-axis robotic arm configured with milling cutters. The curved beam is processed with two-dimensional planarization and the straight rod is processed by CNC. 

---

{{< youtube id="ya7nZ1w3ZL8" autoplay="false" >}}


---
---

I made a 1:2 wooden node model to verify the manufacturing process of the node. Through the simulation of the robot arm, the spatial path planning of the wood node milling is carried out, which is divided into the surface of the milling node and the groove of the node.

---

<p align="center">
  <img width=90% src="/images/projects/Project7/5.jpg">
</p>




