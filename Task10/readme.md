DIP Task 10 - Working / Actions Performed

This notebook demonstrates JPEG-like image compression and Huffman coding for color images using Python and OpenCV. The actions performed are:

Upload Image: Upload a color image (JPEG/PNG) from the local system to Google Colab.

Read Image: Load the image as float32 for precise computations.

Block-wise DCT Compression (JPEG-like):

Divide each image channel into 8×8 blocks.

Apply Discrete Cosine Transform (DCT) to each block.

Quantize the DCT coefficients using a scaled JPEG quantization matrix.

De-quantize and apply inverse DCT (IDCT) to reconstruct the image.

Merge all three channels to get the reconstructed color image.

Huffman Coding (First Channel Demonstration):

Build a Huffman tree based on the frequency of quantized DCT coefficients.

Generate Huffman codes for each symbol.

Encode the first channel and calculate compressed bits.

Compute Metrics:

Compression Ratio (CR): Original bits ÷ Compressed bits.

MSE (Mean Squared Error): Measures difference between original and reconstructed image.

PSNR (Peak Signal-to-Noise Ratio): Quantifies reconstruction quality.

Rate Distortion (RD): Compressed bits ÷ MSE.

Difference Image: Create an amplified difference image to visualize compression artifacts.

Visualization: Display images side by side:

Original Image

Compressed Image

Amplified Difference Image

Output:

Reconstructed image showing visible JPEG-like compression artifacts.

Metrics including CR, MSE, PSNR, and RD to evaluate compression performance.

Difference image to highlight details lost during compression.
