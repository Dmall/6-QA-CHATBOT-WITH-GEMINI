# 🤖 Gemini LLM Q&A Chatbot

**An intelligent conversational assistant powered by Google’s Gemini Pro Model** — built with **Streamlit** and **LangChain** to enable natural, context-aware interactions with persistent chat memory.  

Ask anything, get instant, context-rich responses — all within a clean, interactive web interface.  


## 🚀 Features

- Real-time conversation with the Gemini Pro model.
- Conversation history is displayed in the chat interface.
- Session memory to maintain context throughout the chat.
- The ability to ask questions and receive answers powered by Google Generative AI.
- Configured to use the `dotenv` library for environment variable management.



## 🧩 Tech Stack

| Component | Technology Used |
|------------|----------------|
| **Frontend** | Streamlit |
| **Backend** | Python 3.10+ |
| **LLM Engine** | Google Gemini Pro via `google.generativeai` |
| **Conversation Memory** | LangChain |
| **Environment Management** | python-dotenv |


## Requirements
- Python 3.7+
- Google API Key for Gemini Pro.
- Install the necessary Python packages listed below.

## Setup Instructions

1. Clone the Repository
```bash
git clone <repository-url>
cd smart-ats-resume-analyzer
```

2. Create Virtual Environment
```bash
conda create -p env python=3.10 -y
```

3. Install Dependencies
```bash
pip install -r requirements.txt
```

4. Environment Configuration Create a .env file in the root directory:
```bash
GOOGLE_API_KEY =your_api_key_here
```

5. Run the Application
```bash
streamlit run app.py
```




