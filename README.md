# AutoGluon
AutoGluon, developed by AWS AI, automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy machine learning and deep learning models.  
**Feature importance** allows you to understand the relationship between the features and the target variable.


## Operators Nova Scotia - Classification model
#### The **RandomForestEntr** model achieved the highest test accuracy (93.14%) and slightly outperformed the other models in validation accuracy (71.77%).  
#### **RandomForestGini** closely followed with a test accuracy of 93.12% and validation accuracy of 71.57%.  
Overall accuracy is 81.30%, balanced accuracy is similarly high (81.07%), and the MCC (Matthews Correlation Coefficient) is 0.62, which indicates reasonable predictive performance across all classes.  
F1-score: 0.79 - good balance between precision and recall.
Precision: 0.82 - indicates relatively few false positives.
Recall: 0.78 - reflects that most true positives were correctly identified.  
#### **Visitor Origin** (21.62%) and Number of Visitors (Rounded to nearest hundred) (20.71%) are the most significant predictors, indicating the model relies heavily on these features.

## Tourism Nova Scotia - Classification model  
#### The leaderboard indicates **ExtraTreesGini** and **ExtraTreesEntr** as the best-performing models, achieving identical test accuracy scores of 0.912649. Validation accuracy is comparatively lower (0.603399), suggesting potential overfitting or a less representative validation set.      
#### RandomForestEntr comes third but still delivers strong test accuracy (0.912082) with slightly lower validation accuracy (0.600567).      
While the test accuracy is quite high, the balanced accuracy (0.5958) and MCC (Matthews Correlation Coefficient, 0.5763) reveal imbalances in prediction across classes. This suggests that class imbalances or feature issues might need attention.      
#### **Name** dominates feature importance, indicating it heavily influences predictions. However, Region, Latitude, and Longitude have marginal significance, while Location appears least impactful.
