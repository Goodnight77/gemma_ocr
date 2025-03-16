
# Gemma3 OCR

## Project Overview

Gemma-3 OCR is a Streamlit-based application that extracts structured text from images using the Gemma-3 Vision model via Ollama. The app allows users to upload an image, process it, and receive extracted text in a structured Markdown format.

## Features

* Image Upload: Users can upload PNG, JPG, or JPEG images.

* OCR Extraction: Utilizes the Gemma-3 Vision model to extract and format text.

* Clear Results: Users can clear extracted results with a button.

* User-Friendly Interface: A simple and interactive UI using Streamlit.

## Installation

**Installation Steps:**

1. Clone the repository: `git clone <repository_url>` (Replace `<repository_url>` with the actual repository URL).
2. Navigate to the project directory: `cd gemma3_OCR`
3. Ensure you have Python 3 installed and the following dependencies:


**Prerequisites:**
```bash
  pip install streamlit ollama pillow
```


## Usage

1.  Navigate to the project directory: `cd gemma3_OCR`
2.  Run the application using: `streamlit run app.py`
3.  Upload an image and click the Extract Text button to process it.



## Project Structure
```bash
  .
  ├── app.py              # Main application script
  ├── images/
  │   ├── gemma3.png      # Logo for the UI
  └── README.md           # Project documentation
```
## Acknowledgments

* Built using Streamlit

* Powered by Ollama's Gemma-3 Vision
