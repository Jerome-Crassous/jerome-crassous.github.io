---
title: "Frictional Discrete Elastic Rods"
date: 2023-02-22
permalink: /posts/DER/
---

Based on work carried out in 2005 on the modeling of elastic fibers, I have developed a numerical code of the discrete element. None of the various ingredients of this code (Discrete Elastic Rod, explicit integration of the equations of motion, treatment of frictional contacts) are individually original. However, this combination allows us to tackle a variety of problems in a simple way. Writing the code from scratch means that, at the cost of considerable optimization work, the code is very light and compact.  In particular, control over the physical ingredients of the model is total, and the contact detection part is specifically optimized to handle a large number of elongated objects. The code has been tested in a wide range of configurations and geometries, with comparisons to analytical solutions where available. 
<img src="\images\3_1_knot.png" width="500">
[https://doi.org/10.1103/PhysRevE.107.025003](https://doi.org/10.1103/PhysRevE.107.025003)