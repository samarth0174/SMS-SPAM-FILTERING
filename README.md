# SMS-SPAM-FILTERING
Spam filtering/detection is one of the major applications of Machine Learning in the interwebs today. Pretty much all of the major email service providers have spam detection systems built in and automatically classify such mail as 'Junk Mail'.


## Problem Description:
Our aim is to create a model that can classify dataset SMS messages as spam or not spam, based on the training we give to the model. Usually spam messages have words like 'free', 'win', 'winner', 'cash', 'prize' and the like in them as these texts are designed to catch your eye and in some sense tempt you to open them. Also, spam messages tend to have words written in all capitals and also tend to use a lot of exclamation marks. To the recipient, it is usually pretty straightforward to identify a spam text and our objective here is to train a model to do that for us!

Being able to identify spam messages is a binary classification problem as messages are classified as either 'Spam' or 'Not Spam' and nothing else. Also, this is a supervised learning problem, as we will be feeding a labelled dataset into the model, that it can learn from, to make future predictions.

## Understanding our Dataset
We will be using a [The SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) from the UCI Machine Learning repository which has a very good collection of datasets for experimental research purposes. The direct data link is [here](https://archive.ics.uci.edu/ml/machine-learning-databases/00228/).

The given dataset is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.
<br>

Here's a preview of the data:
```
ham         Fine if thats the way u feel. Thats the way its gota b
spam	    England v Macedonia - dont miss the goals/team news. Txt ur national team to 87077 eg ENGLAND to 87077 Try:WALES, SCOTLAND 4txt/ú1.20 POBOXox36504W45WQ 16+
ham	    Is that seriously how you spell his name?
ham	    I‘m going to try for 2 months ha ha only joking
ham	    So ü pay first lar... Then when is da stock comin...
ham	    Aft i finish my lunch then i go str down lor. Ard 3 smth lor. U finish ur lunch already?
```
The columns in the data set are currently not named and as you can see, there are 2 columns.

The first column takes two values, 'ham' which signifies that the message is not spam, and 'spam' which signifies that the message is spam.

The second column is the text content of the SMS message that is being classified.

> Instructions:
> * Import the dataset into a pandas dataframe using the read_table method. Because this is a tab separated dataset we will be using '\t' as the value for the 'sep' argument which specifies this format.
> * Also, rename the column names by specifying a list ['label, 'sms_message'] to the 'names' argument of read_table().
> * Print the first five values of the dataframe with the new column names.
<br>


 
