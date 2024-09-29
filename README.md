# Text Extracted - OCR Web Application

## Overview

Text Extracted is a web-based application designed to extract text from images using Optical Character Recognition (OCR). The application utilizes `pytesseract` for OCR processing and provides an intuitive interface using `Streamlit`. Additionally, the app features keyword extraction from the OCR-processed text, making it useful for data extraction, analysis, or research purposes.

## Features

- **Image Upload**: Users can upload images containing text.
- **Text Extraction**: The app extracts text from uploaded images using `pytesseract`.
- **Keyword Extraction**: Allows users to extract important keywords from the extracted text.
- **User-Friendly Interface**: Simple web interface for easy interaction.

## Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **OCR Engine**: pytesseract (Tesseract-OCR)
- **Libraries**:
  - `streamlit`: For creating the web interface.
  - `pytesseract`: For performing OCR on images.
  - `Pillow`: For handling image files.
  - `regex`: For text manipulation and keyword extraction.

## Prerequisites

Before running the application, ensure that you have the following installed:

1. **Python 3.7 or higher**: You can download Python [here](https://www.python.org/downloads/).
2. **Tesseract-OCR**: The OCR engine required by `pytesseract`. You can install it as follows:
   - **macOS**: 
     ```bash
     brew install tesseract
     ```
   - **Ubuntu**: 
     ```bash
     sudo apt-get install tesseract-ocr
     ```
   - **Windows**: Download the installer from [here](https://github.com/tesseract-ocr/tesseract/wiki) and follow the instructions.

## Installation

Follow the steps below to set up the project locally:

1. **Clone the Repository**:
   Open your terminal or command prompt and run:
   ```bash
   git clone <repo-link>
   cd Text_Extracted-main
2. **Set Up a Virtual Environment (Optional but recommended)**: Create and activate a virtual environment to manage project dependencies.
3. 
