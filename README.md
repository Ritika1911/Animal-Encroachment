# Animal-Encroachment Detection in Farms using OpenCV and Tensorflow

System Architecture
<img width="537" alt="System Architecture" src="https://user-images.githubusercontent.com/72461423/226546096-2d8804a8-dcc9-4f9d-8d42-70c8da61129b.PNG">

Preprocessing : Image Sharpening using (2D-Convolution Kernels), High pass filters, horiizontal and vertical flip augmentation performed.
Dual channel prior based method implemented to obtain region of interest from images captured at night.

Methodology :
Thresholding & Sobel Edge detection
Erosion and dilation
Finding contours to identify movement
Invoking object detection module if contour area is greater than threshold.
