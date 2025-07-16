# CODSOFT-TASK-4
**SMS SPAM DETECTION** 

This project focuses on detecting spam messages in SMS text using supervised machine learning techniques. It takes a labeled dataset of SMS messages and trains classification models to distinguish between spam and ham (not spam).

**About Dataset**

The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.

**Usage**

1. Automatically detects if an SMS message is spam or not using machine learning.
2. Can be used in mobile apps or messaging platforms to filter unwanted spam messages.
3. Useful for learning and practicing machine learning, especially text classification.
   
**Preprocessing Text Using TF-IDF**

1.TF = Term Frequency → how often a word appears in a message
2.IDF = Inverse Document Frequency → how rare the word is across all messages

TF-IDF is a method to convert text (like SMS messages) into numbers so that a machine learning model can understand and work with it.

TF-IDF converts the text messages into numbers while also:
1.Giving importance to spammy words (like "free", "win", "offer")
2.Ignoring common, useless words (like "the", "at", "is")

 **Model Training**
 
   Three models are used:
   1.Naive Bayes
   2.Logistic Regression
   3.Support vector machine(SVM)
   
Each model was evaluated on four metrics:
 1.Accuracy
 2.Precision (Macro Average)
 3.Recall (Macro Average)
 4.F1-Score (Macro Average)
 
**Accuracy**

Accuracy of all three models
Naive bayes accuracy:0.975
Logistic regression accuracy:0.947
SVM accuracy:0.974

**BEST MODEL OF SMS SPAM DETECTION PROJECT: NAIVE BAYES MODEL**

**Contributors**

### Thalluru LakshmiPrasanna

**Future Scope**

1.Use Deep Learning models like LSTM or BERT for better spam detection accuracy.
2.Extend it to emails, social media, or chat apps (WhatsApp, Telegram, etc.).
3.Add support for multiple languages (e.g., Hindi, Telugu, etc.) for global use.
4.Implement real-time spam detection in mobile or web applications.
5.Combine with phishing or malware detection for enhanced security.


     
