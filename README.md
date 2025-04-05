# bert-chatbot-

# 🤖 BERT Chatbot using Streamlit

This project is a **BERT-powered chatbot** that intelligently responds to user queries using semantic similarity. Built with `Streamlit` for the front-end, this chatbot compares your input to a set of predefined questions and replies accordingly!

---

## 🎯 Features

- Uses BERT embeddings to understand the context
- Computes cosine similarity to match user input with predefined questions
- Beautiful custom background image for an aesthetic UI
- Interactive frontend with Streamlit

---

## 🧰 Tech Stack

- **BERT (via Hugging Face Transformers)** – To extract meaningful sentence embeddings
- **PyTorch** – For handling BERT model architecture
- **Scikit-learn** – For cosine similarity
- **Streamlit** – Frontend web UI
- **Python** – Core logic

---

## 🛠️ How to Run

1. Clone this repository
2. Install dependencies
3. Run the chatbot app

```bash
git clone https://github.com/yourusername/bert-chatbot.git
cd bert-chatbot
pip install -r requirements.txt
streamlit run chatbot_app.py
