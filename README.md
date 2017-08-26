# Content : Computer Vision

## Project : Document Scanner

This project makes use of OpenCV library to detect documents in an image(by using contours) . Then a perspective transformation is applied on them to crop out the document. Finally, adaptive thresholding is applied to the image to give the look of a scanned document.

### Before Scanning:
![mybill](https://user-images.githubusercontent.com/22278430/29742608-1c82db80-8aa0-11e7-9f68-73b62c770a36.jpg)

### Detecting the document

![b1](https://user-images.githubusercontent.com/22278430/29742612-36c7857c-8aa0-11e7-87da-c5a41a1d1955.JPG)

### Final Result

![b2](https://user-images.githubusercontent.com/22278430/29742627-6152b46a-8aa0-11e7-8b37-e8ece5b29890.JPG)

### This project makes use imutils for the perpective transform. Get it from here: https://github.com/jrosebr1/imutils
