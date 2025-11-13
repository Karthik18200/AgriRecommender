

# **Crop Recommendation System – Mysuru Region**

This project provides a machine learning–based crop recommendation tool designed for the Mysuru region. It analyzes soil nutrients and environmental conditions to suggest the most suitable crop. The model is trained using regional agricultural data and is integrated into a Django web application for easy use.

---

## **Features**

* Predicts the best crop for given conditions
* Uses inputs such as N, P, K, pH, rainfall, temperature, humidity, and soil type
* Built using a Random Forest classifier
* Django interface for submitting inputs and viewing predictions
* Region-focused dataset for improved accuracy

---

## **How It Works**

1. Dataset is prepared with soil nutrients and environmental factors
2. Soil type and crop labels are encoded
3. A Random Forest model is trained and saved
4. Django app collects user input and passes it to the model
5. The system returns the recommended crop based on the input values

---

## **Project Structure**

```
/project
│── crop_model.pkl
│── soil_encoder.pkl
│── crop_encoder.pkl
│── train_model.py
│── ml_model.py
│
│── django_app/
│   ├── manage.py
│   ├── db.sqlite3
│   ├── templates/
│   └── static/
```

---

## **Technology Used**

* Python
* scikit-learn
* Django
* Pandas, NumPy
* Joblib

---

## **Running the Project**

### Install dependencies:

```
pip install -r requirements.txt
```

### Run the Django server:

```
python manage.py runserver
```

Open in browser:
[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## **Author**

**Karthik C**
Information Science Engineering
Interested in machine learning, backend development, and web technologies.

