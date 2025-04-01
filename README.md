# Ai-chatbot
# Streamlit Chatbot

A simple chatbot built using Streamlit and Microsoft's Phi-3-mini-4k-instruct model from Hugging Face for generating AI-powered responses.

## Features
- User-friendly chat interface built with Streamlit
- AI-generated responses using the Phi-3-mini-4k-instruct model
- Maintains chat history across interactions
- Supports streaming responses for a more interactive experience

## Installation

### Prerequisites
Make sure you have Python installed (preferably 3.8 or later) and install the required dependencies:

```bash
pip install streamlit huggingface_hub
```

## Usage

1. Clone this repository:
```bash
git clone https://github.com/yourusername/streamlit-chatbot.git
cd streamlit-chatbot
```

2. Run the Streamlit app:
```bash
streamlit run app.py
```

3. Interact with the chatbot via the web interface.

## Code Explanation

- `response_generator(prompt)`: Sends user input to the AI model and fetches a response.
- `st.session_state.messages`: Stores the chat history to maintain conversation flow.
- `st.chat_input()`: Captures user input.
- `st.chat_message()`: Displays messages from both the user and the AI.

## Model Information
This chatbot uses the **Phi-3-mini-4k-instruct** model hosted on Hugging Face.

## Future Enhancements
- Add voice-to-text support
- Improve UI with additional themes and styles
- Support for multiple AI models

## License
This project is licensed under the MIT License.

## Acknowledgments
- [Streamlit](https://streamlit.io/) for the UI framework
- [Hugging Face](https://huggingface.co/) for hosting AI models
- Microsoft for the Phi-3-mini-4k-instruct model
