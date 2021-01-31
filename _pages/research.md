---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---



## Research Statement
AI-based software systems are increasingly used across application domains. However, one of the key challenges continues to be the reliability and correctness of AI-based systems. At the core of AI-based software systems is a machine learning (ML) model that is used to perform tasks such as classification and prediction. Fundamentally, traditional software applications have a deterministic logic written by humans with a pre-defined output. Compared to this, ML models derive their decision logic based on a dataset, and in most cases, they do not have a pre-defined output. Thus, existing testing techniques cannot be directly applied to test AI-based applications. The broader goal of my Ph.D. work is to ***develop methodologies for testing AI-based software systems***.  

My work so far is focused on the following areas: 
* **Test input generation:**
   * Generate t-way test inputs (using combinatorial testing) to ***test five classical machine learning algorithms*** 
   * Generate synthetic image frames to ***test DNN models*** used in ***Autonomous driving systems*** (under review)
* **Test cost reduction:**
    * Empirically analyze the ***effect of using sampled datasets to test supervised learning algorithms***
* **Debugging:**
    * Develop a ***model-agnostic, post-hoc XAI-tool*** that produce *counterfactual explanations* for Image based classifiers.
    * Develop ***a framework to debug big data applications***

## Current Project
My **current project** focuses on developing an explainable AI (XAI) tool that shall produce explanations for decisions made by Deep Neural Network (DNN) models. The explanation can help engineers determine the cause of incorrect decisions of an DNN model (i.e., debugging an DNN model). Conceptually, deriving an explanation for a model’s decision (XAI) is similar to software fault localization, a well-studied problem in software engineering.  In this project, I investigate how to ***use/adopt existing software fault localization techniques and produce explanations for decisions made by ML models***. 

