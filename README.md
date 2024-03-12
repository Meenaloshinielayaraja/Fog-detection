# Fog-detection

Problem Statement:
Foggy weather is always hazardous for people. It becomes difficult to drive due to lack of visibility which leads to accidents. Drivers can’t make out twists and turns and incoming vehicles ahead usually. 

Objective:
To eradicate the issue of visibility in foggy conditions by making advanced analysis of the road and vehicles ahead.

Existing System:
There are no facilities/advancements in vehicles that could detect roads and elements present on roads during foggy conditions. This usually causes chaos as drivers can’t see what’s ahead of them and what awaits them. This usually causes delays and obviously accidents.  

Methodology:
The Sobel edge detector performs a 2-D spatial gradient measurement on an image and so emphasizes regions of high spatial frequency that correspond to edges. Typically it is used to find the approximate absolute gradient magnitude at each point in an input grayscale image.
The operator uses two 3×3 kernels which are convolved with the original image to calculate approximations of the derivatives – one for horizontal changes, and one for vertical.
Sobel Edge Detector along with Canny edge detection could be used to detect what’s ahead of a vehicle. This could be of a lot of use as it detects the edges of cars in foggy conditions. 
Sobel Edge Detector detects the environment while the Canny Edge Detector detects the borders of the vehicles ahead.
The edges of the image are binarized using edge binarization. This is employed for the comparison of the intensity values of pixels of foreground and background elements of an image. 
Vanishing point detection is also being used which helps in image rectification, camera calibration and 3D scene reconstruction.
The various images of road and sky are segmented into a single image to get the result image.

