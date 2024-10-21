# References

Citations of various useful and interesting papers and articles. In no particular order.


## `scikit-learn` contributors
- The `scikit-learn` contributors
- **Common pitfalls and recommended practices**
- https://scikit-learn.org/stable/common_pitfalls.html
- The purpose of this chapter is to illustrate some common pitfalls and anti-patterns that occur when using scikit-learn. It provides examples of what not to do, along with a corresponding correct example.


## Lones 2023
- Michael A. Lones
- **How to avoid machine learning pitfalls: a guide for academic researchers**
- https://doi.org/10.48550/arXiv.2108.02497
- Abstract. This document is a concise outline of some of the common mistakes that occur when using machine learning, and what can be done to avoid them. Whilst it should be accessible to anyone with a basic understanding of machine learning techniques, it was originally written for research students, and focuses on issues that are of particular concern within academic research, such as the need to do rigorous comparisons and reach valid conclusions. It covers five stages of the machine learning process: what to do before model building, how to reliably build models, how to robustly evaluate models, how to compare models fairly, and how to report results. 


## van Giffen et al 2022
- Benjamin van Giffen, Dennis Herhausen, Tobias Fahse
- **Overcoming the pitfalls and perils of algorithms: A classification of machine learning biases and mitigation methods**
- _Journal of Business Research_ **144**, pages 93-106.
- https://doi.org/10.1016/j.jbusres.2022.01.076. (https://www.sciencedirect.com/science/article/pii/S0148296322000881)
- Abstract: Over the last decade, the importance of machine learning increased dramatically in business and marketing. However, when machine learning is used for decision-making, bias rooted in unrepresentative datasets, inadequate models, weak algorithm designs, or human stereotypes can lead to low performance and unfair decisions, resulting in financial, social, and reputational losses. This paper offers a systematic, interdisciplinary literature review of machine learning biases as well as methods to avoid and mitigate these biases. We identified eight distinct machine learning biases, summarized these biases in the cross-industry standard process for data mining to account for all phases of machine learning projects, and outline twenty-four mitigation methods. We further contextualize these biases in a real-world case study and illustrate adequate mitigation strategies. These insights synthesize the literature on machine learning biases in a concise manner and point to the importance of human judgment for machine learning algorithms.
- Keywords: Machine learning; Artificial intelligence; Bias; Mitigation methods; Case study


## Mitchell et al, 2018
- Margaret Mitchell, Simone Wu, Andrew Zaldivar, Parker Barnes, Lucy Vasserman, Ben Hutchinson, Elena Spitzer, Inioluwa Deborah Raji, Timnit Gebru
- **Model Cards for Model Reporting**
- _FAT '19: Proceedings of the Conference on Fairness, Accountability, and Transparency_, January 2019, p 220–229.
- https://doi.org/10.1145/3287560.3287596
- Abstract. Trained machine learning models are increasingly used to perform high-impact tasks in areas such as law enforcement, medicine, education, and employment. In order to clarify the intended use cases of machine learning models and minimize their usage in contexts for which they are not well suited, we recommend that released models be accompanied by documentation detailing their performance characteristics. In this paper, we propose a framework that we call model cards, to encourage such transparent model reporting. Model cards are short documents accompanying trained machine learning models that provide benchmarked evaluation in a variety of conditions, such as across different cultural, demographic, or phenotypic groups (e.g., race, geographic location, sex, Fitzpatrick skin type) and intersectional groups (e.g., age and race, or sex and Fitzpatrick skin type) that are relevant to the intended application domains. Model cards also disclose the context in which models are intended to be used, details of the performance evaluation procedures, and other relevant information. While we focus primarily on human-centered machine learning models in the application fields of computer vision and natural language processing, this framework can be used to document any trained machine learning model. To solidify the concept, we provide cards for two supervised models: One trained to detect smiling faces in images, and one trained to detect toxic comments in text. We propose model cards as a step towards the responsible democratization of machine learning and related AI technology, increasing transparency into how well AI technology works. We hope this work encourages those releasing trained machine learning models to accompany model releases with similar detailed evaluation numbers and other relevant documentation. 


