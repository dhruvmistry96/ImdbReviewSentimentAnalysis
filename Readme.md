Project Details:
I created two predictive models to perform a sentimental analysis IMDB Reviews.

## Why was Sentimental Analysis important to me?
 - I wanted to learn how people use their vocab to praise
		What makes a Review Good / Bad
		My Assumption: Some Keywords make a review Good/Bad

## Source for the Dataset
"https://ai.stanford.edu/~amaas/data/sentiment/"

## How was the Data Labeled?
 - Imdb lets the user rate a movie from 1 to 10
 - All Reviews rated under 4 were marked Negative
 - All Reviews rated above 7 were marked Positive
 - Reviews rated 5 or 6 were not used in this dataset.
 - The data is split evenly


## The Technologies I used along the analysis journey.

Python Pandas
PySpark
Amazon AWS
Zepl
PasteBin API

These are the models I created and compared to each other:
 - Logistic Regression Classifier
 - NaiveBayes Model


## For the Logistic Regression Classifier, please view the .ipynb file attached to this Github Repo.

A few things to highlight for the Logistic Regression Model are listed below:
 - Each review was first converted into a numerical value using the SKlearn Vectorizer
 - Then we create a classifier. The classifier was built using the SKLearn score_accuracy library which provided us with which C value would give the best Accuracy when we train our model
 - The C parameter of 0.05 was used to train the Final Logistic Regression model.
 - The parameter C is the the inverse of regularization strength in Logistic Regression.


## For the NaiveBayes Model please view the link to the Zepl notebook below:

"https://www.zepl.com/viewer/notebooks/bm90ZTovL2RocnV2bWlzdHJ5OTZAZ21haWwuY29tLzlkNzJiNzRiYTNmMzQ5ODQ4ODJiYWQ4Mzk1ZDFlYWUzL25vdGUuanNvbg"

The Results:

NaiveBayes Model had an Accuracy Rate of 78%.
while the Logistic Regression Model had the Rate of 89%.

Along the way I found the following words to be used the most in Positive/Negative Reviews:

Positive Words
 - excellent
 - perfect
 - great
 - amazing
 - superb

Negative Words
 - worst
 - waste
 - Awful
 - poorly
 - boring

The presentation below goes over the details of this project:
"https://docs.google.com/presentation/d/1maq_PGsn-kJiLoTgkSkkqjy1H6wpEktmcWcvtNqAnj4/edit?usp=sharing"