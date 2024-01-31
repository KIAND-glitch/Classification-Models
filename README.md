# Classification and Evaluation Assignment

This repository contains my implementation for the Classification and Evaluation assignment as part of the Introduction to Machine Learning (COMP90049) course at The University of Melbourne. The assignment involves applying various classifiers to the Adult and Student datasets, evaluating results, and answering conceptual questions.

## Datasets

- **Adult**: Predict income based on personal attributes.
- **Student**: Predict final grade based on various attributes.

Attributes are outlines in readme.txt within the datasets

## Key Questions

### 1. Reading and Pre-processing [1.5 marks]

- Read data into a pandas DataFrame.
- Handle missing values and use one-hot encoding.
- Implement equal-width binning for numerical features.

### 2. Baseline Methods and Discussion [4.5 marks]

- Evaluate Zero-R, One-R, and Weighted Random models.
- Discuss differences between baseline models and datasets.
- Inspect feature selection in One-R.
- Analyze convergence of error rate in Weighted Random.

### 3. Naive Bayes Models [5 marks]

- Implement Gaussian, Bernoulli, and Categorical Naive Bayes.
- Compare Naive Bayes models against baseline.
- Identify the best-performing NB classifier for each dataset.
- Discuss assumptions of Gaussian NB.

### 4. K-Nearest Neighbor [3 marks]

- Train/test K-Nearest Neighbor models with Euclidean distance.
- Compare weighted and majority KNN models.

### 5. Evaluation Metrics [2 marks]

- Compute micro/macro-averaged precision for specific models.

### 6. Ethics and Implications in Practice [4 marks]

- Discuss ethical problems in using the Categorical Naive Bayes classifier.
- Remove ethically problematic features, train NB classifiers, and compare performance changes.
- Discuss fairness implications of removing problematic features.


