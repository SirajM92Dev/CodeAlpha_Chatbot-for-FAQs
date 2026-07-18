# 🤖 FAQ Chatbot using TF-IDF and Cosine Similarity

A beginner-friendly Natural Language Processing (NLP) project that answers user questions by matching them with the most relevant Frequently Asked Questions (FAQs). The chatbot preprocesses text using NLTK, converts it into numerical vectors using TF-IDF, and finds the best match using Cosine Similarity.

---

## 📌 Features

* Accepts user questions in natural language
* Cleans and preprocesses text using NLTK
* Removes stopwords and punctuation
* Converts text into TF-IDF vectors
* Uses Cosine Similarity to find the most relevant FAQ
* Returns the corresponding answer
* Displays a message when no relevant question is found

---

## 🛠️ Technologies Used

* Python
* NumPy
* NLTK
* Scikit-learn

  * TfidfVectorizer
  * Cosine Similarity

---

## 📂 Project Structure

```
FAQ-Chatbot/
│
├── Internship project 1.ipynb   # Jupyter Notebook
├── README.md                    # Project documentation
└── requirements.txt             # Required libraries (optional)
```

---

## ⚙️ How It Works

1. Store FAQs and their corresponding answers.
2. Preprocess all questions by:

   * Converting to lowercase
   * Tokenizing text
   * Removing punctuation
   * Removing stopwords
3. Convert the cleaned questions into TF-IDF vectors.
4. Accept a user's question.
5. Preprocess the user's input using the same steps.
6. Calculate Cosine Similarity between the user's question and all FAQs.
7. Return the answer with the highest similarity score.
8. If the similarity score is below **0.50**, inform the user that no relevant answer was found.

---

## 📸 Example

**Input**

```
Tell us your question:
How can I get my money back?
```

**Output**

```
Similarity Score: 0.81

Answer:
You can request a refund from the Orders section within 7 days.
```

---

## 📚 Libraries Required

Install the required packages:

```bash
pip install numpy nltk scikit-learn
```

Download the required NLTK resources:

```python
import nltk

nltk.download("punkt")
nltk.download("stopwords")
```

---

## 🎯 Learning Outcomes

This project helped me understand:

* Text preprocessing
* Tokenization
* Stopword removal
* TF-IDF Vectorization
* Cosine Similarity
* Basic Natural Language Processing (NLP)
* Building a simple rule-based chatbot

---

## 🚀 Future Improvements

* Support larger FAQ datasets
* Add voice input
* Build a graphical user interface (GUI)
* Connect with a real database
* Deploy as a web application using Flask or Streamlit

---

## 👨‍💻 Author

**Siraj Muhammad**

Microsoft Certified: Azure AI Fundamentals (AI-900)

AI & Machine Learning Enthusiast | Python | NLP | Scikit-learn | NumPy | NLTK
