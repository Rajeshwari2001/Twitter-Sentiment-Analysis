# Twitter-Sentiment-Analysis
A course project for Pattern recognition and Machine Learning course at IIT Jodhpur.
# Project Setup
1. Clone the repository.<br/>
`git clone https://github.com/Rajeshwari2001/Twitter-Sentiment-Analysis.git`
2. Upload the Twitter_Sentiment_analysis.ipynb on Google Colaboratory.
3. Upload the database on drive and mount the drive in colaboratory notebook.
4. Update the file path accordingly and run all cells to see the output
## Dataset.
https://www.kaggle.com/kazanova/sentiment140
## Built with
- Python libraries
## Description.
- Preprocessing : Preprocessing is done by removing spaces,URL's,stopwords and punctuations and ends with the tokenization of the text in the given order.
- Data split : Split into training and testing data with the function train_test_split  with a test size of 0.25. Same training set is used for each model training to compare the accuracies.
- Vectorisation : Converted text into numerical matrix to process it. TfIdf and count vectorizers used.
- Models : The models used were Support Vector Machine(SVM)(in which different kernel techniques such as linear,Gaussian,sigmoid and polynomial were used);Multinomial Naive Bayes Cassifier and Decision tree classifier(in which gini and entropy criterion were used).
## Collaborators
| Name |
|---|
|[Sanjukta Bhattacharya](https://github.com/sanjukta7)|
|[Gudur Venkata Rajeshwari](https://github.com/Rajeshwari2001)|
|[Bhawna Chopra ](https://github.com/bhawnachopra2002)|
