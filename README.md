# 🤖  UTTU BABA Chatbot 

This project demonstrates a chatbot built using the **LangChain** framework, **OpenAI's GPT-3.5-turbo**, and the **Streamlit** framework for showcasing the chatbot interface. The chatbot provides helpful responses to user queries and is designed to be extensible and easy to integrate.

---

## ✨ **Features**
- ⚙️ Leverages **LangChain** to manage prompts and chain operations.
- 🧠 Utilizes **OpenAI's GPT-3.5-turbo** as the underlying LLM (Large Language Model) for intelligent responses.
- 🖥️ Implements **Streamlit** to create a simple and user-friendly web interface.
- 🔒 Environment variables are used to securely handle API keys.

---

## 🛠️ **Installation**

Follow these steps to set up and run the project:

### 1️⃣ **Clone the Repository**

git clone <https://github.com/uttuJod/Chatbot>

---

### 2️⃣ **Install Dependencies**
- Ensure you have Python 3.7+ installed. Install the required libraries using:
- pip install -r requirements.txt

---

### 3️⃣ **Run the Application**
- Launch the Streamlit application:
- streamlit run app.py
- Navigate to the URL displayed in your terminal ( http://localhost:8501).

---

### 📂 Project Structure
- ├── app.py               # Main application file
- ├── .env                 # Environment variables file (not committed to Git)
- ├── requirements.txt     # Python dependencies
- ├── README.md            # Project documentation

---

### 🚀 How It Works
🛠️ Prompt Creation with LangChain:

A ChatPromptTemplate is created to structure the interaction between the user and the OpenAI GPT model. The system role instructs the chatbot to behave as a helpful assistant, while the user role formats the input query.
# 🤖 OpenAI Integration:

The ChatOpenAI model is configured to use OpenAI's GPT-3.5-turbo. This is where the magic happens, generating intelligent responses to user queries.
# 🌐 Streamlit Interface:

The chatbot interface is built using Streamlit, allowing users to enter their queries in a text input box and view responses directly in the web application.
# 🔐 Environment Variable Handling:

API keys are securely accessed using Python's os.getenv() and managed through a .env file to avoid accidental exposure in the codebase.
# 📖 Usage
Open the application in your browser.
Enter your question or query in the text input box.
View the chatbot's response generated using OpenAI's GPT model.

# 📜 License
This project is open-source and available under the MIT License.

### 🙏 Acknowledgements
- 📚 LangChain Documentation
- 📚 OpenAI Documentation
- 📚 Streamlit Documentation

