# Data Extraction From Handfilled Form
---
The project is about performing ocr on a particular bank form.

## main.ipynb 
---
This file contains the main code for the program. For the detection of boxes i defined two kernals using opencv, one for detecting horizontal lines and another for detecting vertical line. Then i used contour detection for pinpointing the boxes in the document.After the identification of the boxes the image is fed into a CNN prediction model.


## CNN_Traning.ipynd
---
The file contains the code for the traning of the CNN using the mnist dataset.

## Images 
---
The file contains the images used for the project and also the resulting images after the application of the program