🤖 Gemini Chatbot (Streamlit)

A simple conversational AI chatbot built using Streamlit and Google Gemini-Pro API. This application enables real-time interaction with an AI model while maintaining chat history for context-aware responses.

🚀 Features
💬 Real-time conversational AI using Gemini-Pro
🧠 Context-aware responses with session-based chat memory
🎯 Clean and interactive UI using Streamlit
🔐 Secure API key handling using environment variables
⚡ Lightweight and easy to run locally


🛠️ Tech Stack
Python
Streamlit
Google Generative AI (Gemini-Pro)
dotenv



📂 Project Structure
├── app.py
├── .env
├── requirements.txt
└── README.md


⚙️ Setup Instructions

1️⃣ Clone the repository
clone https://github.com/mousse-26/ChatBot-using-Streamlit.git
cd your-repo-name

2️⃣ Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Set up environment variables

Create a .env file in the root directory and add:

GOOGLE_API_KEY=your_api_key_here

5️⃣ Run the application
streamlit run app.py

💡 What I Learned
Integrating LLM APIs into applications
Managing conversational context using session memory
Building interactive UIs with Streamlit
Handling environment variables securely


📌 Future Improvements
Add multi-user support
Improve UI/UX
Add streaming responses
Integrate document-based RAG capabilities
