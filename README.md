
# 🏠 Real Estate Chatbot

Interact with your real estate CSV data using natural language! This Streamlit app leverages LangChain, HuggingFace embeddings, and Llama-2 for conversational Q&A on property datasets.

---

## 🚀 Features

* 📄 **CSV Upload**: Upload any real estate CSV file and chat with your data.
* 🤖 **Conversational AI**: Uses Llama-2 (via CTransformers) for natural language answers.
* 🧠 **Semantic Search**: Embeddings via HuggingFace and FAISS for relevant document retrieval.
* 💬 **Chat History**: Maintains session history for context-aware responses.

---

## 🛠️ Setup Instructions

1. **Python 3.8+ required**
2. Create a virtual environment:
	```bash
	python -m venv .venv
	.\.venv\Scripts\activate
	```
3. Install dependencies:
	```bash
	pip install -r req.txt
	```
4. Launch the app:
	```bash
	streamlit run app.py
	```

---

## 📊 How It Works

* Upload a CSV file (e.g., `zameenkarachi.csv`).
* The app loads your data, creates embeddings, and builds a FAISS vector store.
* Ask questions about your data (e.g., "Show properties in Karachi under 1 crore").
* The chatbot uses Llama-2 to answer based on your CSV content.

---

## 🧩 Main Libraries Used

* Streamlit
* LangChain
* HuggingFace Embeddings
* FAISS
* CTransformers (Llama-2)

---

## 📂 Project Structure

```
Real_Estate_chatbot/
├── app.py              # Streamlit app
├── req.txt             # Requirements
├── zmeenkarachi.csv    # Example dataset
└── README.md           # Documentation
```

---

## 👤 Author

Syed Muhammad Muzammil Shah

---

## 📃 License

Open-source under the MIT License.
