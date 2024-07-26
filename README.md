**PDF to JPG Converter**

This Python script converts all pages of PDF files in a specified directory into JPG images. Each PDF file in the directory is processed, and each page of the PDF is saved as a separate JPG image in the output directory.

**Features**

    Converts each page of a PDF to a JPG image.
    Saves JPG images in a specified output directory.
    Creates the output directory if it does not already exist.
**Requirements**

    Python 3.x
    pdf2image library
    Pillow library

1. Import Libraries

        import os
        from pdf2image import convert_from_path
        from PIL import Image

import os: Imports the os module to interact with the operating system for file and directory operations.
from pdf2image import convert_from_path: Imports convert_from_path from pdf2image to convert PDF pages to images.
from PIL import Image: Imports the Image class from the Pillow library for image processing.
