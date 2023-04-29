---
title: "An Analysis of Predictive Identification for Major Depressive Disorder Using Transfer Learning 🧠 🩻"
excerpt: "Problems such as identifying Schizophrenia and Alzheimer’s have shown great results when using neural net- works. In this paper, we analyze the results of using transfer learning to identify MDD in MRI scans. <br/><br/><img src='/images/dl-mri.png'>"
collection: portfolio
---

In the past decade, mental health has become more prominent within society and less neglected within the medical industry. Researchers and hospitals have begun to put more resources to develop methodologies to identify such illnesses effec- tively. Recently, the most common mental illnesses that have been explored are Schizophrenia [2, 3, 4] and Alzheimer’s. However, in this paper we focus on a more challenging and minimally explored problem - Major Depressive Disorder (MDD).

MDD is a persistent low mood and/or anhedonia and is a common condition disorder that can often go undi- agnosed. Currently, most diagnoses of MDD are evaluated through a series of structured interviews that look at clinical parameters. Even more so, around two-thirds of all cases of depression, including Major Depressive Disorder (MDD), are undiagnosed due to unreliable symptom-based criteria and lack of a widely accepted quantifiable diagnostic tool.

Within the medical community, there is a huge push and involvement to leverage machine learning in this task. We are interested in using Structural Magnetic Resonance Imaging (sMRI), which can potentially contain important features such as biomarkers to help diagnosis MDD.

In this paper, we explore the use of Transfer Learning to build a robust deep learning model to predict MDD based on sMRIs. Transfer learning is a methodology that uses a model that has been pre-trained on a different dataset and is used as starting point for a model on a second task. The intuition is that the knowledge learned from the pre-trained model might have insights that can be used on our current problem. Formally, a machine uses the knowledge learned from a prior assignment to increase prediction about a new task in transfer learning.
We aim to explore the use of transfer learning and analyze how various pre-trained models perform on our MDD dataset.


[Report Link](https://rohithravin.github.io/files/dl-mdd.pdf) 📝


<img src='/images/dl-mri-1.png'>

<br>

<img src='/images/dl-mri-2.png'>

<br>

<img src='/images/dl-mri-3.png'>