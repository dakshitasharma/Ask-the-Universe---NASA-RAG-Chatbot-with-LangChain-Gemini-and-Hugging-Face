**Ask the Universe – NASA RAG Chatbot**

An AI-powered chatbot that answers space-related questions using NASA’s open data, a RAG (Retrieval-Augmented Generation) pipeline, Hugging Face embeddings, and Google Gemini LLM.

**🔹 Key Features:**
✅ Fetches real-time space data from NASA API
✅ Uses LangChain to split, embed, and retrieve documents
✅ Vector search powered by FAISS
✅ Hugging Face sentence-transformers for embeddings
✅ Google Gemini LLM for intelligent responses
✅ Built with Streamlit for a simple UI (can also run in Colab)

**Tech Stack**
Technology  --	Purpose
NASA API    --	Fetches space data
LangChain   --	Builds the RAG pipeline
Hugging Face--	Sentence embeddings
FAISS       --	Vector database for retrieval
GoogleGemini--	LLM to generate answers
Streamlit   --	Web interface
Python, Colab	Development environment


**How It Works**
User asks a space-related question.
The app queries NASA API for relevant data.
Text is split into chunks and embedded with Hugging Face embeddings.
Data is stored in a FAISS vector database.
A Retriever fetches the most relevant context.
Gemini LLM generates an intelligent answer using this context.
The response is displayed on a Streamlit UI.


**Example Query**

You: “Tell me about Mars rovers.”
Bot: “NASA has launched multiple rovers such as Curiosity, Perseverance, and Spirit to explore the Martian surface…”

**Future Enhancements**

 Add image previews for NASA data
 Support multiple NASA endpoints (Mars Rover Photos, Asteroids API)
 Improve caching and speed with persistent FAISS store
 Add voice interaction
