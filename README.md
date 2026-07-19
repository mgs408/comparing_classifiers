# Practical Application III: Comparing Classifiers

**Overview**: This notebook compares the following classification algorithms: K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines, using a bank marketing dataset to predict whether a client will subscribe to a term deposit.

## Dataset

This dataset [link](https://archive.ics.uci.edu/ml/datasets/bank+marketing) details 79,354 phone contacts across 17 direct marketing campaigns from May 2008 to November 2010. The telemarketing calls promised attractive interest rates on long-term deposits and gathered demographic and financial details for each client. Ultimately, the dataset shows 8% success rate, with 6,499 customers subscribing.

Key Dataset Statistics

- Total Contacts: 79,354
- Total Campaigns: 17
- Timeline: May 2008 – November 2010
- Successful Subscriptions: 6,499
- Overall Success Rate: 8%

The interactions logged key socioeconomic and credit factors, including: employment status, job, marital status, education level, existing housing loans and personal debt.

## Results

The notebook presents the performance of different classification models before and after hyperparameter tuning; the following test accuracies were attained:

Based on the hyperparameter tuning and evaluation, the following are the test accuracies of the tuned models:

-   **Logistic Regression:** 0.909565
-   **KNN:** 0.897791
-   **Decision Tree:** 0.907866
-   **SVM:** 0.910658

Comparing these results, it is possible to conclude that SVM achieved the the highest test accuracy among the evaluated classification models.



