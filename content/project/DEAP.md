---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Deep Cache Replacement - 2020"
subtitle: ""
summary: "The PyTorch codebase for DEAP Cache: Deep Eviction Admission and Prefetching for Cache."
tags: []
categories: []
date: "2020-09-19T00:00:00Z"

url_code: "https://github.com/vlgiitr/deep_cache_replacement"
url_pdf: ""
url_slides: ""
url_video: ""
projects: []
weight: 7
---

The PyTorch codebase for DEAP Cache: Deep Eviction Admission and Prefetching for Cache.

In this paper, we propose a DL based approach to tackle the problem of Cache Replacement. This is the first time an approach has tried learning all the three policies: Admission, Prefetching and Eviction. Unlike, previous methods which relied on past statistics for carrying out cache replacement, we predict future statistics (frequency and recency) and then use an online RL-algorithm for eviction.
