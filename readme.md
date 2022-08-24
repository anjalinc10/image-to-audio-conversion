### Project_Introduction
This is Image to audio conversion project.

### Project Description
Text-to-speech is commonly used as an accessibility feature to help people who have trouble reading on-screen text, but it's also convenient for those who want to be read to. You can find text-to-speech features in many places today, including ebook readers, word processors, internet browsers, and more

### How to Install 

In order to run this code you're supposed to have pytesseract and google text to sound libary installed on your machine, you can just use pip command to this.

-> pip install pytesseract

-> pip install gTTS

Note: Installing pytesseeract can be an issue sometimes, so there ways in which you could do this effectively as follow,

1) install pytesseract in window
2) import pytesseract - import pytesseract
3) specify path - pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-   OCR\tesseract.exe'

### Run the Project
By default the script will load an image with name image_to_sound.png from its current directory. 

**input -:** any image you want to read, just specify its path with name

**output -:** audio which help you to read your image.




