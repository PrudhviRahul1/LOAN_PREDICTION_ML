# Loan Approval Prediction using Machine Learning



\## Project Overview

This project focuses on building an end-to-end machine learning pipeline to predict whether a loan application should be approved based on applicant financial and personal information.  

The objective is to support better decision-making in loan approval systems by reducing risk and improving recall of critical cases.



---



\## Dataset

\- Source: Publicly available Loan Prediction dataset

\- Records include applicant income, loan amount, credit score, asset values, and loan status

\- Target variable: `loan\_status`



---



\##  Project Workflow

1\. Data loading and inspection

2\. Data quality checks and preprocessing

3\. Encoding categorical features

4\. Train–test split

5\. Model training and evaluation

6\. Model comparison and final selection



---



\##  Models Used

\- \*\*Logistic Regression\*\* (baseline model)

\- \*\*Random Forest Classifier\*\* (final model)



---



\##  Evaluation Metrics

\- Accuracy

\- Recall (prioritized due to business importance)



---



\##  Results



MODELS : 1.LOGISTIC REGRESSION - 1.ACCURACY - ~82% | 2.RECALL - ~66%
         2.RANDOM FOREST - 1.ACCURACY - ~97% | 2.RECALL - ~96%



Random Forest significantly outperformed Logistic Regression by capturing non-linear relationships and improving recall.



---



\## Final Conclusion

Although Logistic Regression provided a good baseline, Random Forest was selected as the final model due to its superior recall and accuracy.  

This makes it more suitable for real-world loan decision systems where missing important cases can be costly.



---



\##  Tools \& Technologies

\- Python

\- Pandas

\- NumPy

\- Scikit-learn

\- Jupyter Notebook



---



\##  Future Improvements

\- Cross-validation for better generalization

\- Hyperparameter tuning

\- Feature importance analysis

\- Model deployment using a web framework



