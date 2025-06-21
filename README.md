# 📄 AI PDF Agent

An interactive Streamlit web app that allows users to upload a PDF and ask questions about its content. The app uses Azure's GPT-4.1-nano model to generate intelligent responses based solely on the uploaded document.

## 🚀 Features

- Upload and parse PDF documents
- Ask natural language questions about the content
- Get AI-generated answers based on the PDF
- Powered by Azure AI and PyMuPDF

## 🧰 Tech Stack

- Streamlit – for the web interface
- PyMuPDF (fitz) – for PDF text extraction
- Azure AI Inference – for GPT-based responses
- python-dotenv – for environment variable management
## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/ai-pdf-agent.git
   cd ai-pdf-agent
   ```# AI-Agent

   Create a virtual environment and activate it:


2. Install dependencies:


Set up environment variables:

Create a .env file in the root directory and add your Azure API token:


🧠 Usage
Run the app:


3. In the browser:

Upload a PDF file.
Enter a question related to the document.
View the AI-generated answer.


📁 Project Structure
ai-pdf-agent/
├── app.py              # Main Streamlit app
├── .env                # Environment variables (not committed)
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation


✅ Requirements
Python 3.8+
Azure AI Inference endpoint and API key
Internet connection


🛡️ Disclaimer
This app uses AI to generate responses based on PDF content. Always verify critical information independently.
