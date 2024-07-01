# Multilingual Optical Character Recognition (OCR) System

Welcome to the Multilingual OCR System project! This project leverages advanced technologies and APIs such as OpenCV, Pytesseract, Googletrans, PIL, and Tkinter to achieve efficient text extraction and translation from images. This system is particularly useful in the fintech industry for automating various tasks such as data entry, KYC processes, invoice processing, cheque clearing, and improving customer service.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

The Multilingual OCR System is designed to read text from images, recognize and translate it into multiple languages. The project integrates various libraries and APIs to ensure high accuracy and efficiency in text extraction and translation.

## Features

- **Image Preprocessing:** Enhances image quality for better OCR performance using OpenCV.
- **Text Extraction:** Utilizes Pytesseract for character recognition with CNNs and LSTM networks.
- **Multilingual Translation:** Supports translation into multiple languages using Googletrans.
- **User-Friendly GUI:** Provides an intuitive interface for users to upload images and view results using Tkinter.

## Technologies Used

1. **OpenCV:** Used for image preprocessing tasks such as noise reduction, thresholding, and edge detection.
2. **Pytesseract:** A Python wrapper for the Tesseract-OCR Engine, leveraging CNNs and LSTM networks for text recognition.
3. **Googletrans:** A Python API for Google Translate, using sequence-to-sequence models and attention mechanisms for accurate translation.
4. **PIL (Python Imaging Library):** Used for basic image handling tasks like loading, converting, and resizing images.
5. **Tkinter:** A standard Python interface for creating graphical user interfaces.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your_username/multilingual-ocr-system.git
   cd multilingual-ocr-system
   ```

2. **Create a virtual environment and activate it:**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Download and install Tesseract-OCR:**
   - For Windows: Download the installer from [Tesseract at UB Mannheim](https://github.com/UB-Mannheim/tesseract/wiki).
   - For macOS: Use Homebrew to install Tesseract:

     ```bash
     brew install tesseract
     ```

   - For Linux: Use the package manager to install Tesseract:

     ```bash
     sudo apt-get install tesseract-ocr
     ```

## Usage

1. **Run the GUI application:**

   ```bash
   python main.py
   ```

2. **Use the interface:**
   - Click on the "Browse Image" button to select an image file.
   - Choose the desired language for translation from the dropdown menu.
   - The system will display the extracted text and its translation.
