# Image Editor

This is an image editing application is comprised of two parts- A GUI for single image editing and a text-based interface for editing an entire folder of images at once.


### Prerequisites

* Python 2
* PIL (Python Imaging library).The following command installs PIL:
```
pip install pillow
```
* Pytesseract
```
pip install pillow
```
There is a “Tesseract-OCR” database that you will have to place in "C:\Program Files (x86)" in your computer, which is included in this repository. After this step, you have to either set the path of “Tesseract-OCR” as an environment variable, or add the following line in your program:
```
pytesseract.pytesseract.tesseract_cmd = 'C:/Program Files(x86)/Tesseract-OCR/tesseract'
```
### Sample outputs
In the GUI mode, the following window is displayed:


<img width="300" alt="3" src="https://user-images.githubusercontent.com/17317792/39069074-38523d80-44fc-11e8-90b7-a72f211fef8b.PNG">


If, for example, the brighten button is clicked:


<img width="299" alt="4" src="https://user-images.githubusercontent.com/17317792/39069106-56244fe2-44fc-11e8-9e5a-929a5ed8c07e.PNG">


..and so on.You can also use OCR (Optical Character Recognition) to get text from an image(if the font is recognisable).


The text based mode is similar, but there is no GUI and the operations are applied to a batch of images:


This:


<img width="934" alt="14" src="https://user-images.githubusercontent.com/17317792/39069226-c2fd7350-44fc-11e8-9fd2-a7370ca88a1f.PNG">


...can become this:


<img width="936" alt="16" src="https://user-images.githubusercontent.com/17317792/39069235-c8b147c2-44fc-11e8-8389-a2854f9a91c0.PNG">


### Acknowledgements
* A few parts are **DEFINITELY** from a stackoverflow article, but I can't remember which :stuck_out_tongue:
