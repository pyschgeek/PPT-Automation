# PowerPoint Presentation Analyzer

## Overview
This script is designed to extract and analyze the content of a PowerPoint (`.pptx`) file. It iterates through each slide and extracts metadata, text content, placeholders, and tables.

## Features
- Loads a PowerPoint presentation from a given path.
- Iterates through all slides and shapes.
- Extracts details about shape types, IDs, names, and placeholders.
- Retrieves text content from text boxes, including paragraph and run details.
- Extracts table data for structured analysis.

## Requirements
- Python 3.x
- `python-pptx` library (`pip install python-pptx`)

## How to Use
1. Update the `ppt_path` variable with the path to your PowerPoint file.
2. Run the script using:
   ```sh
   python analyze_ppt.py
