# Bank-Term-Deposit-Subscription-Project
Develop a model that predicts bank customers subscription to a term deposit or not 
●	Develop a model that predicts bank customers subscription to a term deposit or not
●	Use hyperparameter optimization to improve the model
●	Build model using traditional machine learning models and Feed Forward Neural Network
●	Compare different evaluation metrics

Conclusion
The main objectives of the project was to train a model using both Feed Forward Neural Network architecture and different traditional Machine Learning algorithms and afterwards optimize the Neural Network model using any Hyperparameter Optimization technique, herein Random Search was selected. During exploration of the dataset, it was observed that the target variable was imbalanced and the need to further expand the project scope was born. In so doing, a dedication to try the same experiments on the same dataset but an oversampled equivalent proved insightful.
While experimenting with the imbalance data, it is observed that while the training accuracy / loss is not significantly different from the validation accuracy / loss, the training process plot clearly shows that, prior to arriving at these scores, the model underwent a drastic change in terms of variance.
The training process graphic, on the other hand, depicts the impact of working with balanced data on model performance. This distinction may be seen in the training accuracy / loss, validation accuracy / loss, and training plot. Based on these results, we may infer that the oversampled optimized model will outperform the models built using the original dataset.
Also, it can be seen from the above table that the hyperparameter optimized Feed Forward Neural Network achieved a better overall performance than before it was optimized with an accuracy, precision and recall score of 92%.
We built different classification models such as Logistic regression model, Decision tree model, Naive bayes model and Support Vector Machine model. The models were bult with an imbalanced and balanced dataset. We showed that Feed forward neural network and traditional Machine learning models performance can be substantially improved and more reliable when the data is balanced. Also, from the model comparisons, we showed that a Feed Forward Neural Network had a better overall performance than the traditional machine learning models when the data is imbalanced, but the traditional machine learning models performed better when the data was balanced.

Recommendation
4.1 Recommendations
This experiment was carried out using the same Feed Forward neural network design and parameters, and while the parameters varied after optimization, the learning rate and activation functions (ReLu and Sigmoid) remained remarkably consistent. The same project may effectively be carried out precisely utilizing alternative learning rates, activation functions, batch size, and Hyperparameter optimization technique for further study and research, and the project execution can focus on the health sector
