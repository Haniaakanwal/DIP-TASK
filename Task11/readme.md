DIP Task 11 - Working / Actions Performed

This notebook demonstrates morphological operations, hole filling, noise removal, and shape detection using Python and OpenCV. The actions performed are:

Upload Image: Upload a grayscale or binary image from the local system to Google Colab.

Read and Convert Image: Load the image as grayscale and convert it to a binary image using thresholding.

Erosion & Dilation:

Erosion: Shrinks bright regions (foreground), useful to remove small noise.

Dilation: Expands bright regions, useful to recover lost parts after erosion.

Opening & Closing:

Opening: Erosion followed by dilation to remove small noise.

Closing: Dilation followed by erosion to fill small holes in foreground objects.

Boundary Extraction: Extract boundaries of objects by subtracting the eroded image from the original binary image.

Hole Filling: Fill holes in binary objects using iterative morphological reconstruction.

Noise Removal: Remove small isolated noise using opening operation.

Shape Detection:

Detect contours of objects.

Approximate contours and classify shapes as Triangle, Rectangle, Circle, or Unknown.

Draw contours and label shapes on the image.

Visualization: Display all intermediate and final results including:

Binary image

Erosion & Dilation

Opening & Closing

Boundary extraction

Hole-filled image

Noise-removed image

Shape detection with labels

Output:

Morphologically processed images showing noise removal, hole filling, and boundary extraction.

Shape detection image with contours and labels for easy identification.
