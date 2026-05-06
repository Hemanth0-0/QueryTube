# 🔍 QueryTube – Semantic YouTube Search Engine

QueryTube is an AI-powered semantic search engine that retrieves YouTube videos based on meaning rather than exact keyword matching.

Built using Sentence Transformers and Gradio, the system converts video titles and transcripts into embeddings and performs similarity search using cosine similarity.

---

## 🚀 Features

- Semantic search using embeddings
- Retrieves videos by meaning, not keywords
- Transcript-aware ranking
- Cosine similarity based retrieval
- Interactive Gradio UI
- Video thumbnails and relevance scores
- Sorting options:
  - Relevance
  - Title A-Z
  - Newest First
  - Oldest First

---

## 🛠️ Tech Stack

- Python
- Sentence Transformers
- all-MiniLM-L6-v2
- Scikit-learn
- Pandas
- Gradio
- YouTube Data API v3

---

## 📂 Project Structure

```text
QueryTube/
│
├── data/
├── notebooks/
├── src/
├── config/
├── requirements.txt
└── README.md
```

---

## ⚙️ Model Configuration

The project uses the following embedding model configuration: :contentReference[oaicite:0]{index=0}

- Model: all-MiniLM-L6-v2
- Similarity Metric: Cosine Similarity

---

## 🧠 How It Works

1. Fetch YouTube metadata using YouTube Data API.
2. Extract transcripts using youtube-transcript-api.
3. Clean and preprocess transcript data.
4. Generate embeddings using Sentence Transformers.
5. Store embeddings inside a searchable index.
6. Perform cosine similarity search on user queries.
7. Display ranked results through Gradio UI.

---

## ▶️ Run Locally

### Clone Repository

```bash
git clone https://github.com/your-username/QueryTube.git
cd QueryTube
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

Dependencies are listed in: :contentReference[oaicite:1]{index=1}

### Run Application

```bash
python src/ui.py
```

---

## 📸 UI Preview

(Add screenshots here later)

---

## 🔎 Search Engine

The semantic search engine uses:
- SentenceTransformer embeddings
- Cosine similarity ranking
- Weighted title + transcript scoring

Implemented in: :contentReference[oaicite:2]{index=2}

---

## 🎨 Interface

The Gradio-based user interface includes:
- Search history
- Threshold filtering
- Dynamic sorting
- Video thumbnails
- Relevance visualization

Implemented in: :contentReference[oaicite:3]{index=3}

---

## 📊 Dataset Pipeline

Video metadata collection implemented using YouTube Data API v3: :contentReference[oaicite:4]{index=4}

---

## 📌 Future Improvements

- FAISS vector database integration
- Multi-channel search
- Hybrid keyword + semantic search
- Query auto-suggestions
- Deployment using Docker

---

## 👨‍💻 Author

Hemanth  
Computer Science Student | Machine Learning Enthusiast
