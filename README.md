# Text_Classification_Rnn/svm
Text classification problem with Neural Network Method and Machine Learning Method.

The content has been gathered from the popular academic website arXiv.org for articles tagged as computer science content (though some of these are in mathematics or physics categories). Training is 1990-2014 and testing is 2015 plus a bit of 2016. 

The fields are:
- ID: a unique alphanumeric ID.
- URL: a working URL if you prepend "http://".
- Date: the date in format YYYY-MM-DD.
- Title: the full title, though with non-ASCII characters modified and any "," deleted.
- InfoTheory: a "1" if it is classified as an Information Theorey article, otherwise "0".
- CompVis: a "1" if it is classified as a Computer Vision article, otherwise "0".
- Math: a "1" if it is classified as a Mathematics article as well, otherwise "0".
- Abstract: the full abstract, though with non-ASCII characters modified.

The three classes are InfoTheory, CompVis and Math. These can occur in any combination, so an article could be all three at once, two, one or none. This task is to build three text classifiers that predict these three classes only using the Abstract field. I will present two different text classifiers for the three Boolean prediction tasks, and exactly one should be a neural network. That is, I develop three classifiers of the same kind of neural network that predict InfoTheory, CompVis and Math, and another three classifiers of the same kind (which cannot be neural networks) that predict the three Booleans again.

## Analysis code

Key elements of the analysis code are as follows:
- *Gender_Classifiction_Bert.ipynb* - a Python script used to build the gender classifier with BERT.
- *data.zip* - a zip file contains 3,600 twitter texts for those authors, which acts as the training and testing data.
- *train_labels.csv* – a csv file contains training ids and gender. It contains twitter posts from 3,100 authors and acts as the training data.
- *test_labels.csv* - a csv file contains test ids and gender. It contains the twitter posts from 500 authors.


## Authors

Tangwei, Hung

## Contact
hung.tangwei@gmail.com
