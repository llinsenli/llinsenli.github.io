---
title: "Using Text-Based Causal Inference to Disentangle Factors Influencing Online Review Ratings"
collection: publications
category: conferences
permalink: /publication/2025-04-29-using-text-based-causal-inference
excerpt: 'This paper examines the causal impact of different aspects mentioned in online reviews of U.S. K-12 schools on overall ratings using an enhanced CausalBERT framework to improve treatment effect estimation and interpretability.'
date: 2025-04-29
venue: 'Proceedings of the HLT/NAACL 2025'
paperurl: 'https://aclanthology.org/2025.naacl-long.562/'
citation: 'Linsen Li, Aron Culotta, and Nicholas Mattei. 2025. Using Text-Based Causal Inference to Disentangle Factors Influencing Online Review Ratings. In Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers), pages 11259–11277, Albuquerque, New Mexico. Association for Computational Linguistics.'
---

ABSTRACT
======
Online reviews provide valuable insights into the perceived quality of facets of a product or service. While aspect-based sentiment analysis has focused on extracting these facets from reviews, there is less work understanding the impact of each aspect on overall perception. This is particularly challenging given correlations among aspects, making it difficult to isolate the effects of each. This paper introduces a methodology based on recent advances in text-based causal analysis, specifically CausalBERT, to disentangle the effect of each factor on overall review ratings. We enhance CausalBERT with three key improvements: temperature scaling for better calibrated treatment assignment estimates; hyperparameter optimization to reduce confound overadjustment; and interpretability methods to characterize discovered confounds. In this work, we treat the textual mentions in reviews as proxies for real-world attributes. We validate our approach on real and semi-synthetic data from over 600K reviews of U.S. K-12 schools. We find that the proposed enhancements result in more reliable estimates, and that perception of school administration and performance on benchmarks are significant drivers of overall school ratings.

<div style="text-align: center;">
    <img src="/images/li2025using_syn_main_result.png" alt="syn_main_result" width="800"/>
</div>

<div style="text-align: center;">
    <img src="/images/li2025using_temp_result.png" alt="temp_result" width="800"/>
</div>

<div style="text-align: center;">
    <img src="/images/li2025using_real_est_result.png" alt="real_est_result" width="800"/>
</div>

<div style="text-align: center;">
    <img src="/images/li2025using_ig_result.png" alt="ig_result" width="800"/>
</div>