# ChatBot using LangChain and Ollama

This project implements a simple chatbot using LangChain and Ollama with the LLAMA2 model. The chatbot is built with a Streamlit interface for easy interaction.

## Features

- Integration with Ollama for local LLM inference using LLAMA2
- Streamlit web interface for user interaction
- LangChain for prompt templating and chain management
- Environment variable management for API keys

## Setup

1. Clone this repository
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Make sure you have Ollama installed and the LLAMA2 model downloaded:
   ```
   ollama pull llama2
   ```
4. Create a `chatbotapi.env` file with your LangChain API key:
   ```
   LangChainApiKey=your_api_key_here
   ```

## Usage

Run the Streamlit app:
```
streamlit run Ollama.py
```

This will start a local web server and open the chatbot interface in your browser.

## Requirements

- Python 3.8+
- Ollama with LLAMA2 model
- LangChain
- Streamlit

## License

MIT