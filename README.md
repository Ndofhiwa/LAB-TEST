# LAB-TEST

## Question 2: Perceptron Training

### 2.1 Prediction Interpretation
- Prediction -1 = Book classified as Non-Fiction

### 2.2 Misclassification Count
Code: Perceptron with eta=0.01, 10 iterations
Total misclassifications: 6

### 2.3 Error Convergence
- Error reaches zero due to linearly separable data
- Perceptron Convergence Theorem guarantees perfect boundary

Question 3: Scikit-learn Classifiers
3.1 Classifier Comparison

    SVM demonstrates superior separation capabilities

    Focuses on establishing a maximum margin decision boundary

    Results in more robust and better generalizing models

3.2 SVM Advantage

    The kernel trick allows SVM to create non-linear decision boundaries

    Eliminates the need for manual feature engineering

    Efficiently manages complex feature relationships

Question 4: Data Preprocessing
4.1 Feature Scaling Importance

    Guarantees all features contribute equally to the model

    Prevents algorithm bias toward features with larger numerical ranges

    Particularly crucial for distance-based methods and gradient descent optimization

4.2 Categorical Encoding

    Machine learning algorithms require numerical input data

    Avoids incorrect assumptions about categorical ordering

    One-Hot Encoding generates meaningful binary representations

Question 5: PCA Compression
5.1 Variance Captured

print("Variance captured:", sum(pca.explained_variance_ratio_))

The first two principal components preserve over 97% of the original data variance
Question 7: Ensemble Learning
7.1 Ensemble Superiority

    Based on the collective intelligence principle

    Multiple models working together minimize individual prediction errors

    Aggregation through averaging or voting enhances both accuracy and robustness

7.2 Bagging vs Boosting

    Boosting methods like AdaBoost generally deliver superior performance

    Iteratively concentrates on challenging training instances

    Constructs powerful models by combining multiple weak learners

Question 8: Sentiment Analysis
8.1 Sentiment Prediction

    Prediction: Positive (1)

    The term "good" aligns with positive sentiment vocabulary from training data

8.2 Text Preprocessing Importance

    Tokenization: Converts text into meaningful feature units

    Stopword removal: Minimizes noise and reduces feature dimensionality

    Enhances model concentration on discriminative vocabulary

Question 9: Regression Analysis
9.1 RMSE Comparison

    Random Forest achieves superior performance with lower RMSE

    Effectively captures complex non-linear relationships in data

    Linear Regression faces limitations due to its linearity assumptions

9.2 Random Forest Advantage

    Excels at modeling intricate, non-linear patterns

    Operates without linear relationship assumptions

    Naturally handles complex feature interactions

Question 10: Clustering
10.1 Cluster Alignment

    Identified clusters show strong but imperfect alignment with species categories

    K-Means discovers natural statistical groupings in data

    Minor misassignments occur due to overlapping species characteristics

10.2 Unsupervised Nature

    Functions without requiring labeled training data

    Uncovers inherent patterns and structures within the dataset

    Groups data points based on intrinsic similarity measures
