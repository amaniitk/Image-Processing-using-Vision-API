# Image-Processing-using-Vision-API
The objective of this assignment was to build a program using Vision API to 
analyze the uploaded image. The program allows users to upload images, 
perform OCR, segment visual elements, and extract texts and visual elements 
separately. 

# Technology Used: 
**Azure Computer Vision API:** Used for OCR and text extraction. 

**OpenCV:** Utilized for image processing tasks such as grayscale conversion, 
contour detection, and visual element segmentation. 

**Matplotlib:** Used for visualizing images and segmented visual elements. 

# Implementation Details: 
**User Interface:** Implemented a basic web interface using the files module 
from Google Colab to allow users to upload images. 

**Image Processing:**
• Converted uploaded images to grayscale 

• Utilized the Azure Computer Vision API for OCR to extract text 
from the images. 

• Implemented visual element segmentation using OpenCV to 
identify and highlight visual elements. 
**Output:** Displayed the segmented visual elements alongside the original 
image using Matplotlib. 
**Multiple Image Processing:** Extended the program to support the 
processing of multiple images uploaded by the user, providing separate 
outputs for each image. 
