# Internship-Project
This is my internship project repositories

# AI Chat Agent with Streamlit and LangChain

This is a simple AI chat agent web app built using **Streamlit** and **LangChain** with the **ChatGroq** model backend.

## Features

- Interactive chat interface powered by Streamlit.
- Conversation memory to keep context across messages.
- Uses `langchain-groq` to connect to Groq API with the LLaMA 3.1 8b Instant model.
- Loads sensitive API keys securely from `.env` file.

## Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo

**2.Create a .env file in the root directory with your Groq API key:**
GROQ_API_KEY=your_groq_api_key_here
**
3.Install dependencies:**
pip install -r requirements.txt
**
4.Run the app:**
streamlit run app.py
