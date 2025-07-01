# K-Nearest Neighbors Classifier – Iris Dataset

## Objective
Build and evaluate a K-Nearest Neighbors (KNN) classification model using the Iris dataset. The model is trained to predict the species of iris flowers based on petal and sepal measurements, and the decision boundaries are visualized using different feature combinations.

---

## Steps Performed

- Installed and imported all required libraries.
- Loaded the Iris dataset using Pandas.
- Explored the dataset using `head()` and `info()`.
- Checked for missing values and inspected feature distributions.
- Encoded target labels if necessary.
- Split data into training and testing sets (80/20).
- Standardized numerical features using `StandardScaler`.
- Trained a **K-Nearest Neighbors Classifier** from scikit-learn.
- Evaluated the model using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
- Visualized **decision boundaries** using different 2D feature combinations
- Used color maps and `matplotlib` for plotting classification regions.

---

## Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Google Colab  

---

## Evaluation Metrics

- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-score  
- Decision Boundary Visualizations  

---

## Key Takeaways

- KNN is a simple yet powerful non-parametric algorithm that works well on small datasets.
- The decision boundary changes with the value of **k**; lower values may lead to overfitting.
- Visualizing decision boundaries helps understand how the classifier separates classes.
- Standardizing features is essential for distance-based models like KNN.
- Performance can be enhanced or stabilized using cross-validation and parameter tuning.

---

## Dataset

The dataset used is `Iris.csv`, which contains flower measurements:

- **Features**: SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm  
- **Target**: Species (Setosa, Versicolor, Virginica)

---

## How to Run

1. Upload the notebook to Google Colab.
2. Upload the `Iris.csv` file when prompted.
3. Run each cell in sequence to train the model and visualize results.

---

