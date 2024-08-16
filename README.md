# RAG-chatbot: Retrieval Augmented generation (RAG) chatbot using OpenAI GPT Model, Langchain, ChromaDB, and Gradio

### Installing Dependencies Individually
If you prefer to install the dependencies individually, run the following command:

```
pip install gradio==4.13.0 langchain==0.0.354 openai==0.28.0 chromadb==0.4.22 pypdf==3.17.4 pandas==2.1.4
```

1. **Configuration and Execution**
* Open cfg.py and fill in your GPT API credentials.

2. **Activate Your Environment.**
3. **Ensure you are in the RAG-Chatbot directory**
4. **Run the Application:**

In Terminal 1:
```
python src\serve.py
```

In Terminal 2:
```
python src\raggpt_app.py
```
5. Chat with your documents.


Extra read:
- [GPT model](https://platform.openai.com/docs/models/overview) 
- [Gradio](https://www.gradio.app/guides/quickstart)
- [Langchain](https://python.langchain.com/docs/get_started/quickstart)
- [ChromaDB](https://www.trychroma.com/)