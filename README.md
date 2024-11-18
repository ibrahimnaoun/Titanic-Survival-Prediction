# Titanic Survival Prediction 🚢💥

In this project, we use machine learning to predict whether passengers aboard the Titanic survived or not based on certain features like their class, age, and gender. The models used are **Logistic Regression** and **Support Vector Machine (SVM)**.

### 🤖 **Models Used**
- **Logistic Regression**: A simple linear model for binary classification.
- **Support Vector Machine (SVM)**: A more complex model that works well for classification tasks.

### 📊 **Evaluation**
The models were evaluated using the following metrics:

- **Accuracy**: The percentage of correct predictions.
- **Confusion Matrix**: Shows how well the model performed across different classes.
- **Precision, Recall, and F1-Score**: For a deeper understanding of model performance.
- **ROC & AUC**: To visualize the trade-off between true positive rate and false positive rate.

#### **Results**:
- **Logistic Regression Accuracy**: 0.80
- **SVM Accuracy**: 0.79

**Logistic Regression** performed slightly better, so it was chosen as the final model for this project.

### 📝 **Conclusion**
- The **Logistic Regression** model was able to predict survival with an accuracy of 80%.
- **Key features**: **Pclass**, **Age**, and **Sex** were the most important in making predictions.
- This model can be used as a basis for further improvements, like adding more features or trying other advanced algorithms like **XGBoost**.

### 🚀 **Next Steps**
- **Improve Model**: Hyperparameter tuning, adding new features like family size, or trying models like **Random Forest**.
- **Deploy Model**: Make the model available for real-time predictions via a web app or API.
