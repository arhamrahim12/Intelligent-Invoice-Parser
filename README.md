# Intelligent Invoice Parser

This project is an Intelligent Invoice Parser that extracts and validates key information from invoice PDFs using OCR (Optical Character Recognition) and Regex.

## Features

* Extracts key invoice details (Invoice Number, Vendor, Date, Due Date, Total, Tax) from PDFs.
* Supports both text-based and scanned PDFs (OCR fallback).
* Validates invoice totals against calculated values.
* Outputs parsed invoice details in JSON format.
* Easy-to-use, minimal setup.

## Requirements

* Python 3.8+
* Libraries: `pdfplumber`, `pdf2image`, `pytesseract`, `pillow`, `regex`, `openai`

## Installation

1. Install the required libraries:

```bash
pip install pdfplumber pdf2image pytesseract pillow regex openai
apt-get update -qq && apt-get install -y -qq poppler-utils tesseract-ocr
```

2. Ensure you have `tesseract-ocr` installed for OCR support.

## Usage

1. Upload your invoice PDF file.
2. Run the script.
3. The parsed invoice details will be displayed and saved as JSON.

## User Instructions

1. Place your invoice PDF in the specified directory.
2. Execute the script by running all cells.
3. The extracted data will be displayed and downloadable as JSON.

