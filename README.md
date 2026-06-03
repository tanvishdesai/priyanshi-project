# Computer Vision Lip Reading 2.0

An advanced computer vision pipeline designed to automate lip-reading and generate corresponding transcripts and reports.

## Overview

This project tackles the complex challenge of interpreting human speech solely from visual cues (lip movements). It relies on robust deep learning architectures tailored for spatio-temporal data extraction.

## Features

- **Lip Reading Engine**: The core `Computer-Vision-Lip-Reading-2.0` module contains the model weights, preprocessing scripts, and inference logic to convert video frames of lips into text.
- **Automated Reporting**: Built-in scripts (`generate_report.py`, `update_report.py`) automatically structure the inferred text into comprehensive, formatted reports.
- **Documentation Engine**: Maintains a rolling document (`report_dump.txt`) to log predictions and pipeline metrics.

## Getting Started

1. Set up the environment and install dependencies inside the `Computer-Vision-Lip-Reading-2.0` directory.
2. Provide an input video containing clear facial/lip features.
3. Run the report generation script to extract the text:
   ```bash
   python generate_report.py
   ```
