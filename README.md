## SMS-SPAM-FILTERING
Problem Description:The given dataset is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.Task is to build a **prediction model that will accurately classify which texts are spam**<br>
<br>
Data used : <b><a href="https://www.kaggle.com/uciml/sms-spam-collection-dataset">The SMS Spam Collection Dataset</a><b><br>

## Notebook Summary:
- Libraries
- Exploring the Dataset
- Distribution spam and non-spam plots
- Text Analytics
- Feature Engineering
- Predictive analysis (**Multinomial Naive Bayes and Support Vector Machines**)
- Conclusion

## Results Achieved:
<ul>
<li>The best model found is <b>support vector machine<b>with 97.9% validation accuracy.
<li>It classifies 99.5% non-spam message correctly (Model precision)
<li>It classifies the 85.3% of spam messages correctly (Model recall)
<br>
  
## Multinomial Naive Bayes Classifier:
The multinomial Naive Bayes classifier is suitable for classification with discrete features (e.g., word counts for text classification). The multinomial distribution normally requires integer feature counts. However, in practice, fractional counts such as tf-idf may also work.
