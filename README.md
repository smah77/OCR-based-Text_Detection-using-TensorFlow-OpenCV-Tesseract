DISCLAIMER: *** NOT MY END TO END PRPJECT : learnt and tried to implement from coursera *** 

In this project, a program developed in Python that is able to extract text from images and video using Tensorflow, OpenCV, and Tesseract. 
Tasks Covered:
-image extraction
-augmentation with OpenCV
-OpenCVs basic commands utilized. 
-training is done by Tensorflow to identify a specific ROI (region of interest) in an image, and 
-extract and augment the ROI using OpenCV. 
-integrated Tesseract's text recognition functionality into program, and piping the final enhanced image containing text to Tesseract for extraction of text data using OCR (Optical Character Recognition) technology.

•	Tensorflow Model Training- used a pre-trained model
•	Use OpenCV to capture frames from a video or, for our demonstration, singular images, for detection of text regions. 
•	Use OpenCV to apply filters and enhancements to extracted copies of the regions of our image or frame that contains text, using bounding box coordinates from Tensorflow
•	Pass the resulting enhanced image containing text to Google's Tesseract 4 Optical Character Recognition (OCR) engine, using hooks from the pytesseract Python module, to obtain resulting text in the form of a string.

