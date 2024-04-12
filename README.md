# credit-risk-classification

# Overview of the Analysis
The purpose of the analysis is to train a model that will accurately predict the creditworthiness of borrowers from a peer-to-peer lending services company using their historical lending activity, specifically looking at if the loan would be considered high-risk or low-risk based on the borrower's credit history. Using the information provided, we are looking at each individual's debt-to-income ratios, total debt, income, and other factors (X) to determine their 'riskiness' regarding loans (y).  

# Results
* The Logistic Regression Model that was created showed a 99.18% accuracy score, meaning that the model is reliable. However, because the model is so close to being perfect, I would want to go through and do this again with more data to see if the predictive capability hovers around this 99%. Because the recall percentages are so high (99% for low-risk loans and 91% for high-risk loans), we can trust that the model accuracy score is reliable because the model is able to catch mistakes that are made when labeling loans as low- or high-risk. In the provided table, the precision values indicate the accuracy of positive predictions made by the model for each class:
   * Low-Risk: Precision is 1.00, indicating that all (or 100%) predictions for this class are correct.
   * High-Risk: Precision is 0.85, meaning that 85% of the predictions for this class are correct.
  
* From the Confusion Matrix:
   * Low-Risk: Out of the total 18,765 loans considered low-risk, the Confusion Matrix shows that 18,663 as low-risk correctly (99.46%) and 102 as low-risk incorrectly (0.54%).
   * High-Risk: Similarly, out of 619 loans considered high-risk, the Confusion Matrix shows that 563 as high-risk correctly (90.95%) and 56 as high-risk incorrectly (9.05%).

# Summary
* I would recommend using the Logistic Regression Model since the accuracy of predicting whether a borrower is low- or high-risk was so high. The analysis aims to build a model predicting borrowers' creditworthiness based on historical lending data. A Logistic Regression Model achieved 99.18% accuracy, indicating reliability. High recall percentages (99% for low-risk, 91% for high-risk) suggest the model effectively identifies loan risk levels. Precision values confirm this, with 100% accuracy for low-risk and 85% for high-risk predictions. The Confusion Matrix highlights the model's performance: 99.46% correct predictions for low-risk and 90.95% for high-risk loans. Despite skepticism about high accuracy, the model's recall and precision rates reassure about its performance, suggesting it's suitable for practical use.  
