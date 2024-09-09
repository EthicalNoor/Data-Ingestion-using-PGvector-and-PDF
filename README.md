# PDF Text Processing and Embeddings Storage

This short assignment demonstrates a workflow for processing text extracted from a PDF document and generating vector embeddings using HuggingFace models. The embeddings are then stored in PostgreSQL using both JSON and PGVector formats.

## Key Features

- **PDF Text Extraction**: Extract and clean text from PDF documents.
- **Text Chunking**: Split extracted text into manageable chunks.
- **Embedding Generation**: Create embeddings for text chunks using HuggingFace models.
- **Storage**: Store embeddings in PostgreSQL using JSON and PGVector formats.
- **Querying**: Perform similarity searches on stored embeddings.

## Files

- **Notebook**: Contains the code and explanations for the entire process.
- **PDF**: The PDF document used for text extraction and embedding generation.

## Prerequisites

- PostgreSQL
- PGVector extension for PostgreSQL
- Python libraries: `psycopg2`, `langchain-community`, `langchain`, `embeddings`

For more details, refer to the provided Jupyter Notebook and PDF file.
