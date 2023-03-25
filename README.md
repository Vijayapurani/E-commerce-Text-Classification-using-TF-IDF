# E-commerce-Text-Classification-using-TF-IDF
Text Classification using TF-IDF and XG Boost Classifier

## About the dataset
E-commerce text dataset has 4 categories - "Electronics", "Household", "Books" and "Clothing & Accessories", which almost cover 80% of any E-commerce website.
Source : Kaggle

## Objective
  To classify the data into appropriate class using suitable NLP techniques
  
## Procedure
   The dataset is analysed and cleaned. Proprocessing step includes removal of stopwords, removing non-alpha characters, lemmatization and truncation. Truncation is performed to limit the length ofinput to TF-IDF to 150 words (median word length), to reduce computational cost TF-IDF is used for vectorization ang XG Boost algorithm is used for classification. A weighted F1 score of .9 is obtained on the test set. 
   

