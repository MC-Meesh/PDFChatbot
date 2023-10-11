# PDFChatbot: Conversational Insights from PDFs
This project leverages the power of Retrieval Augmented Generation (RAG) to provide conversational interfaces that answer questions directly from multiple PDFs using Vector Embedding.
Dive deep into your document's content with the chatbot interface and fetch relevant insights.
This project is a modification of [Alejandro AO's Implementation](https://github.com/alejandro-ao/ask-multiple-pdfs)

## Features
PDF Content Extraction: Seamlessly extract and process text content from multiple PDFs.
Conversational Interface: Engage in a chat-like experience to ask questions about your documents.
Retrieval Augmented Generation: Uses advanced OpenAI or HuggingFace Models to retrieve relevant information from the processed PDFs to generate contextual answers.

## Getting Started
### Prerequisites
Python 3.x \
OpenAI or HuggingFace API key.
### Installation
Clone the repository:
``` git clone https://github.com/yourusername/RAGpdfBot.git ``` \
Navigate to the project directory:
```cd PDFChatbot```\
Install the required packages:
```pip install -r requirements.txt```

### Configuration
To use this bot, you'll need to have an API key for either OpenAI or HuggingFace.

Store your API key in a .env file in the root directory of the project. Here's the format:\
```OPENAI_API_KEY=your_openai_key_here``` \
or \
```HUGGINGFACE_API_KEY=your_huggingface_key_here```

Load the environment variables:
```
from dotenv import load_dotenv
load_dotenv()
```
Run the main script:
```streamlit run app.py```
Follow the on-screen instructions to upload your PDFs and start asking questions about your documents!

## License
The PDFChatbot App is released under the [MIT License](https://opensource.org/license/mit/).
