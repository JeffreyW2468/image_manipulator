# image_manipulator
 codecademy ap csa java project: 
 
 leverages BufferedImage and ImageIO classes for image conversion between image and 2D arrays holding pixel data
 
 traverses pixel data arrays and manipulates orientation through index reversal / changes colors through RGBA getter methods and rgba array manipulation
 
 generates random images/rectangles by passing in 2D image arrays, color integers, etc as arguments to methods and utilizing row-major traversal and conditional statements to create image outputs through traditional file IO
 
 sample of passing apple jpg image through negative method:
![negative_apple](https://user-images.githubusercontent.com/70827087/145701258-ea675672-ca55-43dd-9038-84d924091e2e.jpg)

Brief implementation instructions:

- make sure that you have java and respective extensions installed in your IDE of preference
- in terminal/command prompt, run "javac ImageProcessing.java" to compile manipulation program and "java ImageProcessing" to run it
- images can be changed by uploading different images to the directory and passing in "./image_name.jpg" (jpg, png, etc) to imgToTwoD method
