---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
======
Hi! I'm a senior undergraduate student at the University of Toronto, majoring in Computer Science and Mathematics.
In parallel, I've been working as a research assistant at the [Dynamic Graphics Project](https://www.dgp.toronto.edu/) Lab, advised by Prof. [Alec Jacobson](https://www.cs.toronto.edu/~jacobson/). Currently I'm doing a summer internship at [Adobe Research](https://research.adobe.com/) under Dr. [Qi Sun](https://qisun.me/) and Dr. [Xin Sun](http://www.sunxin.name/).

I'm broadly interested in physics-based animation, geometry processing, computational fabrication, interactive graphics and novel interfaces that augment creativity and productivity.

Previously, I've explored different research areas with Prof. [Ken Jackson](http://www.cs.toronto.edu/~krj/) on numerical analysis and with Prof. [Fanny Chevalier](http://fannychevalier.net/) on HCI / visualization. I also did research in geometric modeling with Prof. [Marc Alexa](https://www.eecs.tu-berlin.de/cg-archiv/menue/team/alexa/) and physics-based animation with Prof. [David Levin](http://diwlevin.webfactional.com/researchdb/) and Prof. [Alec Jacobson](https://www.cs.toronto.edu/~jacobson/). It's my great honour to be selected as a finalist for [CRA Outstanding Undergraduate Researcher Award](https://cra.org/about/awards/outstanding-undergraduate-researcher-award/) 2020 and an awardee for [Adobe Research Women-in Technology Scholarship](https://adoberesearch.ctlprojects.com/scholarship/previous-scholarship-award-winners/) 2020.

<!-- You can download my full [CV](https://eriszhang.github.io/files/Jiayi-Eris-Zhang-CV.pdf) here. -->

Publications
======

<img width="175" align="left" src="../images/rotation-teaser.jpg"/>

&nbsp; __Fast Updates for Least-Squares Rotational Alignment__<br/>
&nbsp;  __Jiayi Eris Zhang__, Alec Jacobson, Marc Alexa<br/>
&nbsp;  *In Submission*<br/>

<br/>

<img width="175" align="left" src="https://ErisZhang.github.io/images/comp-dynamics-representative-image.jpg"/>

&nbsp; __Complementary Dynamics__  
<!-- &nbsp;  __Jiayi Eris Zhang__, [Seungbae Bang](https://sites.google.com/view/seungbaebang/home), [David I.W. Levin](http://diwlevin.webfactional.com/researchdb/), [Alec Jacobson](https://www.cs.toronto.edu/~jacobson/)   -->
&nbsp;  __Jiayi Eris Zhang__, Seungbae Bang, David I.W. Levin, Alec Jacobson  
&nbsp;  *ACM SIGGRAPH ASIA 2020*<br/>
&nbsp;  [Paper](https://eriszhang.github.io/files/complementary-dynamics-paper.pdf) | [Paper (low res)](https://arxiv.org/abs/2009.02462) | [Project Page](https://www.dgp.toronto.edu/projects/complementary-dynamics/) <br/>
&nbsp; **Featured in the  <a href="https://www.youtube.com/watch?v=Q45KT0lGd7A" style="color:rgb(232, 60, 37);font-size:16px">Technical Papers Trailer</a>*<br/>


<br/>

<img width="175" align="left" src="https://ErisZhang.github.io/images/teaser-1.jpg"/>

&nbsp; __DataQuilt: Extracting Visual Elements from Images to Craft Pictorial__<br/>
&nbsp; __Visualizations__<br/>
&nbsp;  __Jiayi Eris Zhang__, Nicole Sultanum, Anastasia Bezerianos, Fanny Chevalier<br/>
&nbsp;  *ACM Conference on Human Factors in Computing Systems (CHI), 2020*<br/>
&nbsp;  [Paper](https://eriszhang.github.io/files/dataquilt-paper.pdf) | [Project Page](https://dataquilt.github.io/)

<br/>

Selected Projects
======
<div>
<div style="font-size:12pt"><strong>Fast Updates for Least-Squares Rotational Alignment</strong></div>
<div style="font-size:10pt">Across computer graphics, vision, robotics and simulation, many applications rely on determining the 3D rotation that aligns two objects or sets of points. The de facto solution is to use singular value decomposition (SVD), where the optimal rotation is recovered as the product of the singular vectors. While correct, we observe that SVD computes much more information than necessary to build the optimal rotation. In this project, we propose a novel way for efficiently computing updates for least-squares rotational alignment problems. We show that a single Newton-like step is sufficient for small-rotation settings and further optimize implementation using AVX vectorization. 

</div>
</div>
<img width="100%" src="https://ErisZhang.github.io/images/fast-fitting.jpg"/>


<div>
<div style="font-size:12pt"><strong>Fast Support Reduction</strong></div>
</div>
<div style="font-size:10pt"> In layer-based 3D fabrication, supporting structures are fabricated
to support overhanging regions yet discarded later. Reducing supports
saves both time and material cost. In this project, we propose 
a real-time skinning-based method to slim down the
supporting structure while maintaining a detailed-preserved and semantically meaningful geometry.
We achieve this by optimizing a set of performance objectives and searching globally in
the subspace spanned by the joint handles. Artifacts e.g. self-intersection can be effectively avoided.
Our method is implemented via OpenGL shaders and has potential to be
employed as a structural prototyping tool that facilitates model design and fabrication. </div>
<img width="100%" src="../images/bb-bunny.jpg"/>

<br/>

Contact
======
jiayieris.zhang (at) mail.utoronto.ca