# Motion-type-classifier
Takes in 59 variables and build a classifier that classifies 5 types of motion.
It chooses to use all variables from column 6 to 59 to predict column 60's variable, classe, 
even though the variable on column 6 is a near zero variance variable.  It does have over 
400 cases for the minority "yes" group for that two-level factor variable.
Then, only a random forest algorithm is used to train the entire training set of data to 
give a perfect test set answer:  20 out of 20 was predicted correctly.
For the html file, you must get off the master branch and go to the gh-pages branch.  left-
click on the Motion-type classifier.html link, then click on the little screen like picture 
that says open this file on the Github desk top to view the html file without the html code, 
which is easier to read. Remember, you should wait a minute to a few minutes before the real
html output would show up.  So, please exercise some patients.  Thanks!!
