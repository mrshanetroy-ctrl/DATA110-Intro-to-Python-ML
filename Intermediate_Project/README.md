# Intermediate Project – Iris Flower Classification

## Description
This project uses the Iris dataset to classify flowers into three species — Setosa, Versicolor, and Virginica — based on measurements of their petals and sepals. The goal is to analyze the dataset, visualize important patterns, and build a machine learning model for classification.

## Dataset
- **Source:** Kaggle / Scikit-Learn Iris Dataset  
- **Features:**
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  
- **Target:** Iris species (Setosa, Versicolor, Virginica)

## Steps Performed

### 1. Data Cleaning
- Loaded dataset from sklearn  
- Checked for missing values (none)  
- Verified column types  
- Basic formatting and structure checks  

### 2. Exploratory Data Analysis (EDA)
- Dataset shape and summary  
- Statistical distribution  
- Class distribution  
- Relationship between features  

### 3. Visualization
- Pairplot (feature-to-feature relationships)  
- Countplot of species  
- Scatter plots (petal vs sepal measurements)  
- Correlation heatmap  

### 4. Model Building
- Train–test split (80%/20%)  
- Models used:
  - Logistic Regression  
  - KNN Classifier  
- Accuracy evaluation on test set  

## Results
- Accuracy: **95% – 100%** depending on the model  
- KNN gave slightly better results  
- Petal Length & Petal Width are the strongest predictors  
- Species are well-separated in feature space  

## Tools Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colab  

## Conclusion
The Iris dataset is clean and easy to analyze. After visualization and modeling, the trained classifiers achieved very high accuracy. The project demonstrates strong understanding of EDA, visualization, and machine learning basics.

## Author
Shanet P Roy
