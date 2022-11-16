# Image-TextExtraction-using-EasyOCR
Here, we are using the Reader class from easyocr class and then passing [‘en’] as an attribute which means that now it will only detect the English part of the image as text, if it will find other languages like Chinese and Japanese then it will ignore those text.
Now, as in the above line, we have set the attribute for language so, here we are loading the IMAGE_PATH in the readText() function and one will find out a parameter which is “paragraph” here it is set as False which means that now easyOCR will not combine the results i.e. if easyocr will encounter multiple texts it will not combine them instead it will show them separately.
Getting the result in the form of a 2-D NumPy array.
