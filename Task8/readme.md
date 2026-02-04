DIP Task 8 - Working / Actions Performed

This notebook demonstrates image degradation and restoration techniques using Python, OpenCV, SciPy, and skimage. The actions performed are:

Upload Image: Upload a grayscale image from the local system to Google Colab.

Read and Resize Image: Load the image using OpenCV and resize it to 256×256 for faster processing.

Display Original Image: Show the original grayscale image before applying noise or blur.

Simulate Noise and Blur:

Gaussian Noise: Add Gaussian noise to the image.

Salt & Pepper Noise: Add salt-and-pepper noise.

Motion Blur: Apply motion blur using a linear kernel.

Noise/Blur Removal (Restoration):

Wiener Filter: Apply Wiener filter to restore images degraded by Gaussian noise and motion blur.

Median Filter: Apply median filter to restore the image corrupted by salt-and-pepper noise.

Compute PSNR: Measure the quality of restored images using Peak Signal-to-Noise Ratio (PSNR).

Higher PSNR indicates better restoration quality.

Visual Comparison: Display original, noisy/blurred, and restored images side by side for all three cases (Gaussian, Salt & Pepper, Motion Blur).

Output:

Restored images showing effective noise and blur removal.

PSNR values to quantify the performance of each restoration technique.

Clear visual comparison of original, degraded, and restored images.
