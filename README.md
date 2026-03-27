# Random Forest Classification using Mushroom Dataset

 ## Project Overview
This project applies the **Random Forest Classification algorithm** to the **Mushroom Dataset** in order to classify mushrooms as **edible** or **poisonous** based on their physical characteristics.

The notebook includes:
- data loading
- data exploration
- preprocessing
- model training
- prediction
- model evaluation
- feature importance analysis

This project demonstrates the use of **machine learning for classification problems** using a structured categorical dataset.

---

## Aim
To build a **Random Forest Classification model** using the Mushroom dataset and evaluate its performance.

---

## Objectives
- Read the dataset from a CSV file
- Understand the dataset structure
- Perform exploratory data analysis
- Encode categorical data into numerical format
- Train a Random Forest Classifier
- Evaluate the model performance
- Analyze feature importance

---

##  Dataset Information
The dataset used in this project is the **Mushroom Dataset**, which contains various physical and biological characteristics of mushrooms.

Each row represents a mushroom sample, and the target variable indicates whether the mushroom is:

- **e** → edible
- **p** → poisonous

### Example features include:
- cap shape
- cap color
- odor
- gill size
- stalk shape
- habitat

Since the dataset contains mostly **categorical features**, label encoding is used before training the machine learning model.

---

##  Technologies and Libraries Used

### Programming Language
- Python

### Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter notebook

---

##  Machine Learning Algorithm Used
### Random Forest Classifier

Random Forest is an **ensemble learning algorithm** that builds multiple **decision trees** and combines their predictions to improve classification accuracy and reduce overfitting.

It is highly effective for classification tasks and works well with structured datasets like the Mushroom dataset.

---

##  Workflow of the Project

The project follows the below machine learning pipeline:

1. **Import Required Libraries**
2. **Read the Dataset**
3. **Explore the Dataset**
4. **Check Class Distribution**
5. **Encode Categorical Features**
6. **Split Data into Training and Testing Sets**
7. **Train the Random Forest Model**
8. **Make Predictions**
9. **Evaluate the Model**
10. **Analyze Feature Importance**

---

##  Evaluation Metrics Used
The model performance is evaluated using:

- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report**
- **Training vs Testing Accuracy**
- **Feature Importance**
- **Permutation Importance**

These metrics help measure both the accuracy and interpretability of the model.

---

##  Visualizations Included
This project includes the following visual outputs:

- Class Distribution Plot
- Correlation Heatmap
- Confusion Matrix
- Feature Importance Graph
- Permutation Importance Graph
- Accuracy Comparison Plot

---

##  Key Highlights
- Clean and well-structured machine learning notebook
- Proper preprocessing of categorical data
- Use of Random Forest for classification
- Strong evaluation using multiple metrics
- Feature importance analysis for better model interpretation

---


### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/random-forest-mushroom-project.git
