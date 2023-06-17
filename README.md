# Heartattack
![heartbeat-monitor-concept-3](https://github.com/AkshayRamakrishnann/Multiple-Sclerosis-Disease/assets/111365771/2a602b11-a519-42f9-a899-5f31a984ca66)

# Introduction
The goal of this project is to predict heart attacks using machine learning techniques. In order to achieve this, we have utilized the Heart Attack dataset obtained from Kaggle. Heart attacks are a critical health issue worldwide, and accurate prediction models can assist in early detection and prevention.

# About the Dataset
The Heart Attack dataset contains various attributes related to a person's health and lifestyle factors that may contribute to the risk of a heart attack. The dataset includes information such as age, gender, cholesterol levels, blood pressure, and other relevant features. It provides a valuable resource for training and evaluating machine learning models for heart attack prediction.

# OneAPI and OneDAL
OneAPI is an industry initiative that aims to simplify development across diverse hardware architectures. It provides a unified programming model and a set of libraries for cross-platform and performance-portable programming. OneDAL (OneAPI Data Analytics Library) is a component of OneAPI that offers a comprehensive collection of algorithms and techniques for data analysis and machine learning.

In this project, we leverage OneDAL to implement and optimize the machine learning models used for heart attack prediction. OneDAL provides efficient implementations of common algorithms, allowing us to leverage the power of hardware acceleration and achieve faster execution times.

# Methodology
Data Preprocessing: We started by performing data preprocessing tasks such as handling missing values, normalizing numerical features, and encoding categorical variables.

Model Selection: We evaluated multiple machine learning models for heart attack prediction. The models we considered include Logistic Regression, K-Nearest Neighbors (KNN) Classifier, Support Vector Machine (SVM), Decision Tree Classifier, and Random Forest Classifier.

Training and Evaluation: We trained each model on a portion of the dataset and evaluated its performance using appropriate metrics such as accuracy. We used cross-validation techniques to ensure robust evaluation results.

OneDAL Integration: To leverage the power of hardware acceleration and optimize the models, we integrated OneDAL into the training and inference pipeline. This allowed us to take advantage of efficient algorithms and parallel processing capabilities.

# Results
After training and evaluating the models, we obtained the following results:

Model	Accuracy (%)	Execution Time (seconds)
Logistic Regression	90.16	0.0191
K-Nearest Neighbors (KNN)	88.52	0.01269
Support Vector Machine (SVM)	90.16	0.01183
Decision Tree Classifier	81.97	0.00603
Random Forest Classifier	91.8	0.40131
The table above presents the accuracy achieved by each model in predicting heart attacks, as well as the corresponding execution times. The models were evaluated on the Heart Attack dataset using appropriate evaluation metrics.

![accco](https://github.com/AkshayRamakrishnann/Multiple-Sclerosis-Disease/assets/111365771/35dcbc8f-ad23-4453-9ea1-60a9b49429d6)
The results indicate that the Random Forest Classifier achieved the highest accuracy of 91.8%, while the Decision Tree Classifier had the lowest accuracy at 81.97%.

![runtimeco](https://github.com/AkshayRamakrishnann/Multiple-Sclerosis-Disease/assets/111365771/bd564017-390b-49c6-ab45-3f81767fdf69)
In terms of execution time, the Decision Tree Classifier was the fastest with 0.00603 seconds, whereas the Random Forest Classifier took the longest with 0.40131 seconds.

It's important to note that the execution times mentioned here are specific to the dataset and environment used for this project. Actual execution times may vary depending on the hardware, dataset size, and other factors.

# Conclusion
In conclusion, we have successfully developed and evaluated machine learning models for heart attack prediction using the Heart Attack dataset. The results indicate that the Random Forest Classifier achieved the highest accuracy of 91.8%. By leveraging OneDAL, we were able to optimize the models and improve execution times, making the predictions more efficient.

# Future Work
There are several avenues for future work in this domain. Some potential areas to explore include:

Further optimization using hardware-specific features and optimizations provided by OneDAL.
Exploring ensemble methods to improve prediction accuracy.
Incorporating additional relevant datasets to enhance the models' predictive capabilities.
Conducting more extensive feature engineering to identify critical predictors for heart attack risk.
Deploying the models in a real-world setting and evaluating their performance with new data.
By pursuing these directions, we can continue to refine and enhance the accuracy and efficiency of heart attack prediction models, ultimately contributing to early detection and prevention efforts.
