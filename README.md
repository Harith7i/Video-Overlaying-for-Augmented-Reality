#  Video Overlaying for Augmented Reality
The program first captures the live video feed and processes each frame using the ORB (Oriented FAST and Rotated BRIEF), a feature detection and description algorithm, to detect keypoints and descriptors to detect features in the input image. The algorithm is designed to find points of interest in an image, such as corners, edges, and blobs. These keypoints and descriptors are then used to create a mask that is overlaid onto the input image.

Once the mask has been created, a video can be overlaid onto the image using the mask. The program allows users to customize the video that is overlaid onto the image by editing the mp4 file. Users can also adjust the detection parameters in the overlay.py file, such as the minimum number of matches required for a detection, to fine-tune the application's performance.
<p align="center">
![](https://github.com/Harith7i/Video-Overlaying-for-Augmented-Reality/blob/main/demo.gif)
</p>
hello
