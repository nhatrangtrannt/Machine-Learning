# Machine-Learning
**Name: Nha Tran**
---

This notebook is where I practice projects related to ML with the topics as below:

1. **Loan Eligibility Prediction**
    - Understand factors affecting the loan approval
    - Read csv file
      Visualize data and relationship between features (numerical vs categorical)
    - Boxplot, countplot, distribution plot, stacked bar plot, and heatmap
    - Data cleaning (encode categorical features and fill null values by mode and median)
    - Using sklearn library
    - Fit the following ML models (Logistic Regression, Decision Tree, Linear Discriminant Analysis, Random Forest Classifier, Support Vector Classifier, KNeighbors Classifier, and Naive Bayes)

2. **Bayesian Network & Naive Bayes Text Classification (Spam Detection)**
    - The main purpose of this experimental studies is to learn about Naïve Bayes Text Classification and Transfer learning by implementing some preprocessing techniques to see the model performance and evaluating different classification methods.
    - Use scikit-learn library to import libraries that have these pre-built classifiers such as:
        ●	SVC – Support Vector Machine Classifier
        ●	Multinomial Naïve Bayes Classifier
        ●	Random Forest Classifier
        ●	K-nearest Neighbors Classifier
        ●	Decision Tree Classifier
        ●	Logistic Regression Classifier
    - Removing punctuations, lowercasing the text, removing stop words, lemmatization, and stemming are the preprocessing techniques that we will be using in this paper to see how it affects the performance and evaluate the impact of different algorithms to the testing set (SMS).
    - Training set: Email (75% of Email dataset); Testing set: Email (25% of Email dataset) and SMS dataset
    - To conclude, I have some thoughts that I would like to share:
        ●	MultinomialNB performed very well among other classifiers in terms of performance measures and speed.
        ●	Because of the imbalanced dataset, we did not achieve a high accuracy for all the models
        ●	If I have more time, I will try to report Recall because for this particular spam detection. I feel like this metrics is also important since it is about matter of security, so I’d rather to catch some false detection than letting the spam stays out there. 
        ●	I notice that the performance in training set (Email) and the testing set (Email) have a very high accuracy because they all came from the Email dataset. However, when it comes to SMS dataset, the dataset was not a good replica of the training set, so when we did a transfer learning, it did not perform very well. 
        ●	Lastly, If I have plenty of time, I would retrain the model with a new dataset that is similar to SMS dataset and research in-depth what makes SMS and Email different, what factors, which techniques I should use to solve that, and how the content in each dataset is different when comparing to other.

