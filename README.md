# TITLE - [AI-Research-Assistant---Document-and-Dataset-Analyzer]
"GPT-4 Powered Document and Dataset Analysis Platform with Interactive Querying and Summarization"

## Description:
This project is a web application built using Streamlit that leverages GPT-4 via the LangChain library for document analysis (PDF, CSV, Excel, and JSON). The application allows users to upload documents and datasets, extract content, perform analysis, summarize information, answer queries, and search for keywords within the document. It provides a seamless interface for exporting summaries as PDFs and delivers insightful results with natural language processing (NLP) capabilities.

## Responsibilities:

#### 1. Document Analysis:
* Extract text from uploaded PDF files using PyPDF2.
* Summarize the document content using GPT-4 and LangChain.
* Allow users to ask questions related to the document's content.
* Perform keyword searches in the document to find occurrences of specific terms.
* Export the generated summary as a PDF file using FPDF.

#### 2. Dataset Analysis:
* Support file uploads of various datasets (CSV, Excel, JSON).
* Analyze datasets and generate insights using LangChain agents, powered by GPT-4.
* Respond to user queries regarding datasets.
  
#### 3. Custom UI & UX:
* Customize the user interface using Streamlit to provide a clean and intuitive experience.
* Use CSS to set a custom background and enhance the visual appeal.
* Handle file uploads and dynamic content generation based on the uploaded file type.

#### 4. Image Encoding and Background Setup:
* Encode images to Base64 format for embedding as background images in the application.

### Libraries Used:
#### 1. Streamlit: 
* Web framework for building the user interface.
#### 2. PyPDF2:
* Used for reading and extracting text from PDF documents.
#### 3. LangChain: 
* Used for interacting with GPT-4 for document analysis and dataset query handling.
#### 4. Pandas: 
* Data manipulation and analysis for CSV, Excel, and JSON datasets.
#### 5. FPDF: 
* PDF generation library to export summaries as PDFs.
#### 6. OpenAI (GPT-4): 
* Large language model used for summarizing documents and answering questions.
#### 7. Requests: 
* Used for making HTTP requests (though not utilized in the provided code).
#### 8. Base64: 
* For encoding image files to embed in the application’s background.
