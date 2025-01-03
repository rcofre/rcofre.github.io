---
title: "Neural mass modeling for the masses: Democratizing access to whole-brain biophysical modeling with FastDMF"
collection: publications
#permalink: /publication/2009-10-01-paper-title-number-01b
#excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: December 2024
venue: 'Network Neuroscience 2024; 8 (4): 1590-1612'
#paperurl: 'http://academicpages.github.io/files/paper1.pdf'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

[Download paper here](https://direct.mit.edu/netn/article/8/4/1590/123888)
[Code](https://gitlab.com/concog/fastdmf)


Abstract:
Different whole-brain computational models have been recently developed to investigate hypotheses related to brain mechanisms. Among these, the Dynamic Mean Field (DMF) model is particularly attractive, combining a biophysically realistic model that is scaled up via a mean-field approach and multimodal imaging data. However, an important barrier to the widespread usage of the DMF model is that current implementations are computationally expensive, supporting only simulations on brain parcellations that consider less than 100 brain regions. Here, we introduce an efficient and accessible implementation of the DMF model: the FastDMF. By leveraging analytical and numerical advances-including a novel estimation of the feedback inhibition control parameter and a Bayesian optimization algorithm-the FastDMF circumvents various computational bottlenecks of previous implementations, improving interpretability, performance, and memory use. Furthermore, these advances allow the FastDMF to increase the number of simulated regions by one order of magnitude, as confirmed by the good fit to fMRI data parcellated at 90 and 1,000 regions. These advances open the way to the widespread use of biophysically grounded whole-brain models for investigating the interplay between anatomy, function, and brain dynamics and to identify mechanistic explanations of recent results obtained from fine-grained neuroimaging recordings.
