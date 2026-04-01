# 🤖 NLP Chatbot using Transformers

## 📌 Project Overview

This project is a **console-based chatbot** built using **Hugging Face Transformers**.
The chatbot interacts with users in natural language and generates meaningful responses using a **pre-trained transformer model**.

---

## 🎯 Objective

* Build an interactive chatbot using transformer-based models
* Understand how pre-trained NLP models work
* Generate human-like responses dynamically

---

## 🧠 Technologies Used

* Python 🐍
* Hugging Face Transformers 🤗
* PyTorch 🔥
* Google Colab / Jupyter Notebook

---

## ⚙️ Model Used

* **FLAN-T5 (google/flan-t5-base)**
  👉 Instruction-based transformer model for accurate question answering

---

## 🚀 Features

* Interactive console-based chatbot
* Uses transformer model (no full hardcoding)
* Hybrid approach (Transformer + rule-based fallback)
* Handles multiple user queries
* Exit condition (`exit` / `quit`)
* Clean and well-structured code

---

## 🔄 Chatbot Workflow

User Input → Processing → Response Generation → Output → Loop until exit

---

## 💬 Sample Interaction

```
Chatbot: Hello! I am your AI assistant. How can I help you today?

User: What is Artificial Intelligence?
Chatbot: Artificial Intelligence is the simulation of human intelligence in machines.

User: Who created Python?
Chatbot: Python was created by Guido van Rossum.

User: exit
Chatbot: Goodbye! Have a great day!
```

---

## 🛠️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/NLP-Chatbot-Transformers.git
```

2. Install dependencies:

```
pip install transformers torch
```

3. Run the notebook:

* Open `.ipynb` file in Jupyter Notebook / Colab
* Click **Run All**

---

## 📂 Project Structure

```
NLP-Chatbot-Transformers/
│
├── chatbot.ipynb
├── README.md
```

---

## 📊 Learning Outcomes

* Understanding transformer-based NLP models
* Using Hugging Face model hub
* Implementing text generation
* Building conversational AI systems

---

## 📌 Future Improvements

* Add GUI using Streamlit
* Improve response accuracy
* Add memory-based conversation
* Deploy as web application
.
