Digital Image Processing (DIP) - Lab Tasks

This repository contains Digital Image Processing (DIP) lab assignments demonstrating various image processing techniques using Python, OpenCV, NumPy, and related libraries. Each task is implemented in Google Colab notebooks with step-by-step explanations and visualizations.

Table of Contents

Task 1: Image Reading & Visualization
Task 2: Connected Component Labeling
Task 3: Histogram Equalization & Contrast Stretching
Task 4: Color Image Enhancement
Task 5: Image Filtering (Mean, Median, Mode, Gaussian)
Task 8: Noise Addition & Restoration
Task 9: Color Spaces, White Balance & Segmentation
Task 10: JPEG-like DCT Compression & Huffman Coding
Task 11: Morphological Operations
Task 12: Thresholding & Segmentation

Task 1 - Image Reading & Visualization

Objective: Load an image, display, and understand basic image properties.

Actions Performed:
Upload an image and read it using OpenCV.
Display the original image and its grayscale version.
Display image properties: shape, data type, and pixel values.

Output:
Original and grayscale image visualization.
Image details printed in console.

Task 2 - Connected Component Labeling

Objective: Detect and count objects in a binary image.

Actions Performed:
Convert the uploaded image to grayscale.
Apply Otsu’s thresholding to binarize the image.
Remove noise using morphological opening.
Label connected components and count objects above a minimum area.
Display binary image, cleaned image, and labeled components.

Output:
Total number of objects detected.
Visualization of binary image, noise removal, and labeled objects.

Task 3 - Histogram Equalization & Contrast Stretching

Objective: Enhance image contrast using histogram methods.

Actions Performed:
Convert image to grayscale.
Apply built-in histogram equalization.
Implement custom histogram equalization.
Apply contrast stretching.
Display all processed images for comparison.

Output:
Original, histogram-equalized (built-in and custom), and contrast-stretched images.

Task 4 - Color Image Enhancement

Objective: Enhance color images using various methods.

Actions Performed:
Convert image to YCrCb color space and equalize luminance channel.
Perform manual histogram equalization.
Apply contrast stretching.
Apply logarithmic and gamma transformations.
Display all processed images.

Output:
Enhanced images using different color enhancement techniques.
Histograms before and after enhancement.

Task 5 - Image Filtering

Objective: Remove noise from images using different filters.

Actions Performed:
Apply Mean filter, Median filter, Mode filter, and Gaussian filter on noisy grayscale image.
Display all filtered results alongside original.

Output:
Comparison of original and filtered images to evaluate noise removal effectiveness.

Task 8 - Noise Addition & Restoration

Objective: Add different noises and restore the image.

Actions Performed:
Add Gaussian noise, Salt & Pepper noise, and Motion blur to the image.
Apply Wiener filter for Gaussian noise and motion blur.
Apply Median filter for Salt & Pepper noise.
Compute PSNR values for restored images.
Display original, noisy, and restored images.

Output:
Noise-added images and their restored versions.
PSNR metrics to evaluate restoration quality.

Task 9 - Color Spaces, White Balance & Segmentation

Objective: Explore color spaces and perform color-based segmentation.

Actions Performed:
Convert the image to grayscale and split RGB channels.
Convert to HSV, YCbCr, and Lab color spaces.
Apply Gray World White Balance.
Isolate green color using HSV masking.
Perform segmentation using Lab a-channel.
Display all processed images.

Output:
White-balanced image.
Green color isolated image.
Segmented image with Lab a-channel.

Task 10 - JPEG-like DCT Compression & Huffman Coding

Objective: Compress images using DCT and Huffman coding.

Actions Performed:
Divide image into 8×8 blocks and apply DCT.
Quantize coefficients with scaled JPEG matrix and apply IDCT.
Build Huffman coding for first channel and calculate compressed bits.
Compute metrics: Compression Ratio (CR), MSE, PSNR, Rate Distortion (RD).
Display original, compressed, and amplified difference images.

Output:
Compressed image with visible artifacts.
Difference image to highlight compression losses.
Compression metrics printed in console.

Task 11 - Morphological Operations

Objective: Apply morphological operations for shape analysis and noise removal.

Actions Performed:
Convert image to binary and display original.
Apply Erosion, Dilation, Opening, Closing.
Extract boundaries, fill holes, and remove noise.
Detect shapes (Triangle, Rectangle, Circle) using contours.
Display all intermediate and final results.

Output:

Morphologically processed images showing noise removal, hole filling, and boundaries.
Shape detection image with labeled contours.

Task 12 - Thresholding & Segmentation

Objective: Segment images using thresholding and clustering techniques.

Actions Performed:
Convert uploaded color image to grayscale.
Apply Global, Otsu, and Adaptive thresholding.
Perform K-Means segmentation with k=2,3,4.
Apply Mean Shift segmentation.
Display all segmentation results for comparison.

Output:

Thresholded binary images.
K-Means segmented images.
Mean Shift segmented image.
Comparison of all methods.



Open each task notebook in Google Colab:


Upload the required images when prompted.

Run all cells step by step to visualize results.
