# Face-Recognition-on-Olivetti-Dataset

# 🧠 Face Recognition using Olivetti Dataset

This project performs **face recognition** using the Olivetti Faces dataset, a collection of grayscale face images. The process involves dimensionality reduction with PCA and classification using various machine learning models.

## 📌 Project Workflow

1. **Dataset**  
   - Used the Olivetti Faces dataset from `sklearn.datasets`.

2. **Dimensionality Reduction**  
   - Applied **Principal Component Analysis (PCA)** to extract the most significant features (eigenfaces) from the face images.

3. **Component Selection**  
   - Determined the optimal number of principal components needed for best performance.

4. **Model Training**  
   - Trained and tested **three different classification models**:
     - Support Vector Machine (SVM)
     - K-Nearest Neighbors (KNN)
     - Logistic Regression (or another classifier used)

5. **Evaluation**  
   - Computed **accuracy scores** on the test set for each model.
   - Performed **cross-validation** to evaluate the generalization performance.

6. **Hyperparameter Tuning**  
   - Performed **parameter optimization** (e.g., GridSearchCV) on the best-performing model to further improve accuracy.

## 📊 Results

- PCA effectively reduced the dimensionality of image data while preserving key facial features.
- Among the tested classifiers, [insert best model name] achieved the highest accuracy.
- Parameter tuning further boosted the performance.

---

✅ Built with **Python**, **scikit-learn**, **matplotlib**, and **Jupyter Notebook**.
