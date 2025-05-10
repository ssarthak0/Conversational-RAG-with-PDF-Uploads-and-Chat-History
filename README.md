# Conversational-RAG-with-PDF-Uploads-and-Chat-History


This application enables users to upload PDF documents and engage in a conversational Q&A interface powered by Retrieval-Augmented Generation (RAG). It leverages LangChain for document processing, HuggingFace embeddings for semantic understanding, Chroma as the vector store, and Groq's LLMs for generating responses.

---

## 🚀 Features

- 📄 Upload and process multiple PDF documents.
- 🤖 Interactive chat interface with conversational memory.
- 🔍 Context-aware question reformulation using chat history.
- 🧠 Retrieval-Augmented Generation for accurate answers.
- 🧰 Utilizes HuggingFace embeddings and Chroma vector store.
- 🔐 Secure API key management via environment variables.

---

## 📁 Project Structure

```
project-root/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── .env                   # Environment variables
├── README.md              # Project documentation
```

---

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ssarthak0/Conversational-RAG-with-PDF-Uploads-and-Chat-History
   cd Conversational-RAG-with-PDF-Uploads-and-Chat-History
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**

   Create a `.env` file in the project root with the following content:

   ```env
   GROQ_API_KEY=your_groq_api_key
   HF_TOKEN=your_huggingface_token
   ```

   Replace `your_groq_api_key` and `your_huggingface_token` with your actual API keys.

---

## 🧪 Usage

1. **Run the Streamlit application:**

   ```bash
   streamlit run app.py
   ```

2. **Access the application:**

   Open your browser and navigate to `http://localhost:8501`.

3. **Interact with the chatbot:**

   - Enter your Groq API key when prompted.
   - Upload one or more PDF documents.
   - Enter a session ID to track your conversation.
   - Ask questions related to the uploaded documents.

---

## 🧾 Requirements

The application relies on the following Python packages:

```
streamlit
python-dotenv
ipykernel
langchain
langchain-community
langchain-text-splitters
langchain-openai
langchain-chroma
langchain-huggingface
langchain-groq
chromadb
sentence_transformers
faiss-cpu
pypdf
pymupdf
pandas
openai
huggingface_hub
```

Ensure all dependencies are installed by running:

```bash
pip install -r requirements.txt
```

---


## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgments

- [LangChain](https://github.com/langchain-ai/langchain) for providing the framework for building LLM applications.
- [Streamlit](https://streamlit.io/) for the interactive web interface.
- [HuggingFace](https://huggingface.co/) for the embedding models.
- [Chroma](https://www.trychroma.com/) for the vector store implementation.
- [Groq](https://groq.com/) for the language models powering the chatbot.

---
