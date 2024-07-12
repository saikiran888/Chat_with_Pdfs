# Chat With Multiple PDF Documents Using Langchain and Google Gemini Pro

This project demonstrates how to create an end-to-end application for chatting with multiple PDF documents using Google Gemini Pro and Langchain. The application allows users to upload multiple PDF documents, process them into vector embeddings, and interact with the content by querying specific information.

## Features

- **PDF Upload and Processing**: Upload multiple PDF documents and convert their content into vector embeddings.
- **Query and Response**: Ask questions about the content of the uploaded PDFs and receive accurate responses.
- **Vector Embeddings**: Utilizes a vector embedding technique created by Facebook and integrates it with Langchain and Google Gemini Pro.
- **Streamlit Interface**: User-friendly interface built with Streamlit for seamless interaction.

## Demo
![image](https://github.com/user-attachments/assets/21ce0c58-3b4f-4145-9936-c0577c2a6437)

1. Upload PDF documents.
2. The documents are processed and converted into vector embeddings.
3. Ask questions about the content of the PDFs.
4. Receive responses based on the vector embeddings.

## Setup Instructions

### Prerequisites

- Python 3.10+
- [Google Gemini Pro API Key](https://cloud.google.com/gemini)

### Environment Setup

1. **Create Virtual Environment**:
    ```sh
    conda create -n myenv python=3.10
    conda activate myenv
    ```

2. **Install Dependencies**:
    ```sh
    pip install streamlit langchain google-generative-ai pypdf2
    ```

3. **Set Environment Variables**:
    ```sh
    export GOOGLE_API_KEY='YOUR_GOOGLE_API_KEY'
    ```

### Running the Application

1. **Clone the Repository**:
   

2. **Start the Streamlit App**:
    ```sh
    streamlit run app.py
    ```
