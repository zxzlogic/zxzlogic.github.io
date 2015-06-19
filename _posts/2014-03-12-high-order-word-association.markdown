---
layout: post
title:  "Pure High-order Word Association Mining"
date:   2014-03-17 16:47:40
categories: project
---
The contextual high-order word association, e.g., {climate, conference, Copenhagen}, 
indicates that the words in the same association serve as context of each other and form a high-level semantic meaning.
A counterexample is the combination {a, the, of}.

Intuitively, we consider a word combination has "pure dependence" iff its corresponding joint distribution can not be factorized (conditionally or unconditionally).
For a combination with two words, the decision problem is related to the classical test for independence in statistics (e.g., chi-square test).
However, there is lack of an efficient algorithm to decide on the "pure dependence", especilly for the high-order case
with a large corpus.

Based on information geometry, we develop sufficient conditions for deciding on "pure dependence", leading to an efficient implementation
using the log-likelihood ratio test (LLRT) on some statistic &rho;.
Refer to our ACM TOIS paper for more details. ( <a href="../../../../code/Demo_TOIS.zip" target="_blank">Matlab demo code</a> )

