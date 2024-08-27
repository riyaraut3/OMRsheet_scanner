# Automatic OMR Sheet Scanner and Grader

## Project Overview

This project is developed by our team to explore the integration of machine learning with OpenCV for Optical Mark Recognition (OMR). The primary objective is to automatically grade OMR sheets after they are scanned. This project can be applied in educational institutions for efficient and accurate grading of multiple-choice exams.

## Features

- **Automated Scanning**: The OMR sheets are scanned, and the software automatically identifies the answer bubbles.
- **Grading System**: The system compares the scanned responses with the correct answers to generate a score for each sheet.
- **Image Processing**: Leveraging OpenCV, the software preprocesses the images to ensure accurate detection of filled bubbles.
- **Customizable OMR Sheet**: The system can be adapted to different formats of OMR sheets.

## Prerequisites

To run this project, you'll need the following:

- Python 3.x
- OpenCV
- NumPy
- Scikit-learn
- Jupyter Notebook (for running the provided notebook file)

You can install the required libraries using pip:

```bash
pip install opencv-python numpy scikit-learn jupyter
