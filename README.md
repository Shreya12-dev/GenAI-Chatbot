GenAI Chatbot using LangChain, RAG & Streamlit

This is a GenAI-powered chatbot that uses:
- LangChain for Retrieval-Augmented Generation (RAG)
- Google Generative AI (Gemini)
- PDF ingestion using `PyMuPDF`
- Vector Store using `Qdrant`
- Session Memory using `pgvector`
- Streamlit UI for easy interaction

 Files

- `genai_chatbot.py` → Contains chatbot backend logic
- `app.py` → Streamlit app to interact with the chatbot

 How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
