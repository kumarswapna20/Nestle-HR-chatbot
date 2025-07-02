# Nestle-HR-chatbot

🔍 Overview
This project demonstrates the development of a Conversational AI Chatbot designed to respond to user queries using information extracted from internal PDF documents. The initiative supports Nestlé’s Human Resources (HR) department, with the goal of improving operational efficiency and information accessibility through an intuitive AI-driven interface.

🧠 Objective
Leverage GPT-based AI models, Gradio UI, and vector similarity search techniques to automate information retrieval from HR documentation, providing quick and accurate answers to employee inquiries.

🚀 Key Features
PDF Knowledge Ingestion*: Parses PDF documents and extracts textual data for downstream processing.
*Embedding & Vectorization*: Converts text into numerical vector representations using OpenAI Embeddings or Hugging Face models.
*Similarity Search*: Implements vector stores using FAISS or ChromaDB to retrieve the most relevant content based on user queries.
*Conversational AI Integration*: Utilizes LangChain and OpenAI's GPT-3.5 model for contextual response generation.
*Interactive UI*: Features a clean, responsive chatbot interface built with Gradio for real-time interactions.
*Deployment-Ready*: Designed for enterprise use with scalability, ease of use, and HR applicability in mind.

🛠️ Tech Stack
*Programming*: Python
*LLM & Embeddings*: OpenAI API, Hugging Face Transformers
*Vector DB*: FAISS
*Frameworks*: LangChain
*UI*: Gradio

🏢 Use Case: Nestlé HR Automation
This chatbot is tailored to streamline employee support within Nestlé’s HR department by:
- Answering FAQs directly from policy documents
- Reducing HR ticket backlog
- Improving employee access to reliable information

📦 How to Use
- Upload internal HR policy PDFs.
- Run the script to ingest documents and build the vector store.
- Interact with the chatbot via the Gradio UI.
- Ask HR-related questions and receive accurate, document-backed responses in real time.

✅ Outcomes
- Enhanced employee experience via 24/7 instant access to HR information
- Reduced manual workload for HR staff
- Scalable chatbot framework applicable across departments and industries

