---
title: "Explainable AI - Identifying Model Forms 🧪"
excerpt: "We propose a methodology that uses an ontology—a knowledge base on chemical engineering model forms, relationships, and fundamental laws—in tangent with a novel search algorithm that structurally and contextually matches an equation to its corresponding first-principle definition. <br/><br/><img src='/images/xai.png'>"
collection: portfolio
---

[Report Link](https://rohithravin.github.io/files/xai.pdf) 📝

Nowadays, machine learning is used in almost every industry. The abundance of data has allowed machine learning and artificial intelligence to prosper. Many of the models that are used identify as black-box models. Black-box models have high accuracy and can obtain a good fit between input and output variables. However, the name “black-box” arises from not being able to quantitatively identify the relationship and mechanisms between the input and output variables. This is visibility apparent in neural networks. These models do amazing in computer vision, natural language processing, and game-playing. Yet when we attempt to understand why the model does so well, all we get are tensors of weights. To the human eye this means nothing. With respect to chemical engineering systems, black-box models are not able to identify and report back the physicochemical mechanisms. Engineering a methodology that can efficiently identify the underlying physicochemical mechanisms of the data is the current challenge within the industry. This is the premise of our problem, and we hope to tackle an aspect of that problem.

Currently, there are many researchers tackling this problem. One in particular is Professor Venkat Venkatasubramanian, Abhishek Sivaram, and Arijit Chakraborty and their machine learning system called AI-Darwin[2]. AI-Darwin automatically discovers mechanism-based models from data for non-linear parametric systems. In simple terms, their system is able to extract the underlying chemical engineering fundamental principles and laws from the data and output a single equation. This equation describes the data based on the relationships between variables. The system however does not identify what specific model form the equation represents.

Our work this semester focuses on identifying the equations that AI-Darwin generates from the equation. We want to be able to identify the equation to a specific chemical engineering model form, the variables used, and the context of each variable. In order to accomplish this task, we first need to develop a knowledge based on the inner workings of chemical engineering and the domain's fundamental laws. We use an ontology for this purpose. From the ontology, we can search through the known model forms and identify which one most resembles the input equation output form AI-Darwin. Our methodology that we propose utilizes an ontology, constraint satisfaction and search graph traversal to identify the correct model form.

<img src='/images/xai-1.png'>

<br>

<img src='/images/xai-2.png'>