# FusionAI

This repository contains a versatile tool that leverages state-of-the-art NLP and computer vision models to analyze images and PDFs, enhanced with the power of large language models (LLMs). The tool provides two main functionalities:

1. **Image Analyzer**: Generates descriptive text for images, performs OCR, extracts key concepts, and provides relevant resource links.
2. **PDF Summarizer**: Summarizes the content of a PDF document, providing a concise summary using fine-tuned models.

## Features

- **Image Description**: Utilizes a cutting-edge image-to-text model from Hugging Face to generate detailed and contextually rich descriptions of images.
- **OCR (Optical Character Recognition)**: Extracts text from images with high accuracy using Azure Form Recognizer, making it possible to analyze and search for embedded text within images.
- **Key Concept Extraction**: Identifies key concepts and entities from the extracted text using Spacy, enhancing the quality and relevance of search results.
- **Resource Search & Retrieval**: Automatically performs web searches based on extracted concepts and provides a list of relevant resources with brief descriptions.
- **PDF Summarization**: Employs a fine-tuned T5 model to generate concise summaries of PDF documents, suitable for extracting insights from long texts following RAG architecture principles.
- **Chunked Text Processing**: Splits large PDF documents into manageable chunks for efficient processing and summarization without losing context.
- **Embeddings & Vector Store**: Uses Hugging Face embeddings and ChromaDB to store and retrieve document vectors, enabling efficient and scalable document retrieval.
- **Custom Prompting**: Integrates a customizable prompt template to fine-tune the summarization process according to specific user needs.

## Technologies Used

- **Gradio**: For creating an intuitive and interactive web interface, enabling easy access to the tool's features.
- **Transformers & BitsAndBytes**: For running efficient, quantized models that deliver high performance on image-to-text and text summarization tasks.
- **Azure AI Form Recognizer**: A reliable OCR solution that accurately captures and processes text from images.
- **Spacy**: A robust NLP library used for named entity recognition and key concept extraction.
- **BeautifulSoup & Requests**: Essential tools for web scraping, enabling dynamic search of relevant resources based on extracted content.
- **LangChain**: For document processing and managing the integration of PDF loaders, text splitters, and retrieval systems.
- **ChromaDB**: A high-performance vector database for storing and querying embeddings generated from PDF content.
- **PyTorch**: Backend engine powering the models, with dynamic quantization to optimize performance.


