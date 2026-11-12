# NU Policy Assistant demo

Search 352 passages from 4 public Nazarbayev University policy documents in English or Russian. The app uses BGE-M3 for retrieval and BGE reranking.

Run from the repository root with Python 3.12.

```bash
python -m pip install -r requirements.txt
python -m streamlit run src/app.py
```

The first run downloads model weights from Hugging Face. Prepared embeddings for the demo corpus are included. For a managed Streamlit deployment, use `src/app.py` as the entry point.

This is an independent project. For official guidance, consult Nazarbayev University.
