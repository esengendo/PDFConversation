# PDF Conversational Interface Application

## Overview
The PDF Conversational Interface Application is a tool that combines the capabilities of LangChain, OpenAI, and Streamlit. This application allows users to upload multiple PDF documents and interact with them through a conversational interface. It processes the text within these documents, enabling users to ask questions and receive information based on the document contents.

## Objective
To deliver a state-of-the-art PDF Conversational Interface Application that harnesses the power of LangChain, OpenAI, and Streamlit, providing users with the ability to upload, process, and interact with multiple PDF documents in a conversational manner. This tool aims to offer an intuitive, responsive, and seamless experience for extracting and querying document information, thereby enhancing knowledge accessibility and user engagement.

## Key Features
- **PDF Text Extraction**: Efficiently extract text from uploaded PDF files.
- **Advanced Text Processing**: Segment extracted text into manageable chunks for better processing.
- **Vectorized Information Storage**: Utilize vector stores to hold processed text for quick retrieval.
- **Interactive Conversational Interface**: Engage with the content of the PDFs through a responsive chat interface.
- **Streamlit Web Interface**: A user-friendly and intuitive web interface powered by Streamlit.

## Technical Workflow
1. **PDF Upload and Text Extraction**:
    - Users upload PDFs, and the application extracts text from each document.
2. **Text Processing**:
    - The extracted text is split into smaller segments for efficient handling.
3. **Vectorization of Text**:
    - Text segments are converted into vector form using either OpenAI or HuggingFace embeddings for fast information retrieval.
4. **Setting Up the Conversational Interface**:
    - The application utilizes a conversational model combined with a memory buffer to facilitate an interactive Q&A session based on the PDF content.
5. **Streamlit Integration**:
    - The Streamlit framework provides a seamless interface for users to upload documents, ask questions, and view responses.

## Installation and Setup
1. **Clone the Repository**:
   - `git clone [repository URL]`
2. **Install Required Libraries**:
   - Run `pip install -r requirements.txt` in your terminal.
3. **Environment Configuration**:
   - Configure any necessary environment variables.
4. **Running the Application**:
   - Execute `streamlit run app.py` to start the application.

## Usage
- **Uploading PDFs**: Use the sidebar to upload one or multiple PDF files.
- **Asking Questions**: After processing the PDFs, type your questions into the text input box and submit.
- **Viewing Responses**: Responses from the system will appear in the main interface, allowing for an interactive conversation about the document contents.

## Contributions
I encourage contributions to enhance the application. Please feel free to fork the repository, make improvements, and submit a pull request with your changes.


---
References:
- https://python.langchain.com/docs/get_started/introduction
- https://huggingface.co/hkunlp/instructor-xl
- https://platform.openai.com/docs/models
