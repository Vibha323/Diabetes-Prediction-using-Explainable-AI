# Enhancing Diabetes Prediction using Explainable AI (XAI)

This project focuses on predicting diabetes using a deep-learning model enhanced with **Explainable AI (XAI)** techniques. The goal is to build a highly accurate model while ensuring transparency using methods like **SHAP**, **LIME**, and **DICE counterfactuals**, which are essential for clinical decision-making and trust in healthcare AI systems.

## Key Features

-  **Deep Learning model** for diabetes prediction  
- Achieved **~97% accuracy**  
- Model explainability using:
  - **SHAP** – feature importance visualization  
  - **LIME** – local explanations for individual predictions  
  - **DICE** – counterfactual examples (what needs to change to switch prediction)  
- Identifies key clinical features such as:
  - HbA1c_level  
  - Insulin  
  - Miglitol  
  - Repaglinide  
- Helps improve transparency, trust, and potential clinical usability

---

##  **Files in this Repository**

- **`Diabetes_Prediction_XAI.ipynb`**  
  Complete Jupyter Notebook containing:
  - Data preprocessing  
  - Deep learning model  
  - SHAP, LIME, and DICE explanations  
  - Visualizations and interpretations  

- **Project Presentation**
- Enhancing Diabetes Prediction using Explainable AI.pptx`

---

## **Technologies & Libraries Used**

- Python  
- TensorFlow / Keras  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib  
- **SHAP**  
- **LIME**  
- **DICE-ML**

---

##  **Model Performance**

- **Accuracy:** ~97%  
- Loss: ~0.08  
- Strong interpretability using SHAP & LIME  
- Counterfactuals show how feature changes affect prediction outcomes  
