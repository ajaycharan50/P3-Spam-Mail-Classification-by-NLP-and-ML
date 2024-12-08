# <span style="color:#4CAF50;">P3: Spam Mail Classification using NLP and ML</span>  

### 📋 **Project Description**  
Spam emails disrupt communication and pose security risks. This project implements a spam email classification system using **Natural Language Processing (NLP)** and **Machine Learning (ML)** to identify spam and non-spam (ham) emails. The solution is deployed as a user-friendly **Streamlit** application for real-time email classification.  

---

## 🚀 **Features**  
- Real-time email spam classification.  
- NLP-based preprocessing of email content.  
- Machine learning-powered spam detection with Naïve Bayes.  
- Easy-to-use web interface built with **Streamlit**.  

---

## 🌐 **Access the Deployed Application**  
Test the project online using the deployed application:  
👉 **[Spam Mail Classifier Application](https://p3-spam-mail-classification-by-nlp-and-ml-y59vavcjlgbznpssgkwy.streamlit.app/)**  

---

## 🛠️ **Technologies Used**  
- **Programming Language:** Python  
- **Frameworks/Libraries:**  
  - scikit-learn  
  - pandas  
  - numpy  
  - Streamlit  
- **Preprocessing Tools:**  
  - CountVectorizer (for feature extraction)  
  - NLTK/spaCy (for text cleaning)  

---

## 📂 **Project Structure**  

├── spam_dataset.csv # Dataset (replace with your actual dataset) ├── spamDetector.py # Streamlit application script ├── spam.pkl # Trained ML model ├── vectorizer.pkl # Trained CountVectorizer ├── README.md # Project documentation └── requirements.txt # Python dependencies


---

## 💻 **How to Run the Project Locally**  

### **Step 1: Clone the Repository**  
```bash
git clone https://github.com/ajaycharan50/P3-Spam-Mail-Classification-by-NLP-and-ML.git
cd P3-Spam-Mail-Classification-by-NLP-and-ML

### **Step 2: Install Dependencies
Ensure Python 3.8 or higher is installed, then run:

bash
Copy code
pip install -r requirements.txt

### **Step 3: Run the Streamlit Application Locally
bash
Copy code
streamlit run spamDetector.py

## can directly access the deployed app or run it locally!
