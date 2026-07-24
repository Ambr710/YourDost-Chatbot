# YourDost - Mental Health Chatbot 🧠💬

YourDost is a supportive mental health chatbot built with **Streamlit**, **LangChain**, and **Google's Gemini API**. It acts as a patient, caring companion trained to help users understand their emotions and work through negative feelings using techniques like CBT (Cognitive Behavioral Therapy).

> ⚠️ **Disclaimer:** This chatbot is an AI tool for emotional support and is **not a substitute for professional mental health care**. If you or someone you know is in crisis, please reach out to a licensed therapist, counselor, or a crisis helpline in your region immediately.

## ✨ Features

- Conversational chat interface built with Streamlit
- Powered by Google Gemini via LangChain
- Persistent chat history within a session
- Configurable safety settings for open, judgment-free conversations

## 🛠️ Tech Stack

- [Streamlit](https://streamlit.io/) — Web app framework
- [LangChain](https://www.langchain.com/) — LLM orchestration
- [Google Gemini API](https://ai.google.dev/) — Language model
- Python 3.9+

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Ambr710/YourDost-Chatbot.git
cd YourDost-Chatbot
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:
- **Windows (PowerShell):** `.\venv\Scripts\Activate.ps1`
- **Mac/Linux:** `source venv/bin/activate`

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set up your API key

Create a `.env` file in the project root and add your Google Gemini API key:

```
GOOGLE_API_KEY=your_actual_key_here
```

Get a free API key from [Google AI Studio](https://aistudio.google.com/app/apikey).

### 5. Run the app

```bash
streamlit run app.py
```

The app will open automatically at `http://localhost:8501`.

## 📁 Project Structure

```
YourDost-Chatbot/
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
├── .gitignore           # Files excluded from version control
└── README.md            # Project documentation
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to open an issue or submit a pull request.

## 📄 License

This project is open source and available for personal and educational use.
