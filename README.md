

# PDF CHATBOT
## link for the demo:https://huggingface.co/spaces/venkataseetharam/Pdfchatbot

## Introduction
This Streamlit application offers a range of functionalities including PDF processing, text splitting, and integration with Google's Generative AI and LangChain. It's designed to handle complex tasks like question answering and prompt generation.

## Features
- **PDF Processing**: Utilizes PyPDF2 for handling PDF files.
- **Text Splitting**: Employs `RecursiveCharacterTextSplitter` for efficient text manipulation.
- **Generative AI Integration**: Leverages Google Generative AI for advanced language processing tasks.
- **Question Answering**: Includes a question-answering module powered by LangChain.
- **Prompt Templating**: Facilitates the creation of structured prompts.



## Usage

To run the application, execute the following command in the terminal:

```
streamlit run app.py
```

Navigate to the provided local URL to access the application's interface.

## Configuration

Set the necessary environment variables in a `.env` file at the root of your project. This includes API keys and other sensitive information that the application requires.

## Acknowledgments

This application uses several external libraries and APIs:
- Streamlit
- PyPDF2
- LangChain
- Google Generative AI


