
# Chat Bot Application  

This project is a **Streamlit-based chatbot** that integrates with the **Groq API** to deliver interactive and intelligent conversational experiences. The chatbot leverages the power of **LLM (Llama3-8b-8192)** to generate human-like responses based on user inputs.  

---

## Features  
- **Interactive Chat Interface**: A seamless chat experience with user and assistant messages displayed in a conversational format.  
- **Groq API Integration**: Utilizes Groq's advanced LLM for natural language understanding and response generation.  
- **Session Persistence**: Maintains chat history during the session for a consistent conversational flow.  
- **Secure API Key Management**: Uses Streamlit's secrets manager to securely store and access the API key.  
- **Error Handling**: Handles API call errors gracefully, ensuring a smooth user experience.  

---

## Tech Stack  
- **Python**: Programming language for backend logic.  
- **Streamlit**: Framework for building the chatbot interface.  
- **Groq API**: Provides AI-powered language model capabilities.  

---

## Installation  

### Prerequisites  
- Python 3.8 or higher installed on your system.  
- A Groq API key.  
- Streamlit library installed (`pip install streamlit`).  

### Steps  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-repo/chat-bot.git
   cd chat-bot

2. **Install Required Libraries**  
   Install all dependencies from the `requirements.txt` file:  

   ```bash
   pip install -r requirements.txt
3. **Configure API Key**
   Store your API key securely in Streamlit's secrets manager:

   Create a .streamlit/secrets.toml file in your project directory:
   [general]
   API_KEY = "your_groq_api_key"
4. **Run the Application**
   Start the Streamlit app:
   ```bash
   streamlit run app.py
5. **Access the Chatbot**
   Open the app in your browser at http://localhost:8501.







