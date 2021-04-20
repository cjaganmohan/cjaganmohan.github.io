---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---



## Research Statement
AI-based software systems are increasingly used across application domains. However, one of the key challenges continues to be the reliability and correctness of AI-based systems. At the core of AI-based software systems is a machine learning (ML) model that is used to perform tasks such as classification and prediction. Fundamentally, traditional software applications have a deterministic logic written by humans with a pre-defined output. Compared to this, ML models derive their decision logic based on a dataset, and in most cases, they do not have a pre-defined output. Thus, existing testing techniques cannot be directly applied to test AI-based applications. The broader goal of my Ph.D. work is to ***develop methodologies for testing AI-based software systems***. 

## Current Project
My current project focuses on developing an explainable AI (XAI) tool that shall produce explanations for decisions made by Deep Neural Network (DNN) models. The explanation can help engineers determine the cause of incorrect decisions of an DNN model (i.e., debugging an DNN model). Conceptually, deriving an explanation for a model’s decision (XAI) is similar to software fault localization, a well-studied problem in software engineering.  In this project, I investigate how to ***use/adopt existing software fault localization techniques and produce explanations for decisions made by DNN models***. -- [(preprint](https://cjaganmohan.github.io/files/XAI_Tool_pre_print_IWCT_2021.pdf), [(video)](https://www.youtube.com/watch?v=uGdJnsvC7m4)  

## Past Projects

### Test Input Generation for Testing DNN models
Generating data to test AI systems, particularly for image-based AI systems such as autonomous driving systems, is a time-consuming and expensive process. In this project we propose a combinatorial approach to generate test data (images) to test Deep Neural Network (DNN) models used in autonomous driving cars. Each test input represents a combination of image transformations, and can be used to produce a test image. We conducted an experimental evaluation of our approach on three DNN models that are used in the Udacity challenge. Results suggest that combinatorial testing can be effectively applied, and the proposed approach detects a significant number of inconsistent (or undesired) behaviors in pre-trained DNN models developed to predict the steering angle of a car.  -- [(preprint)](https://cjaganmohan.github.io/files/Testing_DNN_pre_print_IWCT_2021.pdf), [(video)](https://www.youtube.com/watch?v=978CwhOWG54)

### Test cost reduction
Many machine learning algorithms examine large amounts of data to discover insights from hidden patterns. Testing these algorithms can be expensive and time- consuming. There is a need to speed up the testing process, especially in an agile development process, where testing is frequently performed. One approach is to replace big datasets with smaller datasets produced by random sampling. In this project, we report a set of experiments that are designed to evaluate the effectiveness of using reduced datasets produced by random sampling for testing machine learning algorithms. Results suggest that reduced datasets can be used to accelerate the testing phase of ML applications while largely preserving the fault detection effectiveness of the original datasets. -- [(preprint)](https://cjaganmohan.github.io/files/Effectiveness_of_dataset_reduction_pre_print_AITest2020.pdf), [(video)](https://www.youtube.com/watch?v=j_4Nz04hmbM)





