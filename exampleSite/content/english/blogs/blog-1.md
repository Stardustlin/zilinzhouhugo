---
title: "Curved Curtain Wall Glass Splitting "
date: 2020-10-14T15:40:24+06:00
# talks thumb
image : "images/blogs/Blog1/covernew.jpg"
draft: false
# description
description: "This is meta description"

# links
links:
  - label : "File"
    link : "https://drive.google.com/drive/folders/1FZYeA0e2uzyRXa_vMz9b6WQCT1KL8Gan?usp=sharing"
---

After a week of detailed division of the curved curtain wall, I find that the subtle adjustments brought about by the parameter changes, like the butterfly effect, will cause more problems in the next fabrication process. The building itself is an industry that requires multi-party collaboration. Design, prefabrication, and final on-site construction are difficult to achieve through a platform to form the entire process of data transmission. This leads to the progress of each step means the rework of the previous step, and the accumulated error value will affect the final appearance of the building. 

In this blog, I will mainly share the script of flat glass flattening and some gradient division. 

<div style="text-align: center">
—— Flat glass ——
</div>

---

In order to save costs, I hope to transform the curved curtain wall into a flat quadrilateral curtain wall, which is convenient for factory production and processing. The problem is that there will be a misalignment between the two pieces of glass after flattening, and what needs to be solved is to minimize the error caused by the misalignment. You can adjust the curvature of the original curve or adjust the spacing of the slits. In principle, the denser the slits. The smaller the error, but the visual effect will not be particularly beautiful. 

Therefore, two methods are adopted. One is to use kangaroo to adjust the curvature of the curve for flattening, and to use the center of the glass plate for projection positioning. The alignment error is basically within the acceptable 2mm error. After the experiment, I think the effect of not adding kangaroo is acceptable. 

<p align="center">
  <img width=90% src="/images/blogs/Blog1/1.jpg">
</p>

---

The second method is to use a combination of quadrilateral and triangle divisions for some hyperbolic glass curtain walls, and focus the error on the subsequent adjustable triangles. When the curtain wall is processed, the triangles can be made into glass mullions. 

<p align="center">
  <img width=90% src="/images/blogs/Blog1/2.jpg">
</p>

---
---

<div style="text-align: center">
—— Curtain wall Gradual division ——
</div>

---

The curtain wall division is the division of the corresponding aluminum plates. Because the processing size is required, the width of the single aluminum plate should be controlled within 1.6m, and at the same time, the widest width should be controlled at about 0.8m, for example. Therefore, the parameterized initial conditions can be transformed into a certain total curve length L, a determined starting point single piece width of 0.8m, a determined end point single piece width of 1.5m, and the rest of the aluminum plates inside should be gradually reduced in a smooth manner. 

Because the total length and the maximum and minimum values are fixed, the division of the simple arithmetic geometric sequence becomes invalid. Therefore, I chose to use the graph's change curve for incremental division, and at the same time, add a variable of the exponential function as the input parameter of the genetic algorithm optimization, so that the total length after smooth division is infinitely close to the required total length. 

<p align="center">
  <img width=90% src="/images/blogs/Blog1/3.jpg">
</p>
