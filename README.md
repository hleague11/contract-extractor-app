# Contract Extractor App

## Overview
This Streamlit-based web app allows users to:
1. Upload a PDF.
2. Automatically extract:
   - Contract dates
   - COF identifiers (e.g., `COF12345`)
   - Customer names (e.g., `Customer Name: John Smith`)
3. Split the PDF into separate files per COF.
4. Download each file locally, named like `COF_John Smith.pdf`.

## Setup and Deployment

### Install Dependencies
1. Install Streamlit and PyMuPDF:
   ```bash
   pip install streamlit pymupdf
   ```# contract-extractor-app
