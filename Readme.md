# Divergent Results in Replicating 'SCADA System Testbed for Cybersecurity Research Using Machine Learning Approach'

As a student, I attempted to replicate the experiment presented in [the article](https://arxiv.org/abs/1904.00753) titled "SCADA System Testbed for Cybersecurity Research Using Machine Learning Approach," published in 2018. While I found that the results for the algorithms Decision Tree, Random Forest, and Logistic Regression were similar to those reported by the researchers, the accuracy obtained for Naive Bayes was significantly lower, which is why it was not included.

Additionally, I found it puzzling that the KNN algorithm was used in a dataset without feature scaling.

The article acknowledged that the dataset used in the study was unbalanced, yet the researchers still used accuracy as the primary performance metric. In my replication attempt, I used "f1_score" as a metric to account for the dataset's imbalance. However, it was unclear to me if the evaluation metric used in Figure 8 considered the imbalance in the dataset.


:man_technologist: You can see the notebook here: [Kaggle](https://www.kaggle.com/victorzeland/scada-cybersegurity) 
