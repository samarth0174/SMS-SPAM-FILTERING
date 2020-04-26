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
  </ul>
  
## Theory:

Document/Text classification is one of the important and typical task in supervised machine learning (ML). Assigning categories to documents, which can be a web page, library book, media articles, gallery etc. has many applications like e.g. spam filtering, email routing, sentiment analysis etc. We will be using some Nlp steps for text preprocessing and then multinomaial naive bayes classifier & SVM for classification.

<ul><li><b>Multinomial Naive Bayes Classifier:</b> 
This classifier is suitable for classification with discrete features (e.g., word counts for text classification). The multinomial distribution normally requires integer feature counts. However, in practice, fractional counts such as tf-idf may also work.
  <a href="https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html">more info</a>
  
<li><b>Support vector machines:</b> 
SVMs are a set of supervised learning methods used for classification, regression and outliers detection.They are Effective in high dimensional spaces.Effective in cases where number of dimensions is greater than the number of samples.Uses a subset of training points in the decision function (called support vectors), so it is also memory efficient.Different Kernel functions can be specified for the decision function. Common kernels are provided, but it is also possible to specify custom kernels.
 <a href="https://scikit-learn.org/stable/modules/svm.html#">more info</a>




 
