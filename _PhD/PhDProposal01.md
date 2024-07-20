---
title: "Signal Quality Monitoring and Assessment for Satellite Navigation Systems using Machine Learning Techniques"
collection: PhD 
permalink: /PhD/PhDProposal01
excerpt: 'This is a reseach proposal in accordance with my application to join **The Aerospace Information Research Institute, Chinese Academy of Science**'
---

## Abstract:

 Signal quality monitoring (SQM) is a crucial task for ensuring the reliability and accuracy of satellite navigation systems, such as GPS, GLONASS, Galileo, and BeiDou. SQM aims to detect and mitigate the effects of signal anomalies, such as signal power fluctuations, cross-correlation, cycle slips, excessive acceleration, code-carrier divergence, and signal deformation. These anomalies can be caused by various factors, such as satellite oscillator failures, ionospheric scintillation, multipath, interference, and spoofing. Traditional SQM methods rely on predefined thresholds, models, or rules to identify and exclude anomalous signals. However, these methods have limitations in terms of adaptability, scalability, and robustness, especially in complex and dynamic environments. Machine learning (ML) techniques offer a promising alternative for SQM, as they can learn from data and automatically adjust to different scenarios and conditions. ML techniques can also leverage the availability of multiple signal quality indicators (QIs), such as carrier-to-noise ratio, pseudorange standard deviation, elevation angle, and azimuth angle, to improve the performance of SQM. The main objective of this research proposal is to develop and evaluate novel ML-based SQM methods for satellite navigation systems, and to compare them with existing methods in terms of accuracy, efficiency, and reliability.


## Research Questions: 

   1. What are the most suitable ML techniques for SQM, and how can they be applied to different types of signal anomalies?
   2. How can multiple QIs be effectively integrated and utilized by ML techniques for SQM?
   3. How can the performance of ML-based SQM methods be evaluated and validated using real-world data and scenarios?
  

## Literature Review: 

The [Article](https://satellite-navigation.springeropen.com/articles/10.1186/s43020-023-00101-w) by Zhang et al. proposes a cost-effective NLOS impact mitigation approach using only GNSS receivers and ML techniques. The paper uses a support vector machine (SVM) classifier to distinguish between LOS and NLOS signals, and a weighted least squares (WLS) algorithm to estimate the user position. The paper evaluates the proposed approach using real-world data collected in the built environment of Shanghai, China. The paper shows that the proposed approach can achieve a positioning accuracy of 3.5 m in the horizontal dimension and 6.5 m in the vertical dimension, which is significantly better than the conventional approach. The paper also compares the performance of different ML techniques, such as decision tree, random forest, k-nearest neighbor, and naive Bayes, and finds that SVM has the best performance for SQM. The paper contributes to the literature by providing a novel and effective solution for NLOS impact mitigation using only GNSS receivers and ML techniques, and by conducting a comprehensive and comparative experiment in the built environment.
A[Book](https://ieeexplore.ieee.org/document/9305069) titled as GNSS Signal Quality Monitoring provides a comprehensive and authoritative reference on the topic of SQM. This book explains the importance, requirements, and current systems of SQM, and summarizes the SQM algorithms and methods for six parameters: signal power, cross-correlation, cycle slips, excessive acceleration, code-carrier divergence, and signal deformation. The book also provides examples and case studies of SQM applications in various domains, such as aviation, maritime, land, and space. The book contributes to the literature by providing a systematic and in-depth overview of the theory and practice of SQM, and by covering the latest developments and challenges in the field.


## Methodology: 

  **1**. Collect an extensive datasets of GNSS signals from GNSS data centers, international GNSS service Providers, GNSS Recievers and other data sources. 
  **2**. Preprocess the collected data and perform an extensive analysis. Do an indepth study of existing SQM models and try to design a new model that can outperform the existing one.
  **3**. Have done an indepth research in analysing the collected data, existing models and design a new model, perform an extensive feture engineering on the collected data to fit the designed model.
  **4**. Model training and testing 
  **5**. Performance evaluations and Reworks.

## Expected Outcomes:
  1.  Developing novel and effective ML-based SQM methods for satellite navigation systems, and  demonstrating their advantages over existing methods.
  2.  Enhancing the reliability and accuracy of satellite navigation systems, and improving the user experience and satisfaction.
  3.  Providing valuable insights and recommendations for future research and development in SQM and ML techniques.