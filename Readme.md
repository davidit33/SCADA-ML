# Replicating "SCADA Project System Testbed for Cybersecurity Research Using Machine Learning Approach"

As part of my studies, I tried to replicate the same experiment shown in this article [this article](https://arxiv.org/abs/1904.00753), titled "SCADA System Testbed for Cybersecurity Research Using Machine Learning Approach", and published in 2018.

The results obtained in my Notebook were very similar to those of the researchers, for: the algorithms: Decision Tree, Random Forest and Logistic Regression, however the results for Naives Bayes are not included because the accuracy obtained was much lower, I do not understand as in the article such a high accuracy was achieved using this last algorithm, I also do not understand how the KNN algorithm was used in a dataset without previously applying feature scaling.
It is mentioned in the article that "As shown in Table 5, our dataset is unbalanced. Therefore, accuracy is not the ideal measure to evaluate performance [33]", which I totally agree, that's why in my notebook I used "f1_score" as a metric to evaluate the accuracy of my model, however in Figure 8, it is not clear to me if an evaluation metric was used that take into account the imbalance in the dataset.
One of the questions I get is: Why did the model perform so well? 
You can see the notebook here: [Kaggle](https://www.kaggle.com/victorzeland/scada-cybersegurity) 
Please contact me and help me learn, give me your conclusions about this Notebook.
[Contact](https://davidtamayo.netlify.app/)
 