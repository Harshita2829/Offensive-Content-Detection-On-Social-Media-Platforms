# Offensive-Content-Detection-On-Social-Media-Platforms
This project presents an offensive content detection system designed to combat offensive language in virtual environments using advanced techniques from natural language processing (NLP), machine learning (ML), and deep learning (DL). The system integrates sophisticated preprocessing, feature extraction, and predictive analytics to identify and block individuals engaging in the posting of offensive and hateful comments. Three diverse datasets are utilized to ensure a comprehensive evaluation of the system's performance.

Dataset Descriptions:
Kaggle Hate Speech and Offensive Language Dataset:
This dataset consists of annotated tweets containing hate speech and offensive language. The annotations provide labels categorizing instances into three distinct classes: hate content (0), offensive content (1), and neither hate nor offensive content (2).
Source: Kaggle.
Faker Generated Synthetic Dataset:
Synthetic tweets are generated using the Faker library, mimicking real-world data. These artificially generated tweets provide a controlled environment for evaluating model performance.
Source: Self-generated using the Faker library, a Python library for generating fake data.
Faker-Kaggle Dataset:
This dataset combines synthetic tweets generated using the Faker library with data closely resembling the Kaggle Hate Speech and Offensive Language Dataset. By merging synthetic and real-world-like data, this dataset provides a hybrid environment for evaluating model performance.
Source: Self-generated by combining synthetic tweets with data resembling the Kaggle dataset.

Key Features:
-Utilizes NLP, ML, and DL techniques for offensive content detection.
-Implements sophisticated preprocessing methods including tokenization, stop words removal, lowercasing, and lemmatization.
-Features TF-IDF and one-hot encoding for effective feature extraction.
-Employs a variety of ML algorithms including Logistic Regression, Naive Bayes, Random Forest, Bagging, and AdaBoost.
-Incorporates DL models such as Artificial Neural Networks (ANN), Convolutional Neural Networks (CNN), Long Short-Term Memory (LSTM), and Bidirectional LSTM (BiLSTM).
-Implements a user blocking system based on predictive analytics for proactive mitigation of offensive comments.

Results:
Kaggle Hate Speech and Offensive Content Dataset:
AdaBoost achieved the highest accuracy of 97%, surpassing other ML and DL models.
CNN demonstrated competitive accuracy, achieving 93%.
Faker Generated Synthetic Dataset:
Random Forest and AdaBoost emerged as the top-performing ML models, achieving 93% accuracy.
Among DL models, ANN achieved 89% accuracy.
Faker-Kaggle Generated Dataset:
Random Forest maintained strong performance, achieving 87% accuracy.
Among DL models, CNN achieved 87% accuracy.

--Across all datasets, AdaBoost achieved the highest accuracy of 97% in the Kaggle Hate Speech and Offensive Content Dataset. Random Forest and AdaBoost demonstrated robust generalization in synthetic datasets, achieving accuracies of 93% and 89% respectively. CNN and LSTM models performed competitively across datasets, with accuracies ranging from 88% to 93%.
