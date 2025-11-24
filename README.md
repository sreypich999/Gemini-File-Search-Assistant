# 📘 Gemini File Search Assistant (Google Colab Notebook)

A simple and powerful **Document Q&A / RAG tool** built entirely inside a single **Colab notebook**: 
It behaves like RAG, but you don’t build the RAG pipeline — no vector DB, no chunking, no embeddings, no indexing. Gemini File Search handles everything automatically.
**`Gemini File Search.ipynb`**

Upload a file → Ask questions → Get **grounded, cited answers** powered by Google’s **Gemini File Search API**.

---

## 🔗 Notebook

## 🚀 Open the Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yy9B81Fi-x_0Cp9cNI-gYVtxRGJYkwOE?usp=sharing)


This notebook contains:
- API setup  
- File upload  
- File Search Store creation  
- File ingestion  
- Grounded chat with citations  

Everything runs inside Colab — no installation needed.

---

## 🔗 Official Documentation

- Gemini File Search: https://ai.google.dev/gemini-api/docs/file-search  
- Gemini Python SDK: https://ai.google.dev/gemini-api/docs/python  
- Gemini Models Overview: https://ai.google.dev  

---

## 🌟 Why Gemini File Search?

The new **File Search Tool** gives you a complete **RAG engine** without needing any infrastructure.

### ❌ No Need For
- Vector DB  
- Chunking scripts  
- Embedding pipelines  
- Indexing logic  
- Retrieval servers  
- Manual OCR configuration
- Old “corpus” / “file stores” setup (SDK is auto-managed)
  
### ✅ Google Automatically Provides
- Free file storage  
- OCR (PDF/images, multilingual including Khmer)  
- Chunking  
- Embeddings  
- Indexing  
- Retrieval  
- Grounding  
- Auto-citations  



---

## 📸 Screenshots / Demo

### 🖼️ File Upload & Status
![Screenshot 1](https://github.com/sreypich999/Gemini-File-Search-Assistant/blob/main/image_2025-11-24_22-57-48.png)

### 💬 Chat With Your Document
![Screenshot 2](https://github.com/sreypich999/Gemini-File-Search-Assistant/blob/main/image_2025-11-24_23-00-43.png)

---

## 🚀 Features

- 100% notebook-based  
- Upload **PDF /docx**
- Automatic File Search Store creation  
- Automatic ingestion + indexing  
- Chat with your document  
- Grounded answers with citations  
- Works instantly on Google Colab  

---

## 📂 Project Structure

```
📁 Gemini-File-Search-Assistant
│── Gemini File Search.ipynb     # Main (and only) app
│── README.md
```

---

## ▶️ How to Use

### 1. Open the notebook  
https://colab.research.google.com/drive/1yy9B81Fi-x_0Cp9cNI-gYVtxRGJYkwOE?usp=sharing

### 2. Enter your Gemini API Key  
From https://ai.google.dev

### 3. Upload your document  
PDF, images, or text files.

### 4. Ask questions  
The notebook uses:
- File Search Tool  
- `gemini-2.5-flash` model  
- Automatic grounding & citations  

---

## 🧠 How It Works

1. User enters API key  
2. Notebook initializes Gemini client  
3. File is uploaded & indexed via File Search  
4. OCR & embeddings handled by Google  
5. User sends questions  
6. Model retrieves relevant text  
7. Answer is grounded and cited  

All flow is inside one notebook — easy to modify, easy to learn.

---

## 🧩 Technologies Used

| Component | Purpose |
|----------|---------|
| Gemini File Search | Retrieval engine |
| gemini-2.5-flash | Fast grounded Q&A |
| Google OCR | PDF/image text extraction |
| Python (Colab) | Notebook runtime |

---

## 🔮 Optional Improvements

- Multi-document support  
- Persistent file stores  
- UI inside notebook (Gradio optional)  
- Cloud Run / HuggingFace deployment  

---

## ❤️ Credits

Powered by the Google Gemini API  
https://ai.google.dev
