# image-processing-welding-X-ray-learning

# X-ray Image Processing

This repository contains Python code for basic X-ray image processing.

## Description

This code provides various image processing techniques for X-ray images using Python libraries such as NumPy, Pandas, Matplotlib, SciPy, and ImageIO. It includes the following techniques:

### Edge Detection
- Laplace Gaussian: Implementing the Laplace Gaussian operation on an X-ray image using SciPy's `gaussian_laplace()`.
- Gaussian Gradient Magnitude: Applying Gaussian filter on the image in both the x-axis and y-axis, then calculating the magnitude using SciPy's `gaussian_gradient_magnitude()`.
- Sobel Filter: Implementation using SciPy's `sobel()` function to apply the Sobel filter on the x-axis and y-axis separately.

### Canny Filter
- Fourier Gaussian Filter: Applying the Fourier Gaussian filter on the original image for noise reduction.
- Calculating Intensity Gradient: Using the Prewitt function from SciPy's ndimage to calculate the gradient magnitude.
- Non-maximum Suppression & Hysteresis Thresholding: Techniques to detect edges.

### Feature Extraction
- Extracting features from images using masking techniques.

### Contributing
Contributions are welcome. For major changes, please open an issue first to discuss what you would like to change.
