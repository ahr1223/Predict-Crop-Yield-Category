# 🌾 Crop Yield Classification using Machine Learning

This project aims to predict crop yield categories based on agricultural features such as soil quality, rainfall, and seed type. A Random Forest Classifier is used to classify the crop yield into predefined categories.

## 📁 Project Structure

- `crop_yield.csv`: The dataset used for model training and evaluation.
- `main.py`: The Python script that performs data preprocessing, model training, evaluation, and visualization.
- `Crop_Yield_Classification_Report.docx`: Detailed project report including code, methodology, results, and references.
- `confusion_matrix.png`: Screenshot of the model's confusion matrix.
- `README.md`: Project overview and setup instructions.

## 🧠 Problem Statement

Accurate crop yield prediction is essential for effective agricultural planning and food security. This project classifies yield outcomes based on soil conditions and climate data to assist farmers and agronomists in making informed decisions.

## 🔍 Features Used

- `soil_quality`: A categorical indicator of soil richness.
- `rainfall`: Recorded rainfall for a particular period.
- `seed_type`: Type or category of seed used.

## 🛠️ Methodology

1. **Data Preprocessing**: Handle missing values and encode categorical variables.
2. **Train-Test Split**: Data is divided into training and testing sets using an 80-20 split.
3. **Feature Scaling**: StandardScaler is used to normalize the feature values.
4. **Model Training**: A Random Forest Classifier is trained with optimized hyperparameters.
5. **Evaluation**: The model's performance is evaluated using accuracy, precision, recall, and a confusion matrix.

## ✅ Results

- **Model**: Random Forest Classifier
- **Accuracy**: Refer to report for exact metric
- **Precision**: Refer to report for exact metric
- **Recall**: Refer to report for exact metric
- Confusion matrix visualizes classification performance.

## 📊 Visualizations

- Confusion matrix heatmap for better understanding of prediction accuracy across classes.
- Feature importance bar chart to understand model decision factors.

## 📦 Requirements

- Python 3.8+
- pandas
- seaborn
- matplotlib
- scikit-learn

Install the dependencies using:

```bash
pip install -r requirements.txt
```

## 📎 References / Credits

- Dataset: Provided as `crop_yield.csv`
- Libraries: pandas, seaborn, matplotlib, scikit-learn
- Confusion matrix and evaluation metrics follow standard ML practices.
