# Image_processor.ipynb

## <span style="color:blue"> Description </span>

This code uses OpenCV (cv2) and Matplotlib to process and display images:

1. Grayscale Conversion: The image is read in grayscale using cv2.imread() with the cv2.IMREAD_GRAYSCALE flag, which simplifies the image to a single intensity channel.

2. Image Resizing: The image is resized to 100x100 pixels using cv2.resize(), adjusting the image dimensions.

3. Gaussian Blurring: A Gaussian blur is applied using cv2.GaussianBlur(), which smooths the image by reducing noise and detail.
git add
4. Image Display: Using Matplotlib, the processed images (grayscale, resized, and blurred) are displayed side by side in a single row (plt.subplot()), with appropriate titles, using plt.imshow() and plt.show().

**************************************************
## <span style="color:green"> Image Example </span>
![Sample Image](images/sample(for README.md).jpg)
**************************************************

## <span style="color:red"> How to Run </span>
To run the code:

1. Install dependencies:
"pip install opencv-python matplotlib"

2. Save the code in a Python file (e.g., image_processing.py).

3. Place your image (sample.jpg) in the same directory or provide the full path.

4. Run the Python file:

This will process the image and display the results.


