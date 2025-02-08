# Brand Detection using OCR

This project demonstrates how to detect brand names from images using Optical Character Recognition (OCR). It leverages the power of Pytesseract and OpenCV to identify and extract text from images, then matches the extracted text with a predefined list of brand names.

## How it Works

1. **Image Preprocessing:** The input image is preprocessed to enhance text clarity. This includes converting to grayscale, applying Gaussian blur for noise reduction, and using Canny edge detection to highlight text boundaries.

2. **Text Extraction:** Pytesseract, an OCR engine, is used to extract text from the preprocessed image.

3. **Brand Matching:** The extracted text is compared against a list of known brand names. If a match is found, the brand is identified.

4. **Visualization:** The original image is overlaid with bounding boxes around detected brand names for clear visualization.

## Potential Applications

- **Market Research:** Analyze product placement and brand visibility in images.
- **Brand Monitoring:** Track brand mentions and sentiment in social media images.
- **Inventory Management:** Automate product identification and categorization.

## Docs:

- OpenCV documentation : https://docs.opencv.org/4.x/index.html
- Tesseract-ocr docs : https://tesseract-ocr.github.io/tessdoc/
