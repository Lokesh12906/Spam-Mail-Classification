# Spam Email Classifier

A machine learning-based web application that classifies text messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) and a trained Scikit-learn model. The application is built with **Python**, **Flask**, and **Scikit-learn**.

---

## Features

* Detects whether a message is Spam or Ham
* Web interface built using Flask
* Text preprocessing and vectorization
* Pre-trained machine learning model for fast predictions
* Simple and lightweight application

---

## Technologies Used

* Python
* Flask
* Scikit-learn
* Pandas
* NumPy
* Joblib

---

## Project Structure

```text
Spam-Email-Classifier/
│── app.py
│── README.md
│── requirements.txt
│── spam.csv
│── model.pkl
│── vectorizer.pkl
│
└── templates/
    ├── index.html
    └── result.html
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Lokesh12906/spam-email-classifier.git
```

Navigate to the project directory:

```bash
cd spam-email-classifier
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

---

## Machine Learning Pipeline

1. Load the dataset.
2. Preprocess the text messages.
3. Convert text into numerical features using a vectorizer.
4. Train a machine learning classifier.
5. Save the trained model using Joblib.
6. Predict whether new messages are Spam or Ham.

---

## Future Improvements

* Support multiple machine learning models
* Display prediction confidence score
* Deploy using Render or Heroku
* Improve UI with Bootstrap
* Email attachment analysis
* REST API support

---

## License

This project is licensed under the MIT License.
