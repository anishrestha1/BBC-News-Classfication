BBC Dataset News Classification

Consists of around 2225 documents from the BBC news website corresponding to stories in five topical area.
Class Labels: 5( Bussiness, Entertainment, Politics, Sport, Tech) 

Method 

Divided the feature extracted dataset into two parts train and test set. Train set contains 1490 examples and Test set contains 735 examples.
The dataset BBC News Train.csv is used to train the model.
1) The beginning task of seperating the 5 different categories are done by grouping the dataframe by categories and count items in each category.
2) Converting words in the news articles into numerical features using tfidf (term frequency-inverse document frequency).
3) A dimensionalty reduction technique to visualize (in 2 Dimensions), a high dimensional space by using t- SNE.
4) Model Training and Evaluation by using 3 differernt classification model on the data: Logistic Regression, RandomForest Classification and MultinomialNB (Navie Bayes).
5) Test data is now tested in the model and submission.csv file is made for the test data set.

Accuracy: 
The accuracy that I  got: 98.3221476510067.
