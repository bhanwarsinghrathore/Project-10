# Medical Report Information Extraction using Gemini Vision

## Overview

This project extracts structured information from scanned medical reports using Google's Gemini Vision model.

The system automatically analyzes report images and extracts important medical information into structured CSV and Excel formats.

## Features

- Medical report image processing
- Gemini Vision based information extraction
- Automatic random image selection
- Structured JSON generation
- CSV export
- Excel export
- Google Colab implementation
- Google Drive integration

## Extracted Fields

- Name
- Test Asked
- Test Name
- Technology
- Value
- Unit
- Clinical Significance

## Dataset

Dataset contains 100 scanned medical report images.

Random selection:
- 5 images for training phase
- 2 images for testing phase

## Technologies Used

- Python
- Google Colab
- Google Drive
- Google Gemini API
- Pandas
- OpenPyXL
- Pillow

## Workflow

Dataset Images
↓
Random Image Selection
↓
Gemini Vision
↓
Information Extraction
↓
JSON Output
↓
CSV / Excel Export

## Output

The extracted information is saved as:

- reports.csv
- reports.xlsx

## Future Scope

- PDF support
- Multi-language extraction
- Streamlit deployment
- Healthcare database integration

## Author

Bhanwar Singh