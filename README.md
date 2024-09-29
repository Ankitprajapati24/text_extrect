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

### Follow the steps below to set up the project locally:

1. **Clone the Repository**:
   Open your terminal or command prompt and run:

```bash
   git clone https://github.com/Goutam16-Withcode/Text_Extracted.git
   cd Text_Extracted-main
```

2. **Set Up a Virtual Environment (Optional but recommended)**: Create and activate a virtual environment to manage project dependencies.
  
```bash
python -m venv venv
# Activate the virtual environment
source venv/bin/activate  # On Windows: venv\\Scripts\\activate
```

3. **Install Dependencies:** Use the `requirements.txt` file to install the necessary Python packages:

```bash
   pip install -r requirements.txt
```

4. **Run the Application:** Start the Streamlit application by running the command below:
   
```bash
streamlit run app.py
```

5. **Open the Application:** Once the application starts, Streamlit will automatically open your default web browser. If not, you can manually visit http://localhost:8501.
   
## File Structure

`**app.py:**`  The main application file that handles the Streamlit interface and coordinates image uploads, OCR processing, and keyword extraction.

`**ocr.py:**`  Contains the logic for processing images using `pytesseract` and extracting keywords from the extracted text.
**requirements.txt:** Lists all the Python dependencies needed to run the application.

## Upload an Image: On the application page, you will see an option to upload an image file. Click the "Browse" button and select an image that contains text.
**Extract Text:** Once the image is uploaded, the application will process the image and display the extracted text.
Extract Keywords (Optional): If required, you can click the button to extract keywords from the extracted text.

## Example
**Input**
An image containing text such as a scanned document, a screenshot, or any image with visible words.

**Output**
The raw text extracted from the image.
A list of keywords derived from the extracted text.
**Dependencies**
The project uses the following Python libraries:

1. `streamlit`
2. `pytesseract`
3. `Pillow`
4. `regex`
These dependencies are listed in the `requirements.txt` file and can be installed using `pip install -r requirements.txt`.


## Screen Shots:
![1](https://github.com/user-attachments/assets/9c3a5779-769f-4367-9ea9-e501a25b89b8)![2](https://github.com/user-attachments/assets/e83695e4-1ba8-48e9-b820-add607abdbf3)

![3](https://github.com/user-attachments/assets/b0116d65-6193-44dd-a3ba-c639638d80d2)![4](https://github.com/user-attachments/assets/12b6a0bd-8f8b-435a-9e79-c2f7272eb0ef)

## Image Uploaded: 
![6](https://github.com/user-attachments/assets/91204189-0396-4bb5-a05c-2876b4c0425f)



