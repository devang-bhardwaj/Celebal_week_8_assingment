# 🚀 RAG Chatbot - Multi-Format Document Intelligence

<div align="center">

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Pinecone](https://img.shields.io/badge/Pinecone-Vector_DB-green)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-AI-red)
![Gradio](https://img.shields.io/badge/Gradio-UI-orange)
![License](https://img.shields.io/badge/license-MIT-purple.svg)

**🤖 Chat with your PDFs, CSVs, and Excel files using state-of-the-art AI!**

[Features](#-features) • [Demo](#-demo) • [Installation](#-installation) • [Quick Start](#-quick-start) • [Usage](#-usage) • [API Keys](#-api-keys) • [Contributing](#-contributing)

</div>

---

## 📖 Overview

**RAG Chatbot** is an intelligent document assistant that allows you to upload various file formats and have natural conversations with your data. Built with cutting-edge Retrieval-Augmented Generation (RAG) technology, it combines the power of vector databases and large language models to provide accurate, context-aware responses.

### 🎯 Key Capabilities

- 📄 **PDF Processing** - Extract and understand text from PDF documents
- 📊 **CSV Analysis** - Intelligent parsing and querying of tabular data
- 📈 **Excel Support** - Multi-sheet workbook comprehension
- 🔍 **Smart Search** - Vector similarity search for relevant information
- 💬 **Natural Chat** - Conversational interface powered by Google Gemini
- 🎯 **Source Attribution** - Always know where the information comes from

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🗂️ Multi-Format Support
- ✅ PDF documents
- ✅ CSV datasets
- ✅ Excel workbooks (.xlsx, .xls)
- ✅ Automatic format detection
- ✅ Batch processing capable

</td>
<td width="50%">

### 🧠 Intelligent Processing
- ✅ Semantic chunking
- ✅ Vector embeddings
- ✅ Context preservation
- ✅ Statistical summaries
- ✅ Data insights

</td>
</tr>
<tr>
<td width="50%">

### 🚀 Advanced RAG Pipeline
- ✅ Pinecone vector storage
- ✅ Sentence transformers
- ✅ Google Gemini LLM
- ✅ Hybrid search
- ✅ Relevance ranking

</td>
<td width="50%">

### 💡 Smart Features
- ✅ Real-time responses
- ✅ Source citations
- ✅ Memory persistence
- ✅ Scalable architecture
- ✅ User-friendly UI

</td>
</tr>
</table>

---


### 🎥 Live Demo
```python
# Launch the application
demo = create_gradio_interface()
demo.launch(share=True, debug=True)
