# Motion-type-classifier
Takes in 59 variables and build a classifier that classifies 5 types of motion.
It chooses to use all variables from column 6 to 59 to predict column 60's variable, classe, 
even though the variable on column 6 is a near zero variance variable.  It does have over 
400 cases for the minority "yes" group for that two-level factor variable.
Then, only a random forest algorithm is used to train the entire training set of data to 
give a perfect test set answer:  20 out of 20 was predicted correctly.
For the html file, just open it up by left-clicking on it, and then left-click on the little
symbol that says open this up on Github desktop, and then the easier to read actual html
output should open up.  Thanks.
