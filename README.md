# YT-WEBSITE_SUMMARIZER
# 🎥🌐 YouTube & Website Summarizer using LangChain

An AI-powered summarization application built with **LangChain**, **Groq LLM**, **Streamlit**, and **UnstructuredURLLoader** that generates concise summaries from **YouTube videos** and **web pages**.

Simply paste a YouTube video URL or a website URL, and the application extracts the content and produces an easy-to-read summary using an LLM. LangChain provides document loaders such as `UnstructuredURLLoader` for web pages and integrates well with transcript-based YouTube loaders to simplify this workflow. :contentReference[oaicite:0]{index=0}

---

## 🚀 Features

- 🎥 Summarize YouTube videos
- 🌐 Summarize websites and online articles
- 🤖 Powered by Groq Llama 3.1
- ⚡ Fast and interactive Streamlit interface
- 📄 Extracts webpage content automatically
- 📚 Generates concise, readable summaries
- 🔑 Secure API key input
- 🧠 Built using LangChain document loaders

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- LangChain Community
- LangChain Groq
- Unstructured
- BeautifulSoup4
- Python-dotenv

---

## 📂 Project Structure

```text
YT-WEBSITE_SUMMARIZER/
│
├── app.py
├── requirements.txt
├── .env
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Maaddhhaav21/YT-WEBSITE_SUMMARIZER.git

cd YT-WEBSITE_SUMMARIZER
```

---

### 2. Create a Virtual Environment

Using **uv**

```bash
uv venv .venv --python 3.11 --seed

source .venv/bin/activate
```

Or using Python

```bash
python -m venv .venv

source .venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
uv pip install -r requirements.txt
```

---

## 🔑 Configure Groq API Key

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key
```

Or enter your API key directly in the Streamlit sidebar.

You can create a free API key from:

https://console.groq.com/keys

---

## ▶️ Run the Application

```bash
python -m streamlit run app.py
```

---

## 💡 Example Inputs

### YouTube

```
https://www.youtube.com/watch?v=xxxxxxxx
```

### Website

```
https://python.langchain.com/
```

---

## 🧠 How It Works

### For YouTube Videos

```text
YouTube URL
      │
      ▼
Transcript Extraction
      │
      ▼
LangChain Document
      │
      ▼
Groq LLM
      │
      ▼
Summary
```

### For Websites

```text
Website URL
      │
      ▼
UnstructuredURLLoader
      │
      ▼
Clean Text Extraction
      │
      ▼
Groq LLM
      │
      ▼
Summary
```

---

## 📸 Example

### Input

```
https://www.youtube.com/watch?v=example
```

### Output

```
This video explains Retrieval-Augmented Generation (RAG),
covering embeddings, vector databases, retrieval,
and how LLMs generate responses using external knowledge.
```

---

## 📦 Requirements

- Python 3.11+
- Groq API Key
- Internet Connection

---

## 🔮 Future Improvements

- 📄 PDF summarization
- 🎙️ Audio summarization
- 📹 Local video summarization
- 🌍 Multi-language summaries
- 📝 Bullet-point summaries
- 📥 Export summary as PDF or TXT
- 💬 Chat with summarized content
- 🧠 RAG over summarized documents

---

## 👨‍💻 Author

**Madhav Manoj**

B.Tech Computer Science Engineering

AI & Generative AI Enthusiast

GitHub:

https://github.com/Maaddhhaav21

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!

---

## 📄 License

This project is intended for educational and learning purposes.
