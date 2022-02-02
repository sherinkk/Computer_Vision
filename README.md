# Computer_Vision

Assignment 1:

Q1: Take an image. a. Convert that into gray scale and that gray scale into binary using builtin functions and display all three in single window. b. Find the minimum and maximum i. in the color image (for green, red and blue channel) ii. in the gray scale image iii. in the binary image

Q2: Write the python program which takes two polynomial as input and output the product of those two polynomials using convolution in spatial domain (in O(n^2))

Assignment 2:

Take an image of the wall of your house and apply a sobel filter and count the number of edge pixels in the edge map. Do the same operation for the image of a tree ( capture your own image of the tree ) and report your observation on the two images.
Each of the images considered in the first problem apply Gaussian filters of size 77, 99 and 11*11. Repeat the problem 1 and report your observation

Assignment 3:

Capture Image of chess board(in Black & white) . The captured imageneeds to be converted to gray scale and then to black and white. Write a python script to find all the corner points in the binary chess board image, anddisplay integer coordinates at each corner, superimposing the coordinates with the binary image. (0,0) needs to be displayed at topmost and left most corner, and (8,8) is to be displayed at the lastcorner

Assignment 4:

Design and implement the scheme to find the disparity map from the stereo images. Consider the given images for the test case. You are allowed to use inbuilt functions.

Assignment 5:

Camera calibration using builtin function. Hint:Chessboard can be used for imaging purpose

Assignment 6:

Implement the watershed algorithm in openCV

Assignment 7:

Problem Description:

All the images attached along with this show cells identifiable by their well-stained nuclei. The nuclei are stained either blue or brown. The diagnosis report is defined as follows:
percentage positivity = percentage of Total nuclei that are brown in color / Total nuclei in the picture (blue & brown inclusive) Write a program to find the percentage of positivity in the image given below and classify into grade the level of cancer, using the thresholding scheme followed in the convention method, which is detailed below.

Currently, we see the image in the microscope, count and calculate the %, manually. This is not reproducible always and is subjective. Idea is to make it objective. The gold standard is to take prints and manually count on the images and many studies show that this is objective. To save on paper and time, we want the software to do the job. Brown nuclei indicate that they express the immune marker called Ki67 and the higher the percentage positivity, the more aggressive it is considered to be. In many cases, a cut-off is used to grade cancer. For example <15% is considered low grade and >15% as high grade. Treatment and follow-up actions differ in these 2 situations. Hence, the real problem is with borderline percentages (between 20 & 30% on manual counts). We expect the software to give more accurate and reproducible results. Here the software must do 2 things

Identify percentage positivity (similar to that described above)
Classify the intensity of staining as low and high grade.


Assignment 8:

Face recognition using SIFT features and the demo should be shown on students' faces.

