# Gemini LLM Chatbot 🧠🤖

This is a **Q&A chatbot** powered by **Google Gemini Pro** and built with **Streamlit**. It supports **real-time streaming responses** and maintains **chat history** for a seamless user experience.

## Features
- ✅ **Google Gemini Pro Integration** for advanced text-based AI responses.
- ✅ **Streaming Responses** for dynamic and real-time interactions.
- ✅ **Session-Based Chat History** to maintain conversation context.
- ✅ **Secure API Key Management** using environment variables.

## Installation
### Prerequisites
Ensure you have **Python 3.8+** installed.

### 1. Clone this repository
```sh
git clone https://github.com/yourusername/gemini-chatbot.git
cd gemini-chatbot
```

### 2. Install dependencies
```sh
pip install -r requirements.txt
```

### 3. Set up environment variables
Create a `.env` file in the project directory and add your **Google API Key**:
```sh
GOOGLE_API_KEY=your_api_key_here
```

### 4. Run the application
```sh
streamlit run app.py
```

## Usage
1. **Enter a question** in the input field.
2. **Click "Ask the question"** to get an AI-generated response.
3. **View the response** in real-time.
4. **Check chat history** to track past conversations.

## Technologies Used
- **Python** (Primary language)
- **Streamlit** (Web framework for UI)
- **Google Gemini Pro** (AI-powered text generation)
- **dotenv** (For secure API key management)

## File Structure
```
/
|-- app.py                # Main application script
|-- .env                  # Environment variables (DO NOT SHARE)
|-- requirements.txt      # Dependencies list
|-- README.md             # Project documentation
```

## Contributing
Pull requests are welcome! Feel free to contribute by:
- Improving the chatbot logic.
- Enhancing UI/UX.
- Adding new features.
