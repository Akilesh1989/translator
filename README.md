Translator is an attempt to read in an image and extract the contents of the image for non english languages.

I have been using pytesseract for my work.

Steps:
1. Download and add language packs to Tesseract OCR
- You can download the tessdata packs from https://github.com/tesseract-ocr/tessdata
- Once downloaded unzip this package.
2. The next and probably the most important step is to set the TESSDATA_PREFIX.
```
export TESSDATA_PREFIX=<PATH_TO_TESSDATA_FOLDER>
```

References:
1. https://www.pyimagesearch.com/2020/08/03/tesseract-ocr-for-non-english-languages/
