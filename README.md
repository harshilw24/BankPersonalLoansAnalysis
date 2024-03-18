## Personal Loan Analysis for Banks

### Description
The Finance Project involves analyzing customer data from a bank to predict the likelihood of a customer accepting a personal loan offer. The dataset contains information on customer demographics, their relationship with the bank, and their response to previous loan campaigns. The goal is to build a predictive model using supervised learning techniques to identify customers who are likely to accept a personal loan offer, aiding the bank's marketing efforts.

### Context
Thera Bank aims to convert its liability customers into personal loan customers while retaining them as depositors. With a successful conversion rate in a previous campaign, the bank's retail marketing department seeks to improve target marketing effectiveness with minimal budget.

### Objective
The primary objective is to predict the likelihood of a liability customer accepting a personal loan offer. This involves building a model using supervised learning methods such as Logistic Regression, K-Nearest Neighbors (KNN), and Naive Bayes Algorithm.

### Methodology
1. **Data Exploration**: Understanding the dataset's features, distributions, and correlations.
2. **Data Preprocessing**: Handling missing values, fixing errors, and scaling attributes.
3. **Model Building**: Utilizing Logistic Regression, KNN, and Naive Bayes classifiers.
4. **Model Evaluation**: Assessing model performance through accuracy metrics and confusion matrices.
5. **Optimization**: Iteratively refining models by considering feature inclusion, scaling, and algorithm selection.

### Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

### Results
- Logistic Regression achieved an accuracy of 94.60% with the 'Experience' feature included.
- KNN yielded an accuracy of 90.93% without the 'Experience' feature.
- Naive Bayes demonstrated comparable performance with and without the 'Experience' feature, achieving an accuracy of approximately 90%.

### Conclusion
- Logistic Regression showed the highest accuracy among the models, suggesting its suitability for predicting personal loan acceptance.
- The inclusion of the 'Experience' feature slightly improved model performance, indicating its relevance in prediction.
- Further optimization, such as feature engineering and ensemble methods, could enhance model accuracy and robustness.

---

### Resume Line (XYZ Format)
Implemented supervised learning algorithms including Logistic Regression, K-Nearest Neighbors, and Naive Bayes to predict personal loan acceptance, achieving up to 94.60% accuracy on real-world banking data.
