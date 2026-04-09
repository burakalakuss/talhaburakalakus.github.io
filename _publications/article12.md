---
title: "A Novel Repetition Frequency-Based DNA Encoding Scheme to Predict Human and Mouse DNA Enhancers with Deep Learning"
collection: publications
permalink: /publication/article12
excerpt: 'This study proposes a novel DNA encoding scheme for the prediction of DNA enhancers using a BiLSTM-based deep learning model. Different encoding methods, including EIIP, integer, and atomic number representations, are compared across two classification scenarios.'
date: 2023-05-23
venue: 'Biomimetics'
paperurl: 'https://www.mdpi.com/2313-7673/8/2/218'
citation: 'Alakuş, T. B. (2023a). A Novel Repetition Frequency-Based DNA Encoding Scheme to Predict Human and Mouse DNA Enhancers with Deep Learning. Biomimetics, 8(2), 218.'
---

## Abstract
Recent studies have shown that DNA enhancers have an important role in the regulation of gene expression. 
They are responsible for different important biological elements and processes such as development, homeostasis, and embryogenesis. 
However, experimental prediction of these DNA enhancers is time-consuming and costly as it requires laboratory work. 
Therefore, researchers started to look for alternative ways and started to apply computation-based deep learning algorithms to this field. 
Yet, the inconsistency and unsuccessful prediction performance of computational-based approaches among various cell lines led to the investigation of these approaches as well. 
Therefore, in this study, a novel DNA encoding scheme was proposed, and solutions were sought to the problems mentioned and DNA enhancers were predicted with BiLSTM. The study consisted of four different stages for two scenarios. 
In the first stage, DNA enhancer data were obtained. 
In the second stage, DNA sequences were converted to numerical representations by both the proposed encoding scheme and various DNA encoding schemes including EIIP, integer number, and atomic number. 
In the third stage, the BiLSTM model was designed, and the data were classified. 
In the final stage, the performance of DNA encoding schemes was determined by accuracy, precision, recall, F1-score, CSI, MCC, G-mean, Kappa coefficient, and AUC scores.
In the first scenario, it was determined whether the DNA enhancers belonged to humans or mice. 
As a result of the prediction process, the highest performance was achieved with the proposed DNA encoding scheme, and an accuracy of 92.16% and an AUC score of 0.85 were calculated, respectively. 
The closest accuracy score to the proposed scheme was obtained with the EIIP DNA encoding scheme and the result was observed as 89.14%. The AUC score of this scheme was measured as 0.87.
Among the remaining DNA encoding schemes, the atomic number showed an accuracy score of 86.61%, while this rate decreased to 76.96% with the integer scheme. 
The AUC values of these schemes were 0.84 and 0.82, respectively. In the second scenario, it was determined whether there was a DNA enhancer and, if so, it was decided to which species this enhancer belonged. 
In this scenario, the highest accuracy score was obtained with the proposed DNA encoding scheme and the result was 84.59%. 
Moreover, the AUC score of the proposed scheme was determined as 0.92. EIIP and integer DNA encoding schemes showed accuracy scores of 77.80% and 73.68%, respectively, while their AUC scores were close to 0.90. 
The most ineffective prediction was performed with the atomic number and the accuracy score of this scheme was calculated as 68.27%. 
Finally, the AUC score of this scheme was 0.81. At the end of the study, it was observed that the proposed DNA encoding scheme was successful and effective in predicting DNA enhancers.
