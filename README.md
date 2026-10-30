
# 🤖 LangChain Chatbot

An AI-powered conversational chatbot built using **Python, LangChain, OpenAI API, and Streamlit**. This application allows users to interact with an AI language model through a simple and user-friendly web interface.

## 📌 About The Project

LangChain Chatbot is a Python-based AI application designed to provide intelligent responses to user queries. It uses LangChain to integrate Large Language Models (LLMs) into the application and Streamlit to create an interactive chatbot interface.

Users can enter their questions, send them to the AI model, and receive generated responses through the web application.

## ✨ Features

- Interactive chatbot interface using Streamlit.
- AI-powered responses to user queries.
- Integration of OpenAI API using LangChain.
- Environment variable management for API credentials.
- Simple and user-friendly interface.
- Python-based application architecture.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| LangChain | LLM integration and management |
| OpenAI API | AI-generated responses |
| Streamlit | Interactive web interface |
| Hugging Face Hub | AI model ecosystem |
| Python-dotenv | Environment variable management |

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

## ⚙️ Getting Started

Follow these steps to set up the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Sujitpw/LangChain-Chatbot.git
```

### 2. Navigate to the Project Directory

```bash
cd LangChain-Chatbot
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

For Windows:

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Configure Environment Variables

Create a `.env` file in the root directory and add your OpenAI API key:

```env
OPENAI_API_KEY=your_openai_api_key
```

**Note:** Keep your API credentials private. Never upload your `.env` file or API keys to GitHub.

### 7. Run the Application

```bash
streamlit run app.py
```

## 🔄 How It Works

The application follows a simple request-response workflow:

1. **User Input:** The user enters a query through the Streamlit interface.
2. **Python Processing:** The application receives and processes the input.
3. **LangChain Integration:** LangChain connects the Python application with the OpenAI language model.
4. **AI Response Generation:** The language model processes the query and generates a response.
5. **Output Display:** The generated response is returned to the application and displayed to the user.

## 🎯 Learning Outcomes

Through this project, I explored:

- Fundamentals of LangChain and Large Language Models (LLMs).
- Integrating AI APIs into Python applications.
- Building interactive applications using Streamlit.
- Managing API credentials using environment variables.
- Understanding the request-response workflow of AI-powered applications.

## 👨‍💻 Author

**Sujit Kumar**

Electronics and Communication Engineering Student  
BIT Sindri, Dhanbad, Jharkhand, India

- **GitHub:** [Sujitpw](https://github.com/Sujitpw)
- **Portfolio:** [www.sujitportfolio.work](https://www.sujitportfolio.work/)

## 📜 License

This project is distributed under the MIT License. See the `LICENSE` file for more information.

## 🙏 Acknowledgements

This project is based on the original [Chatbot-Using-Langchain](https://github.com/KalyanM45/Chatbot-Using-Langchain) repository. Credit goes to the original author for the initial implementation and project inspiration.

---

⭐ If you find this project interesting, feel free to explore the repository!

