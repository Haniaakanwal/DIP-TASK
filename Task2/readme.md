DIP Task 2 - Working / Actions Performed

This notebook demonstrates object detection and counting in an image using Python and OpenCV. The actions performed are:

Upload Image: Upload an image from the local system to Google Colab.

Read Image: Load the uploaded image using OpenCV.

Convert to Grayscale: Convert the color image to a grayscale image for easier processing.

Otsu’s Thresholding: Apply Otsu’s method to convert the grayscale image into a binary image automatically.

Noise Removal: Use morphological opening to remove small noise and clean the binary image.

Connected Component Labeling (CCL): Label connected components in the binary image to detect separate objects.

Filter Small Components: Ignore objects smaller than a set area threshold to avoid counting noise as objects.

Count Objects: Count the total number of significant objects detected in the image.

Visualize Results:

Show the binary image after thresholding.

Show the cleaned image after noise removal.

Display labeled objects with unique colors for each component.

Output:

Total number of detected objects is printed.

Visual representation of all steps is shown side by side for easy comparison.
