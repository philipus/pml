# practical mashine learning project

The goal in this project is to predict the "classe" variable in the training set. First I try to do it using a simple logistic regression model. Doing so I need to impute missing values. Infact the random forest algo which I used afterwords used the imputed variables. Befor imputing missings I was deleting the attributes with near zero information using nearZeroVar. The default method in caret is the bootstrap method which spilts the training data into training and testing data in order to estimate the out of sample error (accuracy).

Comment: I build the model with the code below but because of time consuming model building while the knitr process I saved the required models using save. so while I wrote this knitr I load the important obkects again

you need to get the repo using git in order to downlaod the html and Rmd files
* writeup_final.Rmd
* writeup_final.html
