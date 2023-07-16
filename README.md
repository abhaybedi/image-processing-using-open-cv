# image-processing-using-open-cv
implementation of all popular open cv functions and more in one file with relevant explanation

Basic Image Processing using cv2 functions:

1.Converting Image to Grayscale

2.Cropping Image

3.Thresholding the Image

4.Bluring the Image (using inbuilt blurring and gaussian blurring)

5.Rotating and Scaling of the image

6.Canny edge detection algorithm with and without gaussian blur

7.Hough Line transformation- used for detection of straight lines, first an edge detection pre-processing is desirable (in our case Canny):

a. The Standard Hough Transform
It gives you as result a vector of couples (θ,rθ)
In OpenCV it is implemented with the function HoughLines()

b. The Probabilistic Hough Line Transform (more efficient)
It gives as output the extremes of the detected lines (x0,y0,x1,y1)
In OpenCV it is implemented with the function HoughLinesP() 



Basic Image Processing using Scikit Image:

1.Printing the image in the form of matrix

2.Printing the shape of the matrix

3.Printing the number of chanels in an image

4.The number of pixels

5.Printing the red Channel of the Image

6.Printing the Green Channel of the Image

7.Printing the Blue Channel of the Image

8.Printing the Grayscale of the Image
9.Flipping the Image
10.Histrograms of different colour Chanels
11.Image Conversion (jpg to png and stuff)


