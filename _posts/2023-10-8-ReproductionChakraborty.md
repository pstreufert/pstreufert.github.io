---
title: "Reproduction Plan for Chakraborty, 2020"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - COVID
  - OpenSource
  - Reproduction
---
# Revisions to reproduction of Chakraborty (2021)
Social inequities in the distribution of COVID-19: An intra-categorical
analysis of people with disabilities in the U.S.
Jayajit Chakraborty, PhD

This lab sought to reanalyze the Chakraborty (2021) study of spatial inequalities of covid 19 distribution in peoples with disabilities. The code was created in a previous reproduction study and this version of the reproduction explores the following research choices: 

The current study to explore effects of the covid 19 pandemic on peoples with disabilities (PwD) draws from a collection of hotspots using a Kulldorff spatial scan statistic. This tool selects hotspots by aggregating data at a county level to calculate relative risk within various spherical great circle distance calculations; upon calculating these scores, the model selects the circle with the greatest relative risk and designates the epicenter of the cluster and the surrounding counties. The model problematically clumps the majority of the southeast into a single hotspot, ignoring key covid centers. This reproduction tested the volatility of the tool by adjusting the maximum circle population threshold from 50% to 5%. As a result several counties located in the periphery of previous larger hotspots were marked as hotspots. 

Through a reanalysis of the Chakraborty (2021) study I learned that many seemingly small research decisions may have major implications for the outcome of the study. The single line of code that changed the max population parameter for the Kulldorf statistic had significant changes to the study scope. There may be opportunities to explore how the increased number of hotspots changes the bivariate analysis to further understand the subjectivity and volatility of the study. 
