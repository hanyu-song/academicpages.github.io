---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---



As we have entered the era of big data, I feel that statistics needs to find ways to adequetly handle the massive data sets that are now common. This problem is especially pronounced for Bayesian statistics. Bayesian statistics has many advantages, such as automatic uncertainty quantification, the ability to incorporate prior knowledge in models, and the ability share information across experiments. These advantages, however, are of limited use in the face of big data because Bayesian computational methods scale very poorly. Thus there is a pressing need to develop methods for scalable Bayesian inference. 

## Projects

# Scalable Clustering
I am currently working on techniques scalable Bayesian clustering. Bayesian clustering can be done using mixture models or Bayesian non-parametrics, but there are still unresolved challenges. For instance, MCMC suffers from the label-switching problem, where the cluster labels switch because the model is not identified. This problem makes inference challenging. In addition, when attempting to cluster in parallel, we must consider how to align the clusters across nodes. These are both challenging problems that I very much enjoy working on. 


# Scalable Variable Selection
The problem of variable selection in high dimensions is an area of active research. For example, techniques like the [LASSO](https://en.wikipedia.org/wiki/Lasso_(statistics)) have quickly become standard in statistics. I am helping [Xiangyu (Samuel) Wang](http://www2.stat.duke.edu/~xw56/Research.html) and David Dunson develop a Bayesian method for variable selection in parallel. The technique, called BayesDECO, is an extension of a method developed by [Wang and Dunson](https://arxiv.org/abs/1602.02575) that uses decorelation to perform variable selection in parallel. 
