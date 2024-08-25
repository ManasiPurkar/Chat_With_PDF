# Chat_With_PDF
Basic web application using Streamlit, Google Generative AI, Gemini Pro model, and FAISS to enable interaction with PDF documents.
## Features
- ** PDF Text Extraction:** Upload PDF files, and the application extracts the text content from the documents.
Text Chunking: The extracted text is split into manageable chunks to enable efficient processing.
Vector Store: Text chunks are converted into embeddings and stored in a FAISS index for fast similarity search.
Question Answering: Users can ask questions related to the uploaded PDFs, and the application retrieves relevant content and provides detailed answers using a conversational AI model.
User Interface: A simple and intuitive interface built with Streamlit.
Tech Stack
Streamlit: For building the interactive web application.
Google Generative AI: For generating responses to user queries based on PDF content.
FAISS: For creating and managing a vector store for efficient document retrieval.
PyPDF2: For extracting text from PDF files.
Langchain: For text splitting, embeddings, and chaining the question-answering process.
dotenv: For managing environment variables securely.
