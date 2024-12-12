---

# ChatPDF: Interactive PDF Chatbot

## Overview
ChatPDF is an innovative Streamlit-based application designed to bring interactivity and accessibility to PDF documents. It leverages advanced natural language processing and information retrieval techniques to allow users to engage in a conversational manner with the content of uploaded PDF documents. Whether it's for academic research, business reports, or just general reading, ChatPDF provides a unique way to explore and understand complex documents through a simple, user-friendly chat interface.

## Features

- **PDF Text Extraction**: Utilizes `PyPDF2` to robustly extract text from uploaded PDF files, ensuring a wide range of document compatibility.
  
- **Intelligent Text Splitting**: Implements `CharacterTextSplitter` to divide the extracted content into manageable, coherent chunks, enhancing the retrieval accuracy and response relevancy.

- **Advanced Language Understanding**: Powered by `OpenAIEmbeddings` and `FAISS`, ChatPDF transforms the text chunks into a semantic search space, enabling the system to understand and retrieve information based on meaning rather than just keyword matching.

- **Conversational Interface**: Leverages `ChatOpenAI` and `ConversationBufferMemory` to provide a natural, conversational experience. Users can ask questions and receive contextually relevant answers directly from the text of the PDFs.

- **User-Friendly Web Interface**: Built with `streamlit` and enhanced with `streamlit_chat`, the application offers an intuitive web interface where users can upload documents, ask questions, and view responses in a familiar chat format.

## How It Works
1. **Upload PDFs**: Users start by uploading one or more PDF documents through the web interface.
2. **Text Processing**: The application extracts and processes the text, breaking it down into searchable chunks.
3. **Ask Questions**: Users can type in their queries or questions related to the PDF content.
4. **Receive Answers**: ChatPDF retrieves the most relevant section of the text, providing users with answers and insights directly from the document.

## Installation & Usage

Clone the project and activate the envirenment then run the app with "streamlit run app.py"

---

Feel free to modify this template to better fit the specifics of your project or add any additional sections that you feel are necessary!
