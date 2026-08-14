# 📄 Conversational PDF Chatbot

This project allows users to **upload PDF files** and **chat with the content** in a conversational format. It uses **LangChain**, **vector databases**, and **Streamlit** to provide a smart and interactive user experience.

---

## 🚀 Features

- Upload and parse PDF documents
- Store PDF content as embeddings in a vector database
- Use LangChain for contextual question-answering
- Interactive front-end built with Streamlit

---

## 🧰 Tech Stack

| Component       | Technology                  |
|----------------|-----------------------------|
| Language        | Python                      |
| UI Framework    | Streamlit                   |
| NLP Framework   | LangChain                   |
| Embeddings      | OpenAI / HuggingFace        |
| Vector Store    | FAISS / Chroma / Pinecone   |
| PDF Parsing     | PyMuPDF / pdfminer.six      |

---

## 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/pdf-chatbot.git
cd pdf-chatbot
```

2. **(Optional) Create a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Configure environment variables**

Create a `.env` file in the root directory with the following content:

```
OPENAI_API_KEY=your_openai_key
```

---

## 🧠 How It Works

1. The user uploads a PDF via Streamlit.
2. The file is parsed and split into text chunks.
3. Each chunk is embedded using a language model and stored in a vector DB.
4. A user question is embedded and matched against stored chunks.
5. LangChain uses the most relevant chunks to generate a conversational answer.

---

## ▶️ Usage

Run the app using Streamlit:

```bash
streamlit run app.py
```

Then, upload a PDF and ask questions through the web interface.

## ✅ To-Do

- Add support for multiple
