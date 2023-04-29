---
title: "Predicting Plant Sensitivity Based on Root System Responses to Phytohormones in Arabidopsis using Transfer Learning 🌱 🧬"
excerpt: "We propose a new architecture based on transfer learning and SNP data to describe the sensitivity of arabidopsis accessions in response to phytohormone perturbation. <br/><br/><img src='/images/snp.png'>"
collection: portfolio
---

[Report Link](https://rohithravin.github.io/files/snp.pdf) 📝

Currently, there is an abundance of data related to how a plant’s root system architecture (RSA) responds to various phytohormones. RSAs are both easy to perturb with molecules of interest and of high adaptive relevance as the RSA provides the framework for plant growth and productivity. Phytohormonal pathways are the driving factor for RSA adaptation, allowing the plant to optimize its stability and uptake of vital nutrients. In a paper that analyzed 192 Arabidopsis accessions, it was observed that all Arabidopsis RSAs responded to phytohormones in the same way, however the degree to which each accession responded was dependent on its individual genotype. Understanding the magnitude of a given plant’s RSA response to phytohormone perturbation gives us an understanding of how sensitive that plant is to its own phytohormonal pathway, and thus its ability to optimize its RSA for its environment. The RSA is complex and can be described by 10 measurable phenotypes including root length, root branching, root mass density etc.

While there are various machine learning methods that have shown efficacy in accurately predicting each of these phenotypes, we wish to take a more holistic approach that incorporates all the measured phenotypes in predicting an accession’s sensitivity. We aim to use SNP data from each accession to predict the various root phenotypes and finally compute an overall fitness score. Formally, the biological question we aim to answer goes as follows - Can we predict the overall evolutionary sensitivity of an accession based on root system responses to phytohormones given the respective SNPs?

With respect to our methodology, we plan to develop a supervised model that uses a transfer learning approach. We are interested in building a model that uses pre-trained subnetworks to (i.) predict the accession’s RSA based on the SNP and (ii.) then use those intermediary values to predict the overall sensitivity (singular output). In our proposed architecture, the intermediary outputs are created independently from one another.

<img src='/images/snp-1.png'>

<br>

<img src='/images/snp-2.png'>
