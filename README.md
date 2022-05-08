# Credit_Risk_Analysis

## Purpose
The purpose of this module is to evaluate data to help predict idividuals as high or low credit risks.  In order to achieve this analysis, we analyzed data using several resampling techniques and machine learning models.  The results of these methods are  identified below. 

## Results
* Native Random Oversampling - The balanced accuracy score is 65% with the high-risk precision of 1% and recall of 72%.

![Naive_Random]("https://github.com/LauraZJ/Credit_Risk_Analysis/blob/main/Resources/NaiveRandomOversampling.png")

* SMOTE Oversampling - The balanced accuracy score is 66% with the high-risk precision of 1% and recall of 63%.

![SMOTE]("https://github.com/LauraZJ/Credit_Risk_Analysis/blob/main/Resources/SMOTE_Oversampling.png")

* Undersampling - The balanced accuracy score is 66% with the high-risk precision of 1% and recall of 69%.

![Undersampling]("https://github.com/LauraZJ/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png")

* Combination (Over/Under) Sampling - The balanced accuracy score of 54% with high-risk precision of 1% and 72% recall.

![Combination]("https://github.com/LauraZJ/Credit_Risk_Analysis/blob/main/Resources/Combination_sampling.png")

* Balanced Random Forest Classifier - The balanced accuracy score is 78% with high-risk precision of 4% and 67% recall.

![Balanced Classifier]("https://github.com/LauraZJ/Credit_Risk_Analysis/blob/main/Resources/balanced_random_forest_classifier.png")

* Easy Ensemble AdaBoost Classifier - The balanced accuracy score is 92% with high-risk precision of 9% and 89% recall.

![Easy Classifier]("https://github.com/LauraZJ/Credit_Risk_Analysis/blob/main/Resources/Easy_Ensemble_classifier.png")

## Summary
The desired outcome of the analysis is to identify the optimal method to use to predict credit risk.  To achieve this, we used 4 sampling methods, undersampling, oversampling a combination and SMOTE.  These models all produced accuracy scores from 54% to 66%.

While the Balanced Random Forest Classifier method produces a higher accuracy score, the recall is within the same range as the four sampling methods.  

However, the Easy Ensemble Classifier produces an accuracy score of 92% with better precision and recall than all other methods.  Therefore, this would be my chosen analysis method.
