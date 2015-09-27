---
layout: post
title:  "Model selection for Boltzmann machine"
date:   2015-09-28 04:08:40
categories: project
---

One of the most important problem in machine learning is over-fitting. Various information criterion, for instance, the Akaike information criteria (AIC) and the Bayesian information criteria (BIC), have been proposed to deal with over-fitting via a penalty term to compensate more complex models. However, the AIC and the BIC assume that each parameter makes equal contribution to the model complexity, i.e. each parameter is equally important to the model, and regard the number of model parameter as the measure of model complexity, which is not suitable for many non-linear models, such as the Boltzmann Machines (BMs). This paper introduce a FIS (Fisher information selection) approach to guide model selection. The FIS is more general since we assume that each parameter has different importance with respect to the model. Specifically, the FIS compensates harder (or softer) to parameters with lower (or higher) fisher information. We apply the FIS in a series of VBM density estimation experiments. Experimental results indicate that the FIS achieves a better performance than the AIC and the BIC.

This paper can be downloaded from <a href="../../../../code/ms_fisher.pdf" target="_blank">here</a>.
