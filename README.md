## Wine classification (Tree, RandomForest, LogisticR)


### Data Set Information:

*The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: [Web Link] or the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).*

*These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.*

### Source:

*Paulo Cortez, University of Minho, Guimarães, Portugal, http://www3.dsi.uminho.pt/pcortez
A. Cerdeira, F. Almeida, T. Matos and J. Reis, Viticulture Commission of the Vinho Verde Region(CVRVV), Porto, Portugal
@2009*

## Procedures and goals

- Load the data frame, visualization of histograms and correlations, to understand the important features
- Machine learning to classify the quality of wines. In order: Tree, RandomForest, and LogisticRegression
- We filter features to use Tree and RandomForest machine learning techniques
- For the two first models we explore the mean_error and grid_search to find out the best parameter and avoid underfitting and overfitting. 
 To do that, we plot the score versus the depth of the tree to find out the parameter value that avoids underfitting and overfitting.
  On the other hand, we plot error_function to determine the depth parameter and compare it with the value determined by 
  the mean_train_score and mean_val_score curve. We show that values match perfectly.
  -For LogisticR we consider all features and the grid search to tuning parameter C.

  To learn more about this project and conclusion as well, see the python file.# Wine-classification-Tree-RandomForest-LogisticR-
