# Diabetes Prediction System

This project is a Machine Learning web application designed to predict whether a patient is likely to have diabetes. It uses a pre-trained model and provides a user-friendly interface for entering medical details and getting an instant prediction.

## 🔍 Project Description

The application analyzes specific health metrics—such as Glucose levels, Blood Pressure, and BMI—to classify a patient as **Diabetic** or **Non-Diabetic**. It is built using Python and deployed with a Flask web server, making it easy to run and test locally.

## 📊 Dataset Details

The model is trained on the **Pima Indians Diabetes Dataset**.
* **Source:** National Institute of Diabetes and Digestive and Kidney Diseases.
* **Input Features:**
    1. **Pregnancies:** Number of times pregnant
    2. **Glucose:** Plasma glucose concentration
    3. **Blood Pressure:** Diastolic blood pressure (mm Hg)
    4. **Skin Thickness:** Triceps skin fold thickness (mm)
    5. **Insulin:** 2-Hour serum insulin (mu U/ml)
    6. **BMI:** Body mass index
    7. **Diabetes Pedigree Function:** Genetic score of diabetes likelihood
    8. **Age:** Age in years

## 🛠️ Technologies Used

* **Backend:** Python (Flask)
* **Frontend:** HTML, CSS
* **Machine Learning:** Scikit-Learn, Pandas, NumPy
* **Model Type:** Classification (Logistic Regression / Random Forest)

## 🚀 How to Run this Project

Follow these steps to get the application running on your computer:

### 1. Navigate to the Project Directory
Open your terminal or command prompt and ensure you are inside the correct folder:
```bash
cd "B7. Diabetes Prediction"
````

### 2\. Install Required Libraries

Run the following command to install the necessary Python packages:

```bash
pip install flask pandas numpy scikit-learn
```

### 3\. Start the Application

Run the main Python file:

```bash
python app.py
```

### 4\. View in Browser

Once the server starts, you will see a link in the terminal (usually `http://127.0.0.1:5000/`). Open this link in your web browser to use the app.

## 📝 Future Improvements

  * Add more advanced visualizations to the result page.
  * Improve the model accuracy with Hyperparameter tuning.
  * Deploy the application to the cloud (e.g., Render or AWS).

-----

*This project was developed for educational purposes.*

```
```
