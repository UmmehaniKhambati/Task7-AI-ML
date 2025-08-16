# Task7AIML

#Steps Performed
1. Data Preprocessing
   Loaded dataset (`breastcancer.csv`)
    Split into train/test (80:20)
    Standardized features

2. Model Training
    SVM with Linear kernel
    SVM with RBF kernel

3. Evaluation
    Metrics: Accuracy, Precision, Recall, F1score
    Both kernels achieved ~96.5% accuracy

4. Visualization
    PCA reduced dataset to 2D
    Plotted decision boundaries (toy dataset demo for clarity)

5. CrossValidation & Hyperparameter Tuning
    Used GridSearchCV (which applies crossvalidation internally)
    Best parameters: `C=1, gamma='scale', kernel='rbf'`
    Best CrossValidation Accuracy: 97.8%
    Test Accuracy: 96.5%
