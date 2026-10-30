
# 🤖 LangChain Chatbot

An AI-powered chatbot application built using Python, LangChain, OpenAI API, and Streamlit. It provides an interactive interface where users can submit natural language queries and receive AI-generated responses.

## 🚀 Features

- Interactive chatbot interface.
- AI-powered natural language responses.
- OpenAI API integration using LangChain.
- Secure API key management using environment variables.
- Simple and user-friendly web interface.

## 🛠️ Tech Stack

- **Language:** Python
- **LLM Framework:** LangChain
- **AI Integration:** OpenAI API
- **Frontend:** Streamlit
- **Libraries:** Hugging Face Hub, Python-dotenv

## 📂 Project Structure

```text
LangChain-Chatbot/
│
├── app.py
├── requirements.txt
├── .env
├── .gitignore
├── README.md
└── LICENSE
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Sujitpw/LangChain-Chatbot.git
```

### 2. Navigate to the Project

```bash
cd LangChain-Chatbot
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

For Windows:

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Configure API Key

Create a `.env` file in the project root directory.

```env
OPENAI_API_KEY=your_openai_api_key
```

Keep your API credentials private and never commit the `.env` file to GitHub.

### 7. Run the Application

```bash
streamlit run app.py
```

## 🔄 Application Workflow

1. User enters a query through the Streamlit interface.
2. Python receives the input.
3. LangChain manages the interaction with the OpenAI language model.
4. The AI model generates a response.
5. The response is displayed to the user through Streamlit.

## 🎯 Key Concepts

- Large Language Models (LLMs)
- LangChain Integration
- OpenAI API
- Python Application Development
- Environment Variable Management
- Interactive Web Applications

## 👨‍💻 Author

**Sujit Kumar**

Electronics and Communication Engineering Student  
BIT Sindri, Dhanbad, Jharkhand, India

- **GitHub:** [@Sujitpw](https://github.com/Sujitpw)
- **Portfolio:** [sujitportfolio.work](https://www.sujitportfolio.work/)

## 📜 License

Distributed under the MIT License. See `LICENSE` for details.
