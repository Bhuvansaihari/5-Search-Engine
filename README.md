# 🔎 LangChain - Chat with Search

This project is a simple and interactive **Streamlit app** that allows you to chat with an AI agent capable of searching the web using Wikipedia, ArXiv, and DuckDuckGo. It uses **LangChain**, **Streamlit**, and the **Groq API** with the LLaMA3 model to provide rich, intelligent responses.

---

## 🚀 Features

- **Ask any question** and receive an intelligent, researched response.
- Integrates multiple search tools:
  - 🔍 Wikipedia
  - 📚 ArXiv
  - 🌐 DuckDuckGo
- Uses **LangChain Agents** to process queries with reasoning.
- Powered by **Groq API** and LLaMA3-8b for fast, contextual language understanding.

---

## 🛠️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/langchain-search-agent.git
cd langchain-search-agent
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
GROQ_API_KEY=your_groq_api_key_here
streamlit run app.py
.
├── app.py               # Main Streamlit app
├── requirements.txt     # Python dependencies
├── .env                 # Environment variables (not included by default)
└── tools_agents.ipynb   # Jupyter notebook with tools/agent setup (optional)
🤖 Agent Configuration
The agent is initialized using:

AgentType.ZERO_SHOT_REACT_DESCRIPTION

LangChain tools: WikipediaQueryRun, ArxivQueryRun, DuckDuckGoSearchRun

Callback support via StreamlitCallbackHandler to show real-time agent thoughts and actions

🔐 Note on API Keys
This app uses Groq API to power the LLM backend. You'll need an active Groq account to get an API key. Keep your key private and secure.

📚 Credits
LangChain

Streamlit

Groq

ArXiv API

Wikipedia API

DuckDuckGo Search

📄 License
This project is open source and available under the MIT License.

🧠 Example Prompt
"What is machine learning?"

Try it out and watch the agent collect and summarize information from multiple sources in real-time!










