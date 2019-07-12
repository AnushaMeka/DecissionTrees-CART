# DecissionTrees-CART

Jupyter notebooks here gives the understanding on how decision trees are used both for regression and classification.

Decision trees are resistent to outliers but they are very prone to overfitting - to minimize that use the concept of pruning - cutting the branches/features which have less importance. Basically ensure that tree is small ie., less in depth. 

Select the feature for splitting with high information gain(without having same number of positives and negatives in 'yes' and 'no' branches).

Performance Evaluation:

I have used R-squared for Regression and Accuracy for Classification

R-squared:
In general, the higher the R-squared, the better the model fits your data. 

High variance  --> High R-squared

It doesn't mean that low R-squared results in bad fit of data - It depends on type of problem - I feel achieving 40% fit of data to the problems involving human behaviour is considered as a good model.

If there is 100% of variance or R2 then there is 100% possibility of overfitting data which is not good for predicting unseen data.

