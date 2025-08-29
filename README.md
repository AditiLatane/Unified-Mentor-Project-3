## Unified-Mentor-Task-3
# Iris classification

**Problem Statement :**
The Iris Classification project involves creating a machine learning model to classify iris flowers into three species (Setosa, Versicolour, and Virginica) based on the length and width of their petals and sepals. This is a classic problem in machine learning and is often used as an introductory example for classification algorithms.

# **Steps** :
1. **Dataset Preparation**
   
2. **Data Exploration and Visualization**

3. **Data Preprocessing**

4. **Model Selection and Training**
   
   Models used :
   1. Support Vector Machine (SVM)
   2. Logistic Regression
   3. K-Means
   4. PCA 

5. **Model Evaluation**
📊 Model Comparison on Iris Dataset

| Model                | Accuracy  | Precision | Recall   | F1-score | Notes                    | Explained Variance (PC1) | Explained Variance (PC2) | Total (PC1+PC2) |
|-----------------------|-----------|-----------|----------|----------|--------------------------|--------------------------|--------------------------|-----------------|
| **SVM**              | 1.0       | 1.0       | 1.0      | 1.0      | Supervised classifier    | NaN                      | NaN                      | NaN             |
| **Logistic Regression** | 0.933333 | 0.933333  | 0.933333 | 0.933333 | Supervised classifier    | NaN                      | NaN                      | NaN             |
| **KMeans**           | NaN       | NaN       | NaN      | NaN      | Unsupervised clustering  | NaN                      | NaN                      | NaN             |
| **PCA**              | NaN       | NaN       | NaN      | NaN      | Dimensionality reduction | 0.727705                 | 0.230305                 | 0.95801         |

6. **Hyperparameter Tuning** 
   ✅ Best Parameters: {'C': 0.1, 'gamma': 'scale', 'kernel': 'linear'}
   
   ✅ Best Cross-Validation Accuracy: 0.975

   Test Accuracy with Best SVM: 0.9333333333333333

7. **Model Interpretation and Insights**
   📊 Standardized Feature Means by Species

| Species          | SepalLengthCm | SepalWidthCm | PetalLengthCm | PetalWidthCm |
|------------------|---------------|--------------|---------------|--------------|
| **Iris-setosa**      | -0.810166      |  1.393699     | -1.687386      | -1.518991     |
| **Iris-versicolor**  |  0.130380      | -1.246338     |  0.789195      | -0.889440     |
| **Iris-virginica**   |  0.012990      | -0.144535     |  1.863173      |  2.698873     |

<img width="755" height="489" alt="image" src="https://github.com/user-attachments/assets/4b4ff5bc-1eee-4770-8d8c-b5435b14ba17" />

8. **Conclusion**
   
   Petal width and petal length are the strongest predictors of iris species. Setosa is always well-separated, while Versicolor and Virginica are more challenging due to partial overlap.

Next Project : 
