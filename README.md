# Don't Leave Me Hanging: Filling in the Blanks Using Machine Learning Imputation Techniques

## Author
Paula Martinez

## Project Description
In light of the pervasive integration of AI into decision-making processes, it becomes increasingly crucial to prioritize the fairness of these algorithms. The imperative here is to ensure that these systems remain unbiased and do not discriminate in favor of specific demographic groups, including considerations related to gender, race, or nationality. Upholding fairness in AI is not merely a technological concern but a fundamental ethical principle to prevent unjust disparities and promote equitable outcomes across diverse populations.

Concerns about fairness in data aren't new; they've been around long before AI became a big player. It's not simply a matter of dealing with biased data; the quality of how we handle and process this data is equally important. Fairness demands a comprehensive and thoughtful approach to both data itself and the processes that shape its interpretation and utilization.

One major issue about data quality is the presence of missing values. When these gaps exist in the dataset, they can disrupt the seamless flow of data through various processes in the analytical pipeline, such as data visualization. Missing values can also affect the predictive power of machine learning methods. This mini project explores machine learning imputation techniques to address the presence of missing values.

## Solution Abstract
This exploration tested the effect of different imputation techniques to the predictive power of machine learning models. For single imputation methods, the mean and the mode were used. For multiple imputation methods, `scikit-learn`'s `KNNImputer` and `IterativeImputer` were used. Only the default parameters of the classifiers and imputers were utilized to clearly attribute any improvement in accuracy to the imputation technique used.

## What's Next?
- **The Need for Hypertuning and More Data**
    - This optimization will allow the models to reach their full potential and enhance their accuracy and robustness. Additionally, consider expanding the dataset through either feature engineering techniques or acquiring more data. A larger and more diverse dataset can provide the models with a richer set of patterns to learn from, which will further improve their performance.
- **Explore Non-regression Estimators**
    - Iterative imputation methods, when coupled with suitable estimators, can be powerful tools for handling missing data effectively. This approach may uncover intricate relationships within the data and contribute to more accurate imputations.
- **Integrate Unsupervised Learning Models**
    - Unsupervised learning can unveil hidden patterns and clusters within the data, which could provide a more comprehensive understanding of the underlying dynamics related to recidivism. This aligns with the broader goal that extends from merely classifying re-offenders to identifying the determinants of recidivism, which is important to build a system that prioritizes rehabilitation and reintegration of individuals into society.