## Koçak, 2022
- Burak Koçak
- **Key concepts, common pitfalls, and best practices in artificial intelligence and machine learning: focus on radiomics**
- _Diagn Interv Radiol_ **28**(5), September 2022, p 450–462.
- https://doi.org/10.5152/dir.2022.211297
- Abstract. Artificial intelligence (AI) and machine learning (ML) are increasingly used in radiology research to deal with large and complex imaging data sets. Nowadays, ML tools have become easily accessible to anyone. Such a low threshold to accessibility might lead to inappropriate usage and misinterpretation, without a clear intention. Therefore, ensuring methodological rigor is of paramount importance. Getting closer to the real-world clinical implementation of AI, a basic understanding of the main concepts should be a must for every radiology professional. In this respect, simplified explanations of the key concepts along with pitfalls and recommendations would be helpful for general radiology community to develop and improve their AI mindset. In this work, 22 key issues are reviewed within 3 categories: pre-modeling, modeling, and post-modeling. Firstly, the concept is shortly defined for each issue. Then, related common pitfalls and best practices are provided. Specifically, the issues included in this article are validity of the scientific question, unrepresentative samples, sample size, missing data, quality of reference standard, batch effect, reliability of features, feature scaling, multi-collinearity, class imbalance, data and target leakage, high-dimensional data, optimization, overfitting, generalization, performance metrics, clinical utility, comparison with conventional statistical and clinical methods, interpretability and explainability, randomness, transparent reporting, and sharing data.


## Salzburg 1997
- Salzburg, Steven L
- **On Comparing Classifiers: Pitfalls to Avoid and a Recommended Approach**
- _Data Mining and Knowledge Discovery_ **1**, p 317–327.
- http://www.cs.ru.nl/~tomh/onderwijs/lrs/lrs_files/salzberg97comparing.pdf
- Abstract. An important component of many data mining projects is finding a good classification algorithm,
a process that requires very careful thought about experimental design. If not done very carefully, comparative
studies of classification and other types of algorithms can easily result in statistically invalid conclusions. This
is especially true when one is using data mining techniques to analyze very large databases, which inevitably
contain some statistically unlikely data. This paper describes several phenomena that can, if ignored, invalidate
an experimental comparison. These phenomena and the conclusions that follow apply not only to classification,
but to computational experiments in almost any aspect of data mining. The paper also discusses why comparative
analysis is more important in evaluating some types of algorithms than for others, and provides some suggestions
about how to avoid the pitfalls suffered by many experimental studies.
- Keywords: classification, comparative studies, statistical method


## Yang et al 2022
- Jingkang Yang, Kaiyang Zhou, Yixuan Li, Ziwei Liu
- **Generalized Out-of-Distribution Detection: A Survey**
- https://arxiv.org/abs/2110.11334
- Abstract. Out-of-distribution (OOD) detection is critical to ensuring the reliability and safety of machine learning systems. For instance, in autonomous driving, we would like the driving system to issue an alert and hand over the control to humans when it detects unusual scenes or objects that it has never seen during training time and cannot make a safe decision. The term, OOD detection, first emerged in 2017 and since then has received increasing attention from the research community, leading to a plethora of methods developed, ranging from classification-based to density-based to distance-based ones. Meanwhile, several other problems, including anomaly detection (AD), novelty detection (ND), open set recognition (OSR), and outlier detection (OD), are closely related to OOD detection in terms of motivation and methodology. Despite common goals, these topics develop in isolation, and their subtle differences in definition and problem setting often confuse readers and practitioners. In this survey, we first present a unified framework called generalized OOD detection, which encompasses the five aforementioned problems, i.e., AD, ND, OSR, OOD detection, and OD. Under our framework, these five problems can be seen as special cases or sub-tasks, and are easier to distinguish. We then review each of these five areas by summarizing their recent technical developments, with a special focus on OOD detection methodologies. We conclude this survey with open challenges and potential research directions. 


## Mozer et al
- Michael C. Mozer, Robert Dodier, Cesar Guerra, Richard Wolniewicz, Lian Yan, Michael Colagrosso, David Grimes
- **Prediction and classification: Pitfalls for the unwary**
- https://home.cs.colorado.edu/~mozer/Research/Selected%20Publications/white-paper3.html
- Short white paper from a software company; still worth reading.
