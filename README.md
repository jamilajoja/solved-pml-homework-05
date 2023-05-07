Download Link: https://assignmentchef.com/product/solved-pml-homework-05
<br>
The wine dataset is a multi-class classification dataset which contains three different wine categories and 13 continuous-valued features, for a total of 178 observations.

The goal is to classify an unlabeled wine according to its characteristic features.

y.shape = (178,)

wine categories:

[0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0

<ul>

 <li>0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1</li>

 <li>1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1</li>

 <li>1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2</li>

 <li>2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2]</li>

</ul>

features names:

[‘alcohol’, ‘malic_acid’, ‘ash’, ‘alcalinity_of_ash’, ‘magnesium’, ‘total_phenols’, ‘flavanoids ‘, ‘nonflavanoid_phenols’, ‘proanthocyanins’, ‘color_intensity’, ‘hue’, ‘od280/od315_of_diluted_w ines’, ‘proline’]

<ol>

 <li>Perform a train-test split on the data using sklearn train_test_split with test_size=0.3 . Name your variables X_train , X_test , y_train , y_test . Make sure that your training set contains samples from all the categories.</li>

 <li>Fit sklearn LogisticRegression model to the training data X_train , y_train , predict the classification labels on the test data X_test and use sklearn classification_report to evaluate your model against the actual labels y_test .</li>

 <li>Repeat step 2. using sklearn Naive Bayes classifier GaussianNB .</li>

</ol>