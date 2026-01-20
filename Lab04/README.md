# Lab 04  
## Title: Fundamentals of Digital Image and Basic Image Operations in Python

---

## Objectives
1. To load and display digital images.  
2. To understand digital image representation.  
3. To convert color images to grayscale and binary images.  
4. To perform image transformations (resize, rotate, flip).  
5. To crop the Region of Interest (ROI) from an image.

---

## Background Theory
* Digital image representation (pixels, resolution)  
* Color models (RGB, Grayscale, and Binary)  
* Image file formats  
* Basic image transformations  
* Introduction to OpenCV  

---

## Procedure

#### Step 1: Import Required Libraries
The necessary libraries were imported, including `cv2` for image processing and `numpy` for array operations.

#### Step 2: Load and Display an Image
The image was loaded from a file and displayed in a window using `cv2.imshow()`.

#### Step 3: Convert Color Image to Grayscale
The color image was converted to grayscale using `cv2.cvtColor()`, and the grayscale image was displayed.

#### Step 4: Convert Grayscale Image to Binary
Thresholding was applied to the grayscale image to obtain a binary image, which was then displayed.

#### Step 5: Image Transformations
The image was resized, rotated, flipped, and partially cropped to demonstrate different image transformation techniques.

#### Step 6: Crop ROI (Region of Interest)
A specific region of interest was defined, cropped from the original image, and displayed.

---

## Output
* Original image displayed successfully  
* Grayscale and binary images obtained  
* Image resized, rotated, and flipped correctly  
* Region of interest cropped from the image  

---

## Conclusion
In this lab, the fundamentals of digital image processing were explored using Python and OpenCV. Basic operations such as loading images, converting color models, applying image transformations, and extracting regions of interest were successfully implemented. These techniques form a strong foundation for advanced image processing and computer vision applications.

---
