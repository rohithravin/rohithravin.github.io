---
title: "Identifying Hidden/Indirect Bias in Surgical Outcomes of Colorectal Procedures 👨‍⚕️ 🏥"
excerpt: "Analyze and identify hidden/indirect bias that affected the outcome of colorectal procedures in U.S. hospitals. <br/><br/><img src='/images/colon.png'>"
collection: portfolio
---

[Report Link](https://rohithravin.github.io/files/colon.pdf) 📝

With the world now focused on data, it becomes imperative that hidden biases do not influence the algorithms we use to solve problems. As we develop more complex machine learning methods, we are faced with an increased risk for biased algorithms due to biases that humans cannot necessarily predict from viewing raw data. When these types of algorithms are used in real-world problems (i.e. healthcare industry), they could reinforce societal disparities in the decision-making process based on race, gender, age, and many more factors. Since many of these hidden biases arise from data, we need methods that identify them before applying them to our algorithms. With the use of a Causal Inference Model, we can capture the bias in the data as well as quantify the direct and indirect effect of a factor towards an outcome. In most cases, the biases in an algorithm are based on an indirect factor. My research project with Professor Sunil Prabhakar focused on identifying such factors (direct and indirect) for medical patients that produce a biased outcome to their treatment.

Specifically, for this research project, we are focusing on patients that have undergone colorectal procedures. We picked this subset of patients since colorectal procedures are common across all hospitals, thereby having lots of data within the Cerner dataset to work with. Another reason we picked this subset is that there are specific protocols that have been placed for doctors to follow to reduce the number of surgical infection sites (SSI). While many hospitals adhere to these protocols, many other hospitals don’t, putting them at a disadvantage and significantly differ in the numbers between hospitals within the dataset. One specific example that I will be focusing on with my research is procedures done with minimally invasive (robotic/laparoscopic) techniques vs. open techniques. The former has taken over many urban health centers due to increased funding compared to hospitals in rural cities. Based on this knowledge, I hypothesize that the location of hospitals, more specifically whether they are located in an urban or rural setting, is a bias factor for patients that have undergone colorectal procedures.

<img src='/images/colon-1.png'>

<br>

<img src='/images/colon-2.png'>