**Breast Cancer Classification using Support Vector Machines (SVM)**

This project demonstrates how to use **Support Vector Machines (SVM)** for both **linear** and **non-linear (RBF kernel)** classification using the **Breast Cancer Wisconsin Dataset**. The dataset is used to predict whether a tumor is **malignant** or **benign** based on cell features.

**Tools & Libraries Used**

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

**Dataset**
https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset

**Steps Performed**

 1. Load and Preprocess Data
- Removed `id` column
- Converted `diagnosis` to binary (M=1, B=0)
- Selected two features: `radius_mean` and `texture_mean`

 2. Data Splitting and Scaling
- Train/test split (80/20)
- StandardScaler for feature normalization

 3. Train SVM Models
- Linear SVM using `kernel='linear'`
- RBF SVM using `kernel='rbf'`

 4. Visualization
- Plotted decision boundaries for both linear and RBF SVM in 2D

 5. Evaluation
- Used accuracy score and classification report
- Compared performance of both models

 6. Hyperparameter Tuning
- Used `GridSearchCV` to tune `C` and `gamma` for the RBF kernel

 **Key Concepts Learned**

- Margin maximization in SVM
- Kernel trick for non-linear classification
- Impact of `C` and `gamma` hyperparameters
- Use of cross-validation (`GridSearchCV`)


