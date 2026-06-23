
<img width="1461" height="312" alt="Screenshot 2026-06-23 152906" src="https://github.com/user-attachments/assets/ef82b37c-d1cc-4644-af1d-724be09d2352" />
<img width="1418" height="322" alt="Screenshot 2026-06-23 152918" src="https://github.com/user-attachments/assets/8d6345d2-01f4-4aa7-8305-568eacb62eaf" />

<img width="612" height="502" alt="Screenshot 2026-06-23 150847" src="https://github.com/user-attachments/assets/48ef8a48-41e5-4fe0-9779-36f01576a0f9" />
<img width="652" height="472" alt="Screenshot 2026-06-23 150904" src="https://github.com/user-attachments/assets/623023b9-958c-469a-a9c1-badf0cb765c4" />
<img width="677" height="467" alt="Screenshot 2026-06-23 150915" src="https://github.com/user-attachments/assets/1ab88b76-bfb7-4dde-8ad9-ff2759e176c7" />






# breast-tumor-detection-using-machine-learning

# 🧬 Breast Cancer Prediction System using Machine Learning

A Machine Learning project to classify breast tumors as **Benign (0)** or **Malignant (1)** using classification algorithms, feature scaling, and model evaluation metrics.

---

------------------------------🚀 Project Overview------------------------------------

This project uses a supervised machine learning model to predict breast cancer based on medical features.  
The model achieves high accuracy with proper preprocessing and evaluation.

---

#------------------------------------📂 Dataset----------------------------------
- Dataset contains tumor-related medical features
- Target column: `diagnosis`
  - 0 → Benign
  - 1 → Malignant



--------------------------------------⚙️ Workflow------------------------------------

----------------------------------------Data Preprocessing-----------------------------
- Dropped unnecessary columns
- Encoded diagnosis column
- Feature scaling using `StandardScaler`


---------------------------📌 Feature Scaling-------------------------------------

StandardScaler used to normalize features for better model performance.

------------------------------📌 Train-Test Split----------------------------------

Dataset split into training and testing sets.

----------------------------------📌 Model Training-------------------------------------

Logistic Regression model used for classification.

Model Evaluation Results
Accuracy: 96.49%
Precision: 97.5%
Recall: 92.8%
F1 Score: 95.1%

📋 Classification Report
              precision    recall  f1-score   support

           0       0.96      0.99      0.97        72
           1       0.97      0.93      0.95        42

    accuracy                           0.96       114
   macro avg       0.97      0.96      0.96       114
weighted avg       0.97      0.96      0.96       114


👨‍💻 Author
Abhishek Dhakad
