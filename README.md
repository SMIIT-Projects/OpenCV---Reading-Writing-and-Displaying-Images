## OpenCV- Reading Writing and Displaying Images
### OpenCV-Python: 
Open Source Computer Vision called as OpenCV. OpenCV-Python is a library of Python bindings designed to solve computer vision problems. OpenCV-Python makes use of Numpy, which is a highly optimized library for numerical operations with a MATLAB-style syntax. All the OpenCV array structures are converted to and from Numpy arrays.

### Steps to Install OpenCV on Windows
1.	Install Python on your system
2.	Install pip
3.	Install OpenCV library using pip

After the installation of the Python and pip, we can directly install the OpenCV library and start using them. To install the library, we need to enter the given command in the terminal.

### Reading Images
To read the contents of an image, we have a function cv2.imread(). The image should be in the same directory. If not, then the full path of the image should be given.
To read an image, opencv provide a cv2.imread() function . This function support various file format like JPG, BMP, PNG, JPEG, TIFF etc.
The cv2.imread() function returns a Numpy array representing the image.
The first argument is the file name. The image should be in the working directory (or) a full path of the image should be given.

Syntax:
cv2.imread(path, flag)

### Display an image: 

![4](https://user-images.githubusercontent.com/80674012/115228198-19019100-a12f-11eb-9ed1-7a0344f51d9a.png)

Use the function cv2.imshow() to display an image in a window.
Syntax
cv2.imshow(window_name, image)

### Display this gray scale image

![6](https://user-images.githubusercontent.com/80674012/115228382-50703d80-a12f-11eb-9774-91d91e8a8074.png)

### Saving or Writing image: cv2.imwrite()
cv2.imwrite() method is used to save an image to any storage device. This will save the image according to the specified format in the current working directory.
Syntax
cv2.imwrite(filename, image)

### Resize Image

### Image Frame


### Blog Site:   https://www.smiit.xyz/opencv-read-write-and-display-images/

### GitHub Link:  https://github.com/SMIIT-Projects/OpenCV-Reading-Writing-and-Displaying-Images

### Tools and Technologies:
The Code is written in Python 3.8.5.

### Used libraries:
opencv-python==4.5.1.48
matplotlib==3.4.1
numpy==1.20.2
pandas==1.2.4
scipy==1.6.2
seaborn==0.11.1


