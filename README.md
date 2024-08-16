# Groq LLM Chatbot

This project is a chatbot application powered by Groq's API and Large Language Models (LLMs). The chatbot is designed to provide an interactive conversational experience, allowing users to engage with various LLM models directly from the application interface.


## Features

- **Groq API Integration**: Utilizes Groq's API for efficient execution and interaction with LLM models.
- **Multiple LLM Models**: Provides access to a variety of LLM models, each with different capabilities and scales.
- **Streamlit Frontend**: The frontend of the chatbot is built using Streamlit, offering a simple and intuitive user interface.
- **Real-Time Interaction**: Users can interact with the chatbot in real-time, making it suitable for various applications like customer support, education, and general-purpose Q&A.
- **Model Selection**: Users can choose from various LLM models such as `llama3-70b`, `llama3-8b`, `mixtral-8x7b`, and `gemma-7b`. The selected model is used to generate responses in the chat.
- **Interactive Chat Interface**: The chat interface allows users to input text and receive responses from the selected LLM in real-time.

## Technologies Used

- **Groq API**: Powers the backend LLM processing, enabling high-performance model inference.
- **Large Language Models (LLMs)**: A selection of pre-trained models that are fine-tuned to generate human-like text responses.
- **Streamlit**: A Python-based framework used for building the interactive user interface.

## How to Use
- Choose a conversation model from the sidebar.
- Adjust the memory length slider according to preference.
- Input your question or message in the text area.
- Click the "Submit" button to interact with the chatbot.
- The chatbot's response will be displayed below the input area.
- Chat history will be shown in the interface.

## Getting Started

To run the Groq LLM Chatbot locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/VaishnaviThakre/groq-LLM-Chatbot.git
   cd groq-LLM-Chatbot
   ```

2. **Install Dependencies**:
   Ensure you have Python 3.8+ installed. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   Start the Streamlit server:
   ```bash
   streamlit run app.py
   ```

4. **Access the Chatbot**:
   Open your web browser and navigate to `http://localhost:8501` to start interacting with the chatbot.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue if you have suggestions or bug reports.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
