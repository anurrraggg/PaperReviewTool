# Research Paper Format Checker

## Overview

This Python script automates the process of checking whether research papers in PDF format adhere to a specific structure. It scans PDFs for required sections, checks for the presence of numbered sections, and generates a detailed report.

## Features

- **Section Detection**: Identifies key sections such as `Abstract`, `Introduction`, `Methodology`, etc.
- **Numbered Sections**: Checks for the presence of at least three numbered sections in the document.
- **Batch Processing**: Processes all PDFs in a specified folder.
- **Report Generation**: Outputs results as a CSV file and a summary as a text file.

## Requirements

- Python 3.7+
- Libraries: `os`, `pandas`, `fitz` (PyMuPDF), `re`

### Installation

1. Clone the repository or copy the script.
2. Install the required Python libraries:
   ```bash
   pip install pandas pymupdf
