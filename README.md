# Classification using Decision Tree and Random Forest

This project demonstrates how tree-based machine learning models can be applied to classification problems. Two widely-used models — **Decision Tree Classifier** and **Random Forest Classifier** — are implemented and evaluated using a real-world medical dataset.

---
### 🌐 Google Colab
You can run the notebook directly in the cloud:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yaswanth-G2004/Decision-Trees-and-Random-Forests/blob/main/classification%20&%20regression.ipynb)

---

## Dataset

The dataset used is the [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset), which contains patient health-related attributes to predict the presence or absence of heart disease.

---

## Objective

- Build classification models using decision trees and random forests.
- Visualize model structure and outputs.
- Interpret feature importance.
- Evaluate model performance using test accuracy and cross-validation.

---

## Libraries Used

- `pandas` for data handling  
- `matplotlib` for plotting  
- `scikit-learn` for model building and evaluation

---

## Code Explanation

- The dataset is loaded using `pandas`, and initial data exploration is performed to understand the structure.
- The features and target labels are separated for model training.
- The data is split into training and testing sets to measure generalization ability.
- A **Decision Tree Classifier** is trained with a limited depth to avoid overfitting. The tree is visualized using `plot_tree`, which helps in understanding the decision logic.
- Model predictions are made and accuracy is calculated.
- A **Random Forest Classifier**, which builds multiple decision trees and combines their outputs, is trained for better accuracy and stability.
- Feature importances from the Random Forest are displayed to understand which features contribute most to predictions.
- **5-fold cross-validation** is used to measure how well the model generalizes across different data splits.

---

## Model Performance

| Model              | Accuracy (%) |
|-------------------|--------------|
| Decision Tree      | *Fill your value* |
| Random Forest      | *Fill your value* |
| Cross-Validation   | **99.71%**   |

---

## Key Features

- Decision tree structure visualization  
- Random forest ensemble learning  
- Feature importance interpretation  
- Cross-validation for reliability

---

## How to Run

### ✅ Local Setup
1. Clone the repository.
2. Install required libraries using pip:
   ```bash
   pip install pandas matplotlib scikit-learn
   ```
3. Open the `.ipynb` file in Jupyter Notebook and run all cells.


## File Included

- `classification & regression.ipynb` – Jupyter Notebook with all code, outputs, and visualizations.

---

## Conclusion

Tree-based models are among the most interpretable and flexible tools in supervised learning. The **Decision Tree** offers a clear visualization of decision-making, making it great for insights, but it can overfit. The **Random Forest** mitigates this by combining multiple trees, resulting in better accuracy and generalization.

This project shows that Random Forests not only improve performance but also offer insight into feature importance, making them especially valuable in sensitive domains like healthcare, where both accuracy and interpretability are crucial.

---
## 👨‍💻 Author

**Garikipati Yaswanth**  
📧 Email: garikipatiyaswanth2004@gmail.com  
🔗 [GitHub](https://github.com/Yaswanth-G2004)  
🔗 [LinkedIn](https://www.linkedin.com/in/yaswanth-garikipati-516821288)

---
