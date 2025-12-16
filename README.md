🩺 Diabetes Prediction and Recommendation System Using Machine Learning
A machine learning–based system designed to predict diabetes and provide personalized health recommendations using patient medical data.
The project evaluates multiple ML algorithms and achieves high prediction accuracy, making it a useful tool for early diabetes detection and management.

📌 Project Overview
Diabetes is a chronic disease affecting millions worldwide. Early detection plays a crucial role in reducing complications and improving patient outcomes.
This project leverages machine learning techniques to:


Predict whether a patient is diabetic or not


Provide actionable recommendations based on prediction results


Compare multiple ML models to select the best-performing one


The system is built using the Pima Indian Diabetes Dataset and implemented in a Python & Jupyter Notebook environment Diabetes Prediction and Recomme….

📊 Dataset


Name: Pima Indian Diabetes Dataset


Source: Kaggle


Features include:


Age


BMI (Body Mass Index)


Blood glucose level


Blood pressure


HbA1c level


Physical activity


Daily calories


Smoking history


Diabetes type




The dataset was preprocessed to handle missing values and ensure data consistency before model training Diabetes Prediction and Recomme….

⚙️ Machine Learning Models Used
The following algorithms were trained and evaluated:


Random Forest Classifier


Support Vector Classifier (SVC)


Gradient Boosting Classifier


The data was split into:


67% Training


33% Testing


Cross-validation was applied to ensure model robustness Diabetes Prediction and Recomme….

🏆 Model Performance
ModelAccuracyRandom Forest Classifier97% ✅Gradient Boosting Classifier88%Support Vector Classifier66%
Best Model: Random Forest 🌲


True Positives (TP): 1,185


True Negatives (TN): 18,042


Recall (Diabetic cases): 70%


This model achieved the highest accuracy and was selected as the final model Diabetes Prediction and Recomme….

🧠 Features


✅ Diabetes prediction (Yes / No)


📈 Model comparison & evaluation


📊 Data visualization (BMI vs Blood Glucose)


💡 Personalized recommendations, such as:


"Great, no diabetes! Keep it up."


Lifestyle and health suggestions based on prediction





🛠️ Technologies Used


Python


NumPy


Pandas


Matplotlib / Seaborn


Scikit-learn


Jupyter Notebook



▶️ How to Run the Project


Clone the repository:
git clone https://github.com/your-username/diabetes-prediction-system.git



Install dependencies:
pip install -r requirements.txt



Run the Jupyter Notebook:
jupyter notebook



Open the notebook and run all cells.



📌 Results & Discussion


The Random Forest model demonstrated excellent performance with 97% accuracy.


The system successfully predicted diabetes cases and generated personalized recommendations.


Future improvements may include:


Improving recall for diabetic cases


Handling class imbalance using SMOTE


Integrating real-time patient data





🚀 Future Work


Deploy the model as a web application


Improve recall for positive diabetes cases


Integrate wearable or real-time medical data


Enhance recommendation system with medical guidelines



📚 References


World Health Organization (WHO)


Centers for Disease Control and Prevention (CDC)


International Diabetes Federation (IDF)


Kaggle – Diabetes Prediction Dataset


(Full references are available in the research paper) Diabetes Prediction and Recomme…

👨‍💻 Author
Muhammed Khaled 
Developed as part of a machine learning project focused on healthcare analytics and early disease detection.
