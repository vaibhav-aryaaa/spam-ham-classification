# 📧 Spam vs Ham Classification using Word2Vec & AvgWord2Vec

This project focuses on **email/SMS spam detection** using **semantic word embeddings** instead of traditional bag-based methods.  
It leverages **pre-trained Word2Vec (Google News – 300 dimensions)** and **Average Word2Vec** for sentence-level feature extraction.

The entire workflow is implemented in a **single Jupyter Notebook (.ipynb)**.

---

## 📁 Dataset

The dataset used in this project is the **SMS Spam Collection Dataset**.

🔗 Dataset Link:  
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

---

## 🚀 Project Objective

To build a machine learning model that can accurately classify messages as **Spam** or **Ham** by understanding the **semantic meaning of words**, not just their frequency.

---

## 🧠 Concepts & Techniques Used

- Natural Language Processing (NLP)
- Pre-trained **Word2Vec (Google News)**
- **Average Word2Vec (AvgWord2Vec)** for sentence embeddings
- Text preprocessing
  - Lowercasing
  - Tokenization
  - Stopword removal
- Machine Learning
  - **Random Forest Classifier**
- Model Evaluation
  - Accuracy Score
  - Classification Report

---

## 🛠️ Tech Stack

- Python 🐍
- Jupyter Notebook
- Gensim
- NLTK
- Scikit-learn
- Pandas
- NumPy

---

## 📊 Workflow

1. Load the Spam/Ham dataset
2. Perform text preprocessing
3. Load **Google News pre-trained Word2Vec (300d)**
4. Convert each message into a vector using **AvgWord2Vec**
5. Split data into training and testing sets
6. Train **Random Forest Classifier**
7. Evaluate model using accuracy and classification report

---

## 📈 Results

- The model successfully captures **semantic relationships** between words
- AvgWord2Vec significantly improves representation over Bag-of-Words
- Achieves strong performance in classifying spam vs ham messages

📌 *Exact evaluation metrics are available in the notebook output.*

---

## 🧪 How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/your-username/Spam-Ham-Word2Vec.git

2. Open the notebook.

3. Run all cells sequentially.

⚠️ Note:
The notebook uses Google Drive mounting (Colab).
Update the dataset path if running locally.
