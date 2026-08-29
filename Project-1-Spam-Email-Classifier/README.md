# 📧 Spam Email Classifier

This project is a simple **Machine Learning-based Spam Email Classifier** that can identify whether an email is **Spam** or **Not Spam (Ham)**.

The model analyzes the content of an email and uses **TF-IDF** to convert the text into numerical features. These features are then passed to a **Multinomial Naive Bayes** classifier to predict the email category.

## 🚀 Features

* Classifies emails as **Spam** or **Not Spam**
* Uses **TF-IDF** for text feature extraction
* Uses **Multinomial Naive Bayes** for classification
* Built completely with Python and Scikit-learn
* Simple to train and run locally

## 🛠️ Technologies Used

* **Python**
* **Pandas** – for handling the dataset
* **Scikit-learn** – for machine learning
* **TF-IDF** – for converting email text into numerical features
* **Multinomial Naive Bayes** – for spam classification

## ⚙️ How the Project Works

The classifier follows a simple process:

**Email Text → TF-IDF Vectorization → Naive Bayes Model → Spam / Not Spam**

First, the email text is converted into numerical values using TF-IDF. The trained Naive Bayes model then uses these values to determine whether the email is spam or a legitimate email.

## 📂 Project Structure

```text
Spam-Email-Classifier/
│
├── train_model.py       # Trains the machine learning model
├── app.py               # Runs the spam classifier application
├── dataset.csv          # Email dataset
├── requirements.txt     # Required Python libraries
└── README.md            # Project documentation
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <your-repository-link>
cd Spam-Email-Classifier
```

### 2. Install the required libraries

```bash
pip install -r requirements.txt
```

### 3. Train the model

```bash
python train_model.py
```

### 4. Run the application

```bash
python app.py
```

Now you can enter an email message and check whether the model identifies it as **Spam** or **Not Spam**.

## 🎯 Project Objective

The main objective of this project is to understand how **Natural Language Processing (NLP)** and **Machine Learning** can be used to automatically classify text-based messages.

This project also provides practical experience with text preprocessing, feature extraction, model training, and classification.

## 🔮 Future Improvements

Some possible improvements for this project are:

* Improve the model's accuracy with a larger dataset
* Add more text preprocessing techniques
* Compare different machine learning algorithms
* Create a web-based interface
* Add model performance graphs and evaluation metrics

## 👨‍💻 Author

**Aman Kumar**

This project was created as a practical Machine Learning project to explore **NLP and text classification**.
