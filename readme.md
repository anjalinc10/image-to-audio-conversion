### Project_Introduction
This is Image to audio conversion project.

### Project Description
Text-to-speech is commonly used as an accessibility feature to help people who have trouble reading on-screen text, but it's also convenient for those who want to be read to. You can find text-to-speech features in many places today, including ebook readers, word processors, internet browsers, and more

**Libraries Used**
**1) PIL** - **Python Imaging Library** (expansion of PIL) is the de facto image processing package for Python language. It incorporates lightweight image processing tools that aids in editing, creating and saving images.
**2) gTTS** - **Convert Text to Speech in Python** One of such APIs is the **Google Text to Speech API** commonly known as the gTTS API. gTTS is a very easy to use tool which converts the text entered, into audio which can be saved as a mp3 file
**3) pytesseract** -Python-tesseract is an optical character recognition (**OCR**) tool for python. That is, it will **recognize and “read” the text embedded in images.**
Python-tesseract is a wrapper for Google’s Tesseract-OCR Engine. It is also useful as a stand-alone invocation script to tesseract, as it can **read all image types supported by the Pillow** and Leptonica imaging libraries, including jpeg, png, gif, bmp, tiff, and others. Additionally, if used as a script, Python-tesseract will print the recognized text instead of writing it to a file.
### How to Install 

In order to run this code you're supposed to have pytesseract and google text to sound libary installed on your machine, you can just use pip command to this.

-> pip install pytesseract

-> pip install gTTS

Note: Installing pytesseeract can be an issue sometimes, so there ways in which you could do this effectively as follow,

1) install pytesseract in window
2) import pytesseract in source code - import pytesseract
3) specify path - pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-   OCR\tesseract.exe'

### Run the Project
By default the script will load an image with name image_to_sound.png from its current directory. 

**input -:** any image you want to read, just specify its path with name

**output -:** audio which help you to read your image.




