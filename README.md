# IDENTIFY-AADHAR-PAN-AND-EXTRACT-DETAILS-FROM-AADHAR-PAN-CARD

This project identifies whether a given (input)image (.jpg format) is a aadhar card or pan card and once identified extracts the details in the card such as aadhar number, pan number, name of the peson, DOB, father name etc.

STEP 1: IDENTIFIES WHETHER GIVEN IMAGE IS AADHAR OR PAN CARD

STEP 2: OCR(OPTICAL CHARACTER RECOGNITION) IS APPLIED ON THE IMAGE AND THE DETAILS ARE EXTRACTED using PYTESSERACT. 

NOTE: 1. AS PYTESSERACT IS TRAINED ONLY FOR ENGLISH LANGUAGE, THE QUALITY OF THE DETAILS EXTRACTED FROM THE AADHAR/PAN CARD IN REGIONAL LANGUGAGE IS MUCH MORE DIFFICULT AND QUALITY SEEMS TO BE LESS WHEN COMPARED TO DETAILS IN ENGLISH. 

NOTE : 2. AS PYTESSERACT EXTRACT TEXT INFORMATION FROM IMAGE THERE MIGHT NOT BE 100% ACCURACY IN EXTRACTING THE DETAILS IN EVERY CASE.

* INPUT : Please check the input folder for input images
* OUTPUT : Please check the .json file for output obtained.

USAGE : 

1. DOwnload the folder and make sure aadhar_read.py and pan_read.py are in same directory as detect.ipynb notebook.

2. OPEN DETECT.ipynb notebook and change the path to your respective input image path and run the notebook

3. GIve output path for the data to be stored in .json /.txt file 

4. You can see the final ouput obtained and the details stored in info.json which detects the type of the image(whether aadhar/pan) and its relevant details
