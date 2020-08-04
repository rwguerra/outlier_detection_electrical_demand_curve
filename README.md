# DETECÇÃO DE OUTLIERS EM CURVA DE DEMANDA USANDO TÉCNICAS DE APRENDIZAGEM NÃO SUPERVISIONADA E DEEP LEARNING

Trabalho de Conclusão de Curso apresentado à Coordenação do Curso de Engenharia Elétrica da Universidade Federal da Paraíba como exigência para a obtenção do título de Bacharel em Engenharia Elétrica.

#### ABSTRACT

The detection of outliers is an important problem that has been researched in several research areas and application domains. Many outlier detection techniques have been
developed specifically for certain application domains, while others are more generic. Outliers can be of different types, in this work we will address outliers of the type punctual global) and contextual. The present work aims to detect these failures that occurred during the measurement or communication, and to correct these failures in order to give more reliability to the set. The study was carried out using some clustering algorithms to label outliers (clustering), KNN classification algorithm for detecting outliers (classification) and Autoencoders deep learning algorithms. For the correction of outliers, linear interpolation is used. Comparisons of results between techniques such as Z-Score, Modified Z-Score, K-Means, C-Means, Autoencoders and Sparsed Autoencoders are also provided, and these comparisons are evaluated according to the metrics used in the literature. In order to verify the performance of the proposed techniques, active power data from an energy substation in the state of Paraíba were used. It is expected that this research will provide a better understanding of the different directions in which the research was carried out on this topic and how the techniques developed in an area can be applied in the domains for which they were not intended.


#### In this repository you will find:

1. Code used to produce thesis models and results.

#### Language Python 3.7 and modules:

scikit-learn                       0.22.1
Keras                              2.2.4
tensorflow                         1.14.0
pandas                             1.0.1  
numpy                              1.18.1
matplotlib                         3.1.3
seaborn                            0.10.0
scipy                              1.4.1
fuzzy-c-means                      0.0.6
