# Speed-up-Claims-Processing-SuCP

This repo includes a customized text summarization tool that I developed voluntarily for Anthem Inc, aiming to speed up the claims process.  

The key idea of this tool is to use tesseract OCR to extract the text from an image uploaded by a user and provide a summary of the text. Some customized features would allow users to enter the patient ID and provider ID associated with the uploaded image. Besides, users can also put in their decision regarding the uploaded image by typing "Approve" or "Decline".

I use the Flask package, micro web framework written in Python, to showcase how the tools can be used on a daily basis, and I include 4 screenshots for more details of the usage of the tool. 

Step1.png: Home page

Step2.png: Upload image; Fill in patient ID and provider ID.

Step3.png: Summary of the text for easier decision making. Users can compare the extracted text with the uploaded image.

Step4.png: Type in "Approve" or "Decline" 
