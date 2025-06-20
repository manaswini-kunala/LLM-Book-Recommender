# Build a Semantic Book Recommender with LLMs – Full Course

# 📚 Build a Semantic Book Recommender with LLMs

This repo walks you through creating a full-stack AI-powered book recommender system using large language models (LLMs), vector search, and a user-friendly web interface built with Gradio.

---

## 🧠 Project Overview

Built a semantic search and recommendation engine that:

- Cleans and explores book metadata
- Uses LLM-generated embeddings for similarity search
- Performs zero-shot classification (fiction vs. non-fiction)
- Extracts sentiment and emotional tone from book descriptions
- Provides a Gradio-based UI for user interaction and book discovery

---

## 📂 Project Components

1. **Text Data Cleaning**  
   Initial data exploration and cleanup using pandas and seaborn  
   📄 `data-exploration.ipynb`

2. **Semantic Search (Vector Database)**  
   Convert book descriptions into embeddings using OpenAI, and store/retrieve with ChromaDB  
   📄 `vector-search.ipynb`

3. **Zero-Shot Classification**  
   Classify books as *fiction* or *non-fiction* without any training labels using LLM prompts  
   📄 `text-classification.ipynb`

4. **Sentiment & Emotion Analysis**  
   Use LLMs to identify emotional tone like suspense, joy, or sadness  
   📄 `sentiment-analysis.ipynb`

5. **Gradio Web App**  
   Create an interactive dashboard to input natural queries and explore results  
   📄 `gradio-dashboard.py`

---

## 🧪 Features

- 🔍 **Semantic Search** — Recommend books based on query similarity (e.g., "revenge story with strong female lead")
- 📚 **Genre Filtering** — Sort books as fiction or non-fiction using zero-shot classification
- 🎭 **Emotion Tagging** — Classify books by mood (e.g., joyful, sad, suspenseful)
- 🌐 **Web Interface** — Intuitive UI built with Gradio for real-time user interaction

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/semantic-book-recommender.git
cd semantic-book-recommender


