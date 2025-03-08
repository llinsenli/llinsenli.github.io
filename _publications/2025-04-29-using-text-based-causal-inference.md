---
title: "Using Text-Based Causal Inference to Disentangle Factors Influencing Online Review Ratings"
collection: publications
category: conferences
permalink: /publication/2025-04-29-using-text-based-causal-inference
excerpt: 'This paper examines the causal impact of different aspects mentioned in online reviews of U.S. K-12 schools on overall ratings using an enhanced CausalBERT framework to improve treatment effect estimation and interpretability.'
date: 2025-04-29
venue: 'Proceedings of the HLT/NAACL 2025'
paperurl: ''
citation: ''
---

ABSTRACT
======
Online reviews provide valuable insights into the perceived quality of facets of a product or service. While aspect-based sentiment analysis has focused on extracting these facets from reviews, there is less work understanding the impact of each aspect on overall perception. This is particularly challenging given correlations among aspects, making it difficult to isolate the effects of each. This paper introduces a methodology based on recent advances in text-based causal analysis, specifically CausalBERT, to disentangle the effect of each factor on overall review ratings. We enhance CausalBERT with three key improvements: temperature scaling for better calibrated treatment assignment estimates; hyperparameter optimization to reduce confound overadjustment; and interpretability methods to characterize discovered confounds. In this work, we treat the textual mentions in reviews as proxies for real-world attributes. We validate our approach on real and semi-synthetic data from over 600K reviews of U.S. K-12 schools. We find that the proposed enhancements result in more reliable estimates, and that perception of school administration and performance on benchmarks are significant drivers of overall school ratings.