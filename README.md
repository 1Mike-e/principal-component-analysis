# 🧪 Principal Component Analysis (PCA) with Logistic Regression

This project demonstrates how to apply **Principal Component Analysis (PCA)** for dimensionality reduction and use **Logistic Regression** to classify wine types based on physicochemical properties. The results are visualized for both the training and test sets.

---

## 📁 Dataset

The dataset used is `Wine.csv`, which includes numerical features describing different wine samples and their corresponding class labels.

---

## 📌 Project Workflow

1. **Import Libraries**  
   Load essential libraries for data manipulation, modeling, and visualization.

2. **Load Dataset**  
   Import `Wine.csv` and separate features and labels.

3. **Split Dataset**  
   Divide the data into training and test sets using an 80/20 split.

4. **Feature Scaling**  
   Standardize features to ensure PCA performs optimally.

5. **Apply PCA**  
   Reduce the feature space to 2 principal components for visualization purposes.

6. **Train Model**  
   Train a Logistic Regression classifier on the reduced data.

7. **Evaluate Model**  
   Generate predictions, confusion matrix, and accuracy score on the test set.

8. **Visualize Results**  
   Create 2D decision boundary plots for both the training and test datasets.

---

## 📊 Visualizations

- Decision boundaries created using PCA-transformed features.
- Each class is represented with a unique color.
- Helps visually assess classification performance.

---

## 🛠️ Dependencies

Install the required Python libraries using pip:

```bash
pip install numpy pandas matplotlib scikit-learn
