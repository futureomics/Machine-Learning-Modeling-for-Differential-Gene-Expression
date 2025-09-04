# Machine-Learning-Modeling-for-Differential-Gene-Expression

Machine Learning (ML) modeling for differential gene expression analysis results (logFC, p-values, etc.)

<img width="1333" height="666" alt="image" src="https://github.com/user-attachments/assets/2fff935e-893a-42b5-80dc-15e719bc22af" />


<img width="521" height="150" alt="image" src="https://github.com/user-attachments/assets/326b0030-73e2-42df-b5cc-597b1f787294" />


1.Loads the data

2.Preprocesses it

3.Performs classification (upregulated vs. downregulated genes)

4.Builds an ML pipeline with scaling + a simple ML model (e.g., Random Forest)

5.Evaluates performance with metrics

Genes with logFC > 0 = Upregulated (class 1)

Genes with logFC < 0 = Downregulated (class 0)


**Modeling, feature importance, PCA visualization, and hyperparameter tuning
Multiple Models: Random Forest, Logistic Regression, SVM, XGBoost**

Cross-validation Accuracy for robust comparison

Best Model Selection automatically based on accuracy

PCA Visualization using the best-performing model

<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/3fbd8fd3-c524-4909-945b-d1ae75daf901" />



**LASSO model LASSO is essentially Logistic Regression with L1 regularization for classification tasks. It does two things:
**
Classification of upregulated vs. downregulated genes

Feature selection by shrinking some coefficients to zero → helps identify important features

Follow like, share, and subscribe https://www.youtube.com/@Bioinformatics_Made_Easy
