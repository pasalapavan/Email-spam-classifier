# 📧 Email Spam Classifier

A simple **Machine Learning web app** built with **Streamlit** that classifies emails as **Spam** or **Not Spam**.  
Users can paste the content of any email into the app, and the model will predict whether it's spam.

---

## 🚀 Features
- Paste email text directly into the website.
- Get instant prediction: **Spam** or **Not Spam**.
- Uses **TF-IDF Vectorizer** and **Machine Learning model** trained on email datasets.
- Lightweight and easy to run locally.

---

## 🛠️ Tech Stack
- **Python 3.9+**
- **Streamlit** – for the web interface
- **Scikit-learn** – for ML model
- **Pickle** – for saving/loading trained models

---

## 📂 Project Structure
📦 email-spam-classifier
┣ 📂 python code

┃ ┣ app.py # Streamlit app

┃ ┣ model.pkl # Trained ML model

┃ ┣ vectorizer.pkl # TF-IDF vectorizer

┃ ┗ requirements.txt # Dependencies

┗ README.md


---

## ⚡ Installation & Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/email-spam-classifier.git
   cd email-spam-classifier/python\ code


2. Create a virtual environment:

   python3 -m venv .venv
source .venv/bin/activate   # On Mac/Linux
.venv\Scripts\activate      # On Windows




3. Install dependencies:

   pip install -r requirements.txt


4. Run the Streamlit app:

   streamlit run app.py
