---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Machine Unlearning"
subtitle: ""
summary: "We aimed to research on removing specific classes of data from a pre-trained LLM model by using Adapter Based approaches and model pruning "
tags: []
categories: []
date: "2023-11-26T00:00:00Z"

url_code: "https://github.com/vlgiitr/Machine_Unlearning"
url_pdf: ""
url_slides: ""
url_video: ""
projects: []
weight: 1
---
Machine unlearning is an emergent subfield of machine learning that aims to remove the influence of a specific subset of training examples — the "forget set" — from a trained model. Furthermore, an ideal unlearning algorithm would remove the influence of certain examples while maintaining other beneficial properties, such as the accuracy on the rest of the train set and generalization to held-out examples.

A straightforward way to produce this unlearned model is to retrain the model on an adjusted training set that excludes the samples from the forget set.
