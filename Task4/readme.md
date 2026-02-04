DIP Task 4 - Working / Actions Performed

This notebook demonstrates advanced image enhancement techniques using Python and OpenCV. The actions performed are:

Upload Image: Upload an image from the local system to Google Colab.

Read Image: Load the uploaded image using OpenCV and convert it to RGB for display.

Display Original Image: Show the original image before processing.

Histogram Equalization (Built-in, Color Image):

Convert the image to YCrCb color space.

Equalize only the Y (luminance) channel using OpenCV’s built-in function.

Convert back to RGB and display the result.

Histogram Equalization (Manual, Grayscale):

Convert the image to grayscale.

Compute the histogram and cumulative distribution function (CDF).

Map pixel values manually to enhance contrast.

Histogram Comparison: Display original and equalized histograms to visualize changes.

Contrast Stretching: Stretch the intensity range of the grayscale image to improve visibility of details.

Log Transformation: Apply logarithmic transformation to enhance dark regions in the grayscale image.

Gamma Transformation: Apply gamma correction to adjust brightness non-linearly.

Visualization: Display all processed images (log transform, gamma transform, contrast stretching) side by side for comparison.

Output:

Enhanced images with improved contrast and brightness.

Histograms showing the effect of manual equalization.

Visual comparison of multiple enhancement techniques.
