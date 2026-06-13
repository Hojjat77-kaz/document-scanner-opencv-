# Document Scanner with OpenCV

A computer vision project that automatically detects a document in an image and converts it into a scanned, top-down view using contour detection and perspective transformation.

## Features

- Document detection using contours
- Edge detection with Canny
- Polygon approximation with approxPolyDP
- Automatic corner extraction
- Perspective transformation
- Top-down document scanning
- Noise reduction using Gaussian Blur

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib

  ## Processing Pipeline

1. Read input image
2. Convert image to grayscale
3. Apply Gaussian Blur
4. Detect edges using Canny
5. Find contours
6. Locate the document contour
7. Approximate document corners
8. Order corner points
9. Compute perspective transform
10. Warp image to obtain scanned document

## Concepts Practiced

- Image Preprocessing
- Edge Detection
- Contour Analysis
- Polygon Approximation
- Geometric Transformations
- Perspective Correction
- Document Rectification

  ## Example Output

Input:
- Perspective-distorted document image

Output:
- Clean top-down scanned document

  ## Future Improvements

- Adaptive thresholding for scanned effect
- Automatic brightness correction
- Shadow removal
- Mobile image support
- Real-time webcam document scanning
- PDF export

  ## What I Learned

This project helped me understand:

- How contours can be used to detect documents
- How polygon approximation identifies document corners
- How perspective distortion affects images
- How perspective transformation works
- How to build a complete document scanning pipeline
