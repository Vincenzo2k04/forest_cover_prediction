
# 🌲 Forest Cover Type Prediction

This project predicts the type of forest cover from cartographic variables using various machine learning models. The dataset used is the popular Forest Cover Type dataset from the UCI Machine Learning Repository.

## 📂 Project Structure

- `forest_cover_prediction.ipynb`: Main notebook containing preprocessing, modeling, and evaluation steps.
- `README.md`: Project overview and instructions.
- (Optional) `requirements.txt`: Python dependencies (to be added).

## 📊 Dataset

The dataset contains 581,012 rows and 54 features (after one-hot encoding), including:

- Elevation
- Aspect
- Slope
- Horizontal and Vertical Distances
- Soil Type (40 binary features)
- Wilderness Area (4 binary features)
- Target: Cover_Type (7 forest categories)

## 🚀 Models Used

The following models were implemented and compared:
- K-Nearest Neighbors (KNN)
- Logistic Regression
- XGBoost Classifier
- Random Forest (with enhancements)

All models were trained and evaluated on scaled data, with hyperparameter tuning using `GridSearchCV`.

## 🧪 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report

Each model’s performance was compared using these metrics to select the most effective one.

## 🧼 Preprocessing

- Missing value handling (if any)
- Feature scaling using `StandardScaler`
- Outlier removal
- Train-test split with stratification

## 🛠️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/forest-cover-prediction.git
   cd forest-cover-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook forest_cover_prediction.ipynb
   ```

## ✅ Results

The best performing model was **Random Forest with enhancements**, achieving over **X% accuracy** (replace with your result). The use of multiple algorithms ensured robust comparisons and insights.

## 📌 Future Improvements

- Feature selection using PCA or SHAP
- Ensemble stacking of models
- Model deployment using Streamlit or Flask

## 📚 References

- UCI ML Repository: [Forest Cover Type Dataset](https://archive.ics.uci.edu/ml/datasets/Covertype)
- Scikit-learn Documentation
- XGBoost Documentation

## 👨‍💻 Author

- [Your Name](https://github.com/your-username)
