---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

[Curriculum Vitae](https://drive.google.com/file/d/1XdNfgDjhyhylxJj1FL0xkpjfiMEGn2W4/view?usp=sharing)
-===

[Atmospheric Dynamics Modeling Group Website](https://admg.engin.umich.edu/)

[UM CLaSP Webpage](https://clasp.engin.umich.edu/)


Bio
-======

I grew up outside of Los Angeles, CA and received my B.S. and M.S. in Physics at California State University, Northridge in 2016 and 2018, respectively. I worked in the research lab of Dr. Tyler Luchko studying and implementing various numerical methods for the 3D Reference Interaction Site Model (3D-RISM), a molecular solvation model. Upon graduating in 2018, I was awarded the Graduate Research Fellowship Program (GRFP) fellowship from NSF and enrolled in the department of Climate and Space Sciences and Engineering at the University of Michigan for my doctoral studies. At Michigan I have been working under the advisement of Dr. Christiane Jablonowski in the area of advancing our understanding of the interface of climate modeling and machine learning. While working on my research and coursework in atmospheric science, I enrolled in the Science, Technology, and Public Policy graduate certificate program through the Ford School of Public Policy, as well as the Data Science graduate certificate program offered by the Michigan Institute for Data Science. Upon graduating, I intend to pivot to a career in data science, ideally with a company that would value my diverse expertise across fields like computational physics, atmospheric science, and science policy.

Research Interests
-======

During my PhD, I have been focused primarily on the question of feasibility and limitations of machine learning (ML) applications for emulating the physical parameterizations in climate models. Physical parameterizations are responsible for the sub-grid scale processes occuring in the atmosphere but cannot be explicitly resolved with the fluid flow calculations. Thus, they are parameterized and are responsible for significant bias and uncertainty in GCMs. Working with the Community Atmosphere Model (CAM), the atmospheric component of the Community Earth System Model developed by NCAR, we have been able to train and test ML emulators for various simplified model configurations. We recently showed how offline random forest emulators can be highly skillful for various idealized CAM configurations, but with just minor increases in complexity we do observe non-negligible decreases in skill. Details on the promises and potential limitations of these techniques, as well as comparisons to baseline neural network implementations, can be found in my recent manuscript [available here](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2022MS003395).

Currently, my projects consist of testing online implementations of my random forest and neural network emulators, as well as the development of an object-oriented Python library for development ML emulators for parameterization schemes. The coupling project is an extension of the work in our recent maniscript (Limon & Jablonowski, 2023) and has required a significant amount of troubleshooting both from a hardward and software standpoint. The workflow software is something we believe the community would be greatly interested in for future researchers to be able to pre- and post-process their data, as well as create, train, test, and export their ML models in a signular python workflow.
