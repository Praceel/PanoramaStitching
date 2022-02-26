# PanoramaStitching
A simple and easy to implement Python Code on Panorama Stitching using OpenCV, Numpy, and Matplotlib.
The Code has been conducted as part of the University Assignment regarding introduction to Image Processing.
It could be interesting to understand how the Panorama stitching works. It gives a basic idea and ofcourse one could modify it as per their necessities.

# Project Fundamentals
The code is implemented with a Feature based Image stitching Algorithm, where Shift Invariant Fatures Transform (SIFT) is used to extract the features and keypoints. For the overlapping input images, all matched keypoints are detected using Euclidean distance (kNN match) and OpenCV provides method for these. Similarly, Homography computation and Warp Persepctive for seamless Image Blending.

The Final Output is the Stitched Image i.e., Panorama, and based on the number of Input Images provided, the algorithm detects key points and construct the final image.


The work is inspired from various sources
https://towardsdatascience.com/image-panorama-stitching-with-opencv-2402bde6b46c
https://medium.com/@navekshasood/image-stitching-to-create-a-panorama-5e030ecc8f7
https://stackoverflow.com/questions/45295986/panoramic-image-stitching-using-opencv-python


# Deliverables
Input Images (4 in this case)
![IMG_01](https://user-images.githubusercontent.com/66719592/155841999-6047c685-e1ca-4c4e-a105-2cb6cc4ad8ec.JPG)
![IMG_02](https://user-images.githubusercontent.com/66719592/155841993-e09893d2-c9ec-470f-83f5-503900e023a8.JPG)
![IMG_03](https://user-images.githubusercontent.com/66719592/155841996-c6ebd6e9-bf35-41a3-a692-d9a32f6af642.JPG)
![IMG_04](https://user-images.githubusercontent.com/66719592/155841997-39bd4616-04dd-44c2-bc7f-273787481a59.JPG)


Matched Keypoints
![Matched_points](https://user-images.githubusercontent.com/66719592/155842014-d954d355-7626-4c0b-b816-6237c03db872.jpg)

Output Panoramic Image
![Panorama_image](https://user-images.githubusercontent.com/66719592/155842026-5008200f-658b-4246-ba0c-8129ee47433b.jpg)
