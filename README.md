# Chatbot with Sentiment Analysis, Summarization, and Q&A Using Flask

This project is a chatbot built with **Flask** that integrates **sentiment analysis, text summarization, and question answering** models. It also includes a **decoder-only model (GPT-2)** for general text generation.

## 🔥 Features
- **Sentiment Analysis**: Determines if the user's message is positive or negative and adjusts responses accordingly.
- **Text Summarization**: If the user requests a summary, the bot summarizes the given text.
- **Question Answering**: If the input contains a question, the chatbot uses a Q&A model to provide an accurate answer.
- **Conversational Memory**: Stores conversation history for better contextual responses.
- **Reset Conversation**: Summarizes and clears chat history upon request.

## 🛠️ Technologies Used
- **Flask** (for the web server)
- **Transformers (Hugging Face)** (for NLP models)
- **TensorFlow** (for deep learning)
- **GPT-2** (for text generation)
- **DistilBERT** (for sentiment analysis)
- **FLAN-T5** (for summarization & Q&A)

