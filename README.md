# Task-7
Task-8 AI-ML Internship By Elevate Labs

Data : Breast cancer
Tools : Scikit-learn,pandas, NumPy, Matplotlib

1. Load and Prepare Dataset
We loaded the Breast Cancer dataset, which is used for binary classification (malignant vs. benign). We selected only two features for visualization and split the data into training and test sets. Feature scaling was applied to normalize the values for better SVM performance.

2. Train SVM with Linear and RBF Kernels
Two Support Vector Machine models were trained: one with a linear kernel and one with an RBF (Radial Basis Function) kernel. These models were fit to the training data, and their accuracy was evaluated on the test data.

3. Visualize Decision Boundary
We plotted the decision boundaries for both the linear and RBF models using the 2D feature space. This helped us visually understand how each model separates the two classes in the dataset.

4. Tune Hyperparameters (C and Gamma)
We used GridSearchCV to find the best values for the C and gamma parameters. C controls regularization, and gamma defines how far the influence of a single training point reaches. The model was optimized based on cross-validation performance.

5. Use Cross-Validation to Evaluate Performance
We evaluated the best model using k-fold cross-validation (usually k=5), which splits the training data into multiple folds to test model generalization. The average score across folds gave a more reliable performance estimate.
