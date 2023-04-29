---
title: "Self-Evaluation Using Zero-shot Learning 🤖"
excerpt: "The goal of this project is to create a system that utilizes a self-evaluation policy to determine whether a task has been completed, and self-identify errors made during task execution without a human evaluator. <br/><br/><img src='/images/robot.png'>"
collection: portfolio
---

[Report Link](https://rohithravin.github.io/files/zero-shot-learning.pdf) 📝

The field of robotics has gone through rapid advancements due to advances in computing as well as learning techniques. Particularly in recent years, the emergence of large language models trained on massive web corpus has revolutionized the way we can interpret natural language instructions and potentially execute tasks on robots. The paper ‘Do As I Can, Not As I Say’ by M Ahn et al, bridges the gap between large language models and robotic language processing by providing a real-world grounding to help the robot better understand and execute tasks. This method for task execution requires human evaluators to monitor the robot and make sure it is operating, especially to gauge success as it moves through a long-horizon task.

The goal of this project is to create a system that utilizes a self-evaluation policy to determine whether a task has been completed, and self-identify errors made during task execution without a human evaluator. Our idea is to use visual language models (VLM) and large-language models (LLM) to self-evaluate action completion during each step of the task. This will allow the robot to self-evaluate whether it is correctly executing a task as well as notice any errors it makes as it completes each step of a task sequence. 

<img src='/images/zero-shot-fig1.png'>

<br>

<img src='/images/zero-shot-fig4.png'>