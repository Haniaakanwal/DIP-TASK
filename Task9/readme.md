DIP Task 9 - Working / Actions Performed

This notebook demonstrates color space transformations, white balancing, color isolation, and image segmentation using Python and OpenCV. The actions performed are:

Upload Image: Upload an image from the local system to Google Colab.

Read and Resize Image: Load the image using OpenCV and resize it to 256×256 for faster processing.

Convert to Grayscale: Convert the original image to grayscale and display side by side with the original image.

Split RGB Channels: Separate the image into Red, Green, and Blue channels and display each channel.

Convert to Other Color Spaces:

Convert the image to HSV, YCbCr, and Lab color spaces.

Display the images in these color spaces for visual comparison.

Gray World White Balance: Apply the gray-world assumption to correct the color balance of the image.

Color Isolation (Green):

Convert image to HSV.

Define a green color range and create a mask.

Isolate green color from the image using the mask.

Image Segmentation (Lab a-channel):

Convert the image to Lab color space.

Threshold the ‘a’ channel (red-green) to create a segmentation mask.

Apply the mask to the original image to extract segmented regions.

Visualization: Display all intermediate and final results for clear understanding:

Original, grayscale, RGB channels, color space conversions, white-balanced image, color-isolated image, and segmented image.

Output:

Grayscale and RGB channel visualization.

Images in HSV, YCbCr, and Lab color spaces.

White-balanced image.

Green color isolated image.

Segmented image using Lab a-channel.
