
## Malaria Prognosis Using Logistic Regression

This project implements a binary logistic regression model to predict malaria prognosis based on patient symptoms and demographic factors. The goal is to support healthcare workers in diagnosing malaria, especially in resource-limited settings where diagnostic tools may be unavailable. The dataset includes 337 patients with various symptoms, and the model identifies key symptoms that are predictive of malaria, such as headache and hypoglycemia.

1. **Data**
   - The dataset used in this project contains patient demographics (age, sex) and symptoms like fever, cold, rigor, fatigue, headache, diarrhea, and more.
   - Data was collected from suspected malaria cases at the Federal Polytechnic Medical Centre, Ilaro.

2. **Model**
   - The project uses a binary logistic regression model to predict the probability of malaria based on the symptoms.
   - Key performance metrics include accuracy, precision, recall, F1 score, and ROC-AUC, providing insight into how well the model identifies malaria cases.
   - Significant predictors such as headache and hypoglycemia are highlighted in the model.

3. **Requirements**
   - Python 3.x
   - Libraries: pandas, scikit-learn, statsmodels, numpy, matplotlib

4. **Installation**
   - Clone this repository:
     ```bash
     git clone https://github.com/username/malaria-prognosis-logistic-regression.git
     cd malaria-prognosis-logistic-regression
     ```
   - Install the required libraries:
     ```bash
     pip install -r requirements.txt
     ```

5. **Usage**
   - Run the model:
     ```bash
     python malaria_model.py
     ```
   - The model will output key metrics like accuracy, precision, recall, F1 score, and ROC-AUC for model evaluation.

6. **Model Evaluation**
   - **Accuracy**: Measures overall correctness of the model.
   - **Precision**: Focuses on the correct positive malaria predictions.
   - **Recall**: Measures how well the model identifies true malaria cases.
   - **F1 Score**: A balance between precision and recall.
   - **ROC-AUC**: Assesses the model’s ability to distinguish between positive and negative cases.

7. **Future Improvements**
   - Expand the dataset with more clinical and environmental factors.
   - Explore advanced machine learning models like decision trees or random forests.
   - Deploy the model in real-time applications via mobile or web-based tools.

8. **Contributing**
   - Contributions to improve the model are welcome! Please submit pull requests or raise issues for discussion.

9. **License**
   - This project is licensed under the MIT License.

10. **Contact**
    - For further information or queries, feel free to contact the repository maintainer at ibkfresh@gmail.com.

---

This model aims to support healthcare professionals in diagnosing malaria by leveraging data-driven insights from patient symptoms. By using logistic regression, the model provides a practical and interpretable solution for malaria prognosis in regions with limited resources.
