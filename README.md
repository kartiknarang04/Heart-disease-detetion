# Heart-disease-detetion

### Techniques Used

1. **Baseline Models**: Initially, the dataset is used to train three baseline classifiers:
   - Random Forest: A versatile ensemble learning method based on decision trees.  Accuracy: 0.83
   - Decision Tree: A simple yet powerful classification algorithm that partitions the feature space into regions. Accuracy: 0.83
   - Support Vector Machine (SVM): A supervised learning algorithm that finds the optimal hyperplane to separate classes in a high-dimensional space. Accuracy: 0.70

2. **Feature Selection**: 
   - K-Best Feature Selection: Selects the top k features based on statistical tests such as ANOVA. Accuracy - 0.87
   - Random Forest Feature Importance: Ranks features based on their importance scores computed by a Random Forest classifier. Accuracy: 0.83

3. **Dimensionality Reduction**:
   - Principal Component Analysis (PCA): Reduces the dimensionality of the feature space while retaining as much variance as possible. Accuracy: 0.85
