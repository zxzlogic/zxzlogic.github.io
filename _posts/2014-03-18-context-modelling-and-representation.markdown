---
layout: post
title:  "Context Representation and Modelling"
date:   2014-03-18 15:11:40
categories: project
---

In information retrieval tasks, we need to analyze the contextual information, which is composed of high-order word patterns with semantic 
associations implied by the textual data.
The definition of context should satisfy the following metrics: <br />
(1) the information provided is large enough; <br />
(2) the noise contained is small enough; <br />
(3) it is effective in terms of time and space cost.<br />

In order to process the massive data with high dimensionality, the traditional data mining algorithms choose the neighborhood terms within 
a certain scope surrounding the core word as the context, the so-called "window". Besides, some traditional word association approaches 
could be used to analyze the contextual information, such as the Apriori approach, closed frequency itemset, co-occurrence analysis, 
syntactical phrase and word-net association, etc.

In terms of probabilistic statistics, the context composed of several terms could be sufficiently described by the joint probability distribution.
And the pure high-order word association (described in the former post) could lead to a new perspective for the interpretation of contextual semantics w.r.t.
the properties of the joint distribution.

Recently, we have just opened up a collaborative project with Baidu on the Baidu openresearch community. ( <a href="http://openresearch.baidu.com/news/1327.jhtml">Project No. 5</a> )

