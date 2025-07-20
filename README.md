💼Employee Salary Prediction using KNN 
This project is a machine learning-based web application that predicts whether a person's income exceeds $50K annually based on demographic data. Built with Python, trained using a supervised learning algorithm - KNN, and deployed using Streamlit for an interactive interface.

📄 Overview
This project focuses on building a robust classification model to predict whether an individual's annual income exceeds $50K based on demographic and employment-related attributes. The model leverages the K-Nearest Neighbors (KNN) algorithm, enhanced with GridSearchCV for hyperparameter tuning to achieve optimal performance.

🎯 Objective
To implement a machine learning solution capable of accurately classifying income levels by:
1. Preprocessing and encoding real-world data
2. Applying the KNN algorithm for classification
3. Optimizing model parameters using GridSearchCV
4. Evaluating model performance using standard classification metrics
5. Deploying the model through an interactive Streamlit web application

⚙️ Tools and Techniques
**Algorithm:** K-Nearest Neighbors (KNN)

**Hyperparameter Tuning:** GridSearchCV

**Performance Metrics:** Accuracy, Precision, Recall, F1-Score

**Visualization & Deployment:** Streamlit

**Preprocessing:**  Label Encoding, Min-Max Scaler

📊 Dataset Description
The model uses a structured dataset with attributes including:
Age, workclass, education, marital-status, occupation, relationship, race, gender, capital-gain, capital-loss, hours-per-week, native-country, and income (target variable)

✅ Key Outcomes
1. Achieved improved classification accuracy through optimal hyperparameter selection (n_neighbors)
2. Enhanced model reliability using feature scaling and encoding
3. Developed a responsive user interface for real-time predictions via Streamlit
4. Provided clear and interpretable results to assist in understanding income-level prediction patterns

🛠️ How to Use
1. Clone the repository
2. Install dependencies using pip install -r requirements.txt
3. Run the application using streamlit run app.py
4. Use the web interface to input values and view income predictions

