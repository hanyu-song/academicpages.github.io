---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---



As we have entered the era of big data, I feel that statistics needs to find ways to adequetly handle the massive data sets that are now common. This problem is especially pronounced for Bayesian statistics. Bayesian statistics has many advantages, such as automatic uncertainty quantification, the ability to incorporate prior knowledge in models, and the ability share information across experiments. These advantages, however, are of limited use in the face of big data because Bayesian computational methods scale very poorly. Thus there is a pressing need to develop methods for scalable Bayesian inference. 

## Projects

# Scalable Clustering

In many modern applications, there is interest in analyzing enormous datasets that cannot be easily moved across computers or loaded into memory on a single computer.  In such settings, it is very common to be interested in clustering.  However, simple divide-and-conquer approaches are not appropriate for clustering problems in that clusters are inherently describing relationships in all the data points.  Currently we are developing a model-based Bayesian approach to clustering.  Our goal is to develop a computationally efficient algorithm that is nearly embarrassingly parallel and avoids moving individual data between computing nodes.  


# Scalable Variable Selection
The problem of variable selection in high dimensions is an area of active research. For example, techniques like the [LASSO](https://en.wikipedia.org/wiki/Lasso_(statistics)) have quickly become standard in statistics. I am helping [Xiangyu (Samuel) Wang](http://www2.stat.duke.edu/~xw56/Research.html) and David Dunson develop a Bayesian method for variable selection in parallel. The technique, called BayesDECO, is an extension of a method developed by [Wang and Dunson](https://arxiv.org/abs/1602.02575) that uses decorelation to perform variable selection in parallel. 
