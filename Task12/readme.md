DIP Task 12 - Working / Actions Performed

This notebook demonstrates image thresholding and segmentation techniques using Python and OpenCV. The actions performed are:

Upload Image: Upload a color image (PNG, JPG, etc.) from the local system to Google Colab.

Read and Convert Image: Load the color image and convert it to grayscale for thresholding.

Display Original Image: Show the original color image.

Thresholding Techniques:

Global Thresholding: Apply a fixed threshold to separate foreground and background.

Otsu Thresholding: Automatically compute optimal threshold to separate foreground and background.

Adaptive Thresholding: Compute local thresholds for different regions using Gaussian weighting.

Display all thresholded images for comparison.

K-Means Segmentation:

Implement K-Means clustering to segment the image into k clusters.

Apply K-Means for k = 2, 3, 4 and display results.

Mean Shift Segmentation:

Apply Mean Shift Filtering for color-based image segmentation.

Smooths color regions while preserving edges.

Comparison of Segmentation Methods:

Display all segmentation results side by side:

Global Threshold, Otsu Threshold, Adaptive Threshold

K-Means (k=2,3,4)

Mean Shift Segmentation

Compare the effectiveness of different thresholding and clustering techniques visually.

Output:

Thresholded images showing binary segmentation.

Color-segmented images using K-Means and Mean Shift.

Visual comparison of multiple segmentation techniques on the same image.
