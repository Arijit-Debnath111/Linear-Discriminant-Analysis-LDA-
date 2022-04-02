# Linear-Discriminant-Analysis-LDA-
It's is also a dimensional reduction  algorithm which is used in ML
The process is as-
#recall->tp / (tp + fn)
#The recall is the measure of our model correctly identifying True Positives. 
#
#precision of class 0 = TP of class 0/total number of object 
#What is the Precision for our model? Yes, it is 0.1 or, when it predicts 0 digit, it is correct around 100% of the time.
#precision of class 1 = TP of class 1/total number of object 
#macro average = (precision of class 0 + precision of class 1)/2 

#weighted average is precision of all classes merge together
#weighted average = (TP of class 0 + TP of class 1)/(total number of class 0 + total number of class 1) 

#F1-score is a measure of a model's accuracy on a dataset
#a good F1 score means that you have low false positives and low false negatives, 
#Accuracy is used when the True Positives and True negatives are more important while 
#F1-score is used when the False Negatives and False Positives are crucial.
#Support is the number of actual occurrences of the class in the specified dataset.


