# EXTRACT

## Introduction

EXTRACT is an optical character recognition engine for various operating systems which extracts texts from an image and converts them to plain text.

This model is a very primitive form of the original google tesseract which extracts texts from an image and converts them to plain text.

## Modules/Library REQUIREMENTS:

  1) os
  2) numpy
  3) PIL
  4) sys
  5) keras
  6) cropyble
  7) cv2
  8) shutil
  
## Features
 
a)  Extracts text from input image<br/>
b) Works on lowercase,uppercase, number ans special characters.<br/>
c) Saves the output in output.txt to allow search.<br/>

## How To Run the script:

NOTE1:- The trained model is not provided. So for the very first time run the script as it is. Once the model is trained:
                                          COMMENT OUT 'Train_Model()' then run the script for further use.
                                          


Run the script on your terminal: 'python3 tesseract.py':




| Input Image |  Output |
| ------------- | ------------- |
| <img align="left" width="350" height="150" src=sentences/say.png> | <img align="left" width="420" height="50" src=sentences/say_output.png> |
| <img align="left" width="350" height="150" src=sentences/ex5.png> | <img align="left" width="420" height="50" src=sentences/ex5_output.png> |
| <img align="left" width="350" height="150" src=sentences/ex7.png> | <img align="left" width="420" height="50" src=sentences/ex7_output.png> |
| <img align="left" width="350" height="150" src=sentences/say3.png>  |<img align="left" width="420" height="50" src=sentences/say3_output.png> |







## Contributors

- Akarsh Malik
- Angad Ripudaman Singh Bajwa

## Future Work

1)  To add characters of your own, make sure to add them in the train and test dataset
2) Change the output of the softmax layer in Train_Model function to the total number of trained characters.
2) Re-train the model
3) Test your image
