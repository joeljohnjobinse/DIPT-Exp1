# Experiment 1 – OpenCV Image Processing Basics

## Overview
This experiment demonstrates the basic image processing operations using **OpenCV** and **Matplotlib** in Python. It covers image loading, drawing shapes, color space conversions, pixel manipulation, resizing, cropping, flipping, and saving images.

## Objectives
- Load and display an image.
- Draw basic shapes and add text.
- Perform color space conversions.
- Access and modify pixel values.
- Resize and crop images.
- Flip images horizontally and vertically.
- Save the processed image.

## Technologies Used
- Python 3
- OpenCV (`cv2`)
- Matplotlib

## Required Libraries

```bash
pip install opencv-python matplotlib
```

## Files
```
├── Ex-1.ipynb                 # Jupyter Notebook
├── Joel_John_Jobinse_Photo.jpg # Input image
└── README.md
```

## Experiment Steps

### Step 1: Image Loading
- Read an image from the local directory.
- Display the image using Matplotlib.

### Step 2: Drawing Operations
- Draw a diagonal line.
- Draw a circle.
- Draw a rectangle.
- Add the text **"OpenCV Drawing"**.

### Step 3: Color Space Conversion
- RGB → HSV
- RGB → Grayscale
- RGB → YCrCb
- HSV → RGB

### Step 4: Pixel Manipulation
- Access pixel values.
- Modify a region of the image by changing its color.

### Step 5: Image Resizing
- Resize the image to half its original dimensions.

### Step 6: Region of Interest (ROI)
- Crop a selected portion of the image.
- Display the cropped region.

### Step 7: Image Flipping
- Horizontal flip.
- Vertical flip.

### Step 8: Save Image
- Save the final processed image to the local directory.

## Learning Outcomes
After completing this experiment, you will be able to:
- Read and display images using OpenCV.
- Perform basic drawing operations.
- Convert images between different color spaces.
- Manipulate pixels and regions of an image.
- Resize, crop, and flip images.
- Save processed images for future use.
