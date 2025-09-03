A self project that enables users to chat with PDF documents using LangChain, OpenAI, and Streamlit. Upload any PDF and ask natural language questions to get instant answers powered by embeddings and vector search.

🚀 Features

🔍 Extracts and processes text from PDFs

🧩 Splits text into chunks for better retrieval

🤖 Uses LangChain with OpenAI embeddings for semantic search

💬 Interactive chat-style interface built with Streamlit

📊 Handles multi-page PDFs efficiently

📂 Project Structure
langchain-ask-pdf/
│── app.py                  # Main Streamlit app
│── requirements.txt        # Dependencies
│── .env                    # API key configuration
│── India.pdf               # Sample input PDF
│── India_States.docx       # Sample output (processed text)
│── GUI.png                 # Screenshot of the interface
│── README.md               # Project documentation

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/daminidsarma/pdf-chatbot-langchain.git
cd pdf-chatbot-langchain


Create and activate a virtual environment

python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate   # On Mac/Linux


Install dependencies

pip install -r requirements.txt


Set up environment variables
Create a .env file and add your OpenAI API key:

OPENAI_API_KEY=your_api_key_here


Run the Streamlit app

streamlit run app.py

🖼️ Screenshots
Chat Interface

📊 Example Use Case

Upload India.pdf

Ask: “What is the capital of Rajasthan?”

Get instant answer: Jaipur

🛠️ Tech Stack

Python

LangChain

OpenAI

FAISS

Streamlit

PyPDF2

🌟 Future Enhancements

Support for multiple file formats (.docx, .txt)

Add conversation history memory

Deploy on cloud (Streamlit Cloud / HuggingFace Spaces)
