# cs445-final-project
**Note: Github has a max file size of 25MB.  google "frozen_east_text_detection.pb" to find a copy of this widely used pre trained model.

CS445 Computational Photography
University of Illinois Urbana-Champaign
Fa2023
Scene Text Detection - Final Project

Description
This project is developed as part of the CS445 course (Fall 2023) and focuses on the detection of text in various scenes. Utilizing a combination of image processing techniques and text detection algorithms, the program aims to efficiently identify and extract text from a given image.


Installation
To run this project, you will need Python installed on your machine along with several dependencies.

You can install the required packages using the following command:
pip install exifread, pillow, numpy opencv-python matplotlib, matplotlib-inline, pytesseract, tesseract, imutils.  There is also a requirements.txt file provided so you may run pip install -r requirements.txt

Usage
After installing the required dependencies, you can run the script from the command line. Make sure to place the image files to be processed in a folder called 'dataset'
There is an option to uncomment line 446 and call preprocess_image() function and/or edge_detection() to pre process the images before running through EAST text detection.


python3 final_project.py

Features
Text detection in various environmental scenes.
Image preprocessing for improved text recognition.
Integration with PyTesseract for OCR (Optical Character Recognition).
Non-maximum suppression for accurate text localization.

File Structure
final_project.py: The main Python script containing all the logic for text detection and processing.
Folder - 'dataset' for images to be analyzed.

Limitations and Known Issues
The script may have varying performance on different types of images, especially with complex backgrounds or varied lighting conditions.  Report shows processing time and the one outlier was a large image.

