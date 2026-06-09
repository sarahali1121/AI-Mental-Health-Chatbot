🧠 AI-Driven Mental Health Chatbot
A context-aware chatbot that answers mental health questions using Retrieval-Augmented Generation (RAG).
Built with LangChain, LLaMA 3.3, ChromaDB, and Gradio.

💡 How It Works

Loads a mental health PDF document
Splits it into chunks and stores embeddings in ChromaDB
On user query, retrieves the most relevant chunks
Sends context + question to LLaMA 3.3 via Groq
Returns a warm, supportive response through a Gradio chat UI


🛠️ Tech Stack
ToolPurposeLangChainRAG pipelineLLaMA 3.3 (Groq)Language modelChromaDBVector databaseHuggingFace EmbeddingsText embeddingsGradioChat interfacePyPDFPDF loading

🚀 Getting Started
1. Open in Google Colab

2. Get a free Groq API Key
👉 console.groq.com
3. Upload your PDF to Google Drive
Update PDF_PATH in Step 3 of the notebook with your file path.
4. Run all cells top to bottom

📸 Demo

Chat UI powered by Gradio — ask anything about mental health and get a compassionate, document-grounded response.


👩‍💻 Author
Sara 
