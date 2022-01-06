# Sowmya-IP-lab
# 1.Develop a program to perform linear transformation on the image.

Description: Here in the codes, we have used the getRotationMatrix function to define the parameter required in the warpAffine function to tell the function to make a matrix that can give a required rotation angle.

The warpAffine() function applies an affine transformation to the image. After applying affine transformation, all the parallel lines in the original image will remain parallel in the output image as well.

Code:

import cv2

image = cv2.imread('girl.jpg')

height, width = image.shape[:2]

center = (width/2, height/2)

rotate_matrix = cv2.getRotationMatrix2D(center=center, angle=60, scale=1)

rotated_image = cv2.warpAffine(src=image, M=rotate_matrix, dsize=(width, height))

cv2.imshow('Original image', image)

cv2.imshow('Rotated image', rotated_image)

cv2.waitKey(0)
![image](https://user-images.githubusercontent.com/95745982/148336633-3ecc575b-42cf-46b7-8561-6ed81d64c296.png)


![image](https://user-images.githubusercontent.com/95745982/148336665-561a9d79-35ed-466b-8a70-9d67a882f6ad.png)
