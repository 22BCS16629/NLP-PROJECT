Research Paper Recommender

AI-powered app that recommends ML research papers based on semantic similarity of user queries using NLP and TF-IDF vectorization.

Live Demo
[paper-recommender.streamlit.app](https://paper-recommender.streamlit.app/)

Tech Stack
- Python, Streamlit
- Scikit-learn (TF-IDF, Cosine Similarity)
- Pandas, Regex
- Dataset: arXiv papers (titles + abstracts)

How It Works
1. User enters a natural language query
2. TF-IDF vectorizes query against paper titles and abstracts separately
3. Cosine similarity computed for both, averaged for final ranking
4. Top 5 most relevant papers returned with highlighted matching terms

Files
- `app.py` — Main Streamlit application
- `requirements.txt` — Dependencies

Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
```
