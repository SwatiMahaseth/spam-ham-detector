# spam-ham-detector
## Content
The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

This corpus has been collected from free or free for research sources at the Internet:

-> A collection of 425 SMS spam messages was manually extracted from the Grumbletext Web site. This is a UK forum in which cell phone users make public claims about SMS spam messages, most of them without reporting the very spam message received. The identification of the text of spam messages in the claims is a very hard and time-consuming task, and it involved carefully scanning hundreds of web pages. The Grumbletext Web site is: [Web Link].
-> A subset of 3,375 SMS randomly chosen ham messages of the NUS SMS Corpus (NSC), which is a dataset of about 10,000 legitimate messages collected for research at the Department of Computer Science at the National University of Singapore. The messages largely originate from Singaporeans and mostly from students attending the University. These messages were collected from volunteers who were made aware that their contributions were going to be made publicly available. The NUS SMS Corpus is avalaible at: [Web Link].
-> A list of 450 SMS ham messages collected from Caroline Tag's PhD Thesis available at [Web Link].
-> Finally, we have incorporated the SMS Spam Corpus v.0.1 Big. It has 1,002 SMS ham messages and 322 spam messages and it is public available at: [Web Link]. This corpus has been used in the following academic researches:

## Project Overview
- Created a machine learning model that detects/classifies a SMS into SPAM or HAM (normal) based on the textual data using Natural Language Processing.
- Engineered features like word_count, contains_currency_symbol, and contains_number from the text SMS.
- This project helps in filtering/cleaning the SMS from the phone.

### Approach: 
The classical machine learning tasks like Data Exploration, Data Cleaning,  Feature Engineering, Model Building and Model Testing. Try out different machine  learning algorithms that’s best fit for the above case. 


### Resources Used
- Packages: pandas, numpy, sklearn, matplotlib, seaborn, nltk.
- Dataset by UCI Machine Learing on Kaggle: https://www.kaggle.com/uciml/sms-spam-collection-dataset

### Feature Engineering
- Handling imbalanced dataset using Oversampling
SpamVsHam
- Creating new features from existing features e.g. word_count, contains_currency_symbol, contains_numbers, etc.
word_count
currency_numbers

### Data Cleaning
- Removing special character and numbers using regular expression
- Converting the entire sms into lower case
- Tokenizing the sms by words
- Removing the stop words
- Lemmatizing the words
- Joining the lemmatized words
- Building a corpus of messages

### Model Building and Evaluation
- Decision Tree: 0.97
- Random Forest: 0.99

Note: Evaluation scores are obtained using accuracy score.

