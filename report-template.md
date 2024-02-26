# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

In this analysis companies lend money to borrowers with the expectation that the borrower will either return the asset or repay the lender. Credit Risk is associated with a borrower not returning an asset or paying a loan back causing a lender to lose money. This is measured by lenders in many ways, however in this analysis we will use Machine Learning to analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  Model 1, which was trained on the original data, achieves an accuracy of 94.4% when predicting the two labels. It excels in predicting healthy loans, with perfect precision and recall scores of 1.00. However, its performance in predicting high-risk loans could be enhanced. The precision score for high-risk loans stands at 0.87, suggesting that only 87% of actual high-risk loans were accurately predicted. The recall score for high-risk loans is 0.89, indicating that the model identified only 89% of all high-risk loans present in the dataset.




* Machine Learning Model 2:
  Model 2, which was trained on the resampled data, achieves an accuracy of 99.6% when predicting the two labels. It excels in predicting healthy loans, with perfect precision and recall scores of 1.00. Although the precision score for high-risk loans remains at 0.87, the recall score has improved to 1.00. This improvement suggests that the model can now correctly predict all high-risk loans present in the dataset.


## Summary

The analysis indicates that Model 2 surpasses Model 1 in predicting high-risk loans and demonstrates a higher overall accuracy in predicting both labels. Model 2 notably achieved a high precision in predicting high-risk loans and successfully identified all high-risk loans in the dataset, showcasing strong performance in this aspect. Consequently, I recommend utilizing Model 2 for identifying high-risk loans due to its improved accuracy in predicting labels.


