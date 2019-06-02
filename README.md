## Portable-QR-Code-Qenerator-with-python
Generate Qr codes on the go!!                                                                                                           
No internet connection required!!
        
# Objective
1.The main objective of the application is to utilise new libraries and produce QR Code for the given data.                                
2.Also this application bypasses the saving process beforing displaying it.                                                                
3.This allows the user to save the QR Code once the desired data is shown.                                                                 
4.This provides a good UI for the user to work with.                                                                                       

# Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install pyperclip
pip install qrcode
pip install pillow    #for PIL
```
# Visuals

![qrgenerator](https://user-images.githubusercontent.com/24393343/58764209-081ef500-8582-11e9-8e1c-a8993c9baa33.jpg)
 
# Run Locally
1. Method-1
* Clone the repo.
* Open the file and extract it.
* Edit the .py File in any editor and run it.

2. Method-2
* Go to this website : https://absanthosh01.wixsite.com/pythonist
* Download the application and run the portable .exe file!!
# Requirnments

```bash
import PIL 
import PIL.Image
import PIL.ImageTk
import base64
import os
import pyperclip
import qrcode
import tkinter

from PIL import Image
from resizeimage import resizeimage
from tkinter import *
from tkinter import PhotoImage 
from tkinter import filedialog
from tkinter import messagebox

```
    
