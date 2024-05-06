# Amazon_Customer_semantic_analysis_using_NLP
The paper focuses on developing a sophisticated classification model for customer reviews by leveraging Natural Language Processing (NLP) techniques. The main contribution is the Universal Language Model Fine-tuning (ULMFiT) method, which enhances text classification tasks by efficiently fine-tuning pre-trained models. The study aims to improve sentiment analysis in customer reviews to help businesses understand and analyze customer sentiments effectively. It introduces techniques like discriminative fine-tuning, slanted triangular learning rates, and gradual unfreezing to achieve significant error reduction in text classification tasks. The research also emphasizes the importance of feature engineering, cross-validation, hyperparameter tuning, and error analysis to enhance model performance. Furthermore, the study suggests future research directions, such as exploring the generalizability of ULMFiT in various NLP tasks and assessing the impact of different pretraining corpora on fine-tuning performance.

the dataset is collected from the Kaggle and we have performed some preprocessing and data cleaning to remove the Nan Values.
We have used the Bert Tokenisation to tokenise the reviews of the products and tested the same data with different classifiers.

Classifier Models	Accuracy
KNN	0.68
Gaussian Naïve Bayes	0.73
Multinomial Naïve Bayes	0.69
Decision Tree	0.68
Random Forest	0.67
Logistic Regression	0.70
Support Vector machine	0.72
Multi-layer Perceptron (MLP)	0.75
Voting Classifier (Hard)	0.74
Voting Classifier (Soft)	0.77

these are the final results for each classifier.
