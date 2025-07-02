 🌼 Iris Flower Classification using K-Nearest Neighbors (KNN)

📌 Task Objective

Build a K-Nearest Neighbors (KNN) classifier to predict the species of Iris flowers using sepal and petal features.

 🗂 Dataset Used

- Dataset: Iris Dataset (built-in from `sklearn.datasets`)
- Features: Sepal length, sepal width, petal length, petal width
- Target classes:
  - 0: Setosa
  - 1: Versicolor
  - 2: Virginica
- Samples: 150 total (50 per class)

🛠 Tools & Libraries Used

- Python
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

✅ Steps Performed

 1. Data Loading & Exploration
- Loaded from `sklearn.datasets.load_iris()`
- Verified all 3 classes are equally distributed (50 each)

 2. Feature Scaling
- Standardized features using `StandardScaler`
- Important for distance-based models like KNN

 3. Train-Test Split
- Split dataset (80% train, 20% test)

 4. Model Tuning – Best K Value
- Tested K from 1 to 20
- Achieved **maximum accuracy (100%)** for K between 3–15

 5. Final KNN Model
- Used `K=5`
- Achieved perfect classification
  
 6. Decision Boundary Visualization
- Plotted 2D decision boundaries using:
- `petal length`
- `petal width`
- Model clearly separates all 3 species



 📊 Final Output

| Metric         | Value |
|----------------|--------|
| **Best K**     | 5      |
| **Accuracy**   | 100%   |
| **Precision**  | 1.00   |
| **Recall**     | 1.00   |
| **F1-Score**   | 1.00 

