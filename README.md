# DocuWiz AI 📚

Welcome to **DocuWiz AI**, an advanced document intelligence application designed to analyze a variety of document types. Powered by cutting-edge AI technologies, DocuWiz AI offers features such as text extraction, summarization, sentiment analysis, topic modeling, and comprehensive data analysis for CSV and Excel files.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Text Extraction**: Supports PDFs, DOCX, TXT, PPTX, CSV, and XLSX.
- **Summarization**: Provides concise summaries of lengthy documents.
- **Sentiment Analysis**: Detects the sentiment of the document's content.
- **Topic Modeling**: Identifies the main topics discussed in the document.
- **Data Analysis**: Offers statistical analysis and visualizations for CSV and Excel files.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/SohaibKhaliq/DocuWiz-AI.git
    cd DocuWiz-AI
    ```
2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Set your OpenRouter environment variables before running the app:
    ```bash
    set OPENROUTER_API_KEY=your_key_here
    set OPENROUTER_MODEL=openai/gpt-4o-mini
    ```

## Usage
1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```
2. Open your web browser and go to `http://localhost:8501` to access the application.

3. Upload a document (PDF, DOCX, TXT, PPTX, CSV, or XLSX) and use the provided features to analyze the document.

## Technologies Used
- **Python**: The main programming language.
- **Streamlit**: For the web interface.
- **PyPDF2**: For PDF text extraction.
- **python-docx**: For DOCX text extraction.
- **python-pptx**: For PPTX text extraction.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization.
- **OpenRouter & LangChain**: For document Q&A.
- **Sentence Transformers**: For local document embeddings.
- **Transformers**: For NLP tasks such as summarization, sentiment analysis, and topic modeling.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


