# Lab 04
## Title : Fundamentals of digital image and basic image operations in Python

---

## Objectives:
1. Load and display digital images.
2. Understand the digital image representation.
3. Color to grayscale and binary image translation.
4. Image transformation (Resize, Rotate. Flip)
5. Crop the ROI (Region of interest) in an image.

---

## Background Theory:
* Digital image representaion (pixels, resolution)
* Color Models (RGB, Grayscale & Binary)
* Image File Formats
* Basic Image Transformation
* Introduction to OpenCV

---

## Procedure 
#### Step 1: Import Required Libraries
We had imported the necessary libraries, cv2 for image processing and numpy for array operations.

#### Step 2: Load and Display an Image
We had loaded the image from the file and had displayed it in a window using cv2.imshow().

#### Step 3: Convert Color Image to Grayscale
We had converted the color image to grayscale using cv2.cvtColor() and had displayed the grayscale image.

#### Step 4: Convert Grayscale Image to Binary
We had applied thresholding on the grayscale image to had obtained a binary image and had displayed it.

#### Step 5: Image Transformations
We had resized the image, had rotated it, had flipped it, and had cropped a portion for transformation demonstration.

#### Step 6: Crop ROI (Region of Interest):
we had defined a specific region of interest, had cropped that area from the original image, and had displayed the cropped ROI.
---
## Output
* Original image displayed successfully
* Grayscale and binary images obtained
* Image resized, rotated, and flipped correctly
* Region of interest cropped from the image
---
## Conclusion
In this lab, the fundamentals of digital image processing were explored using Python and OpenCV. Core operations such as loading images, converting color models, performing transformations, and extracting regions of interest (ROI) were successfully implemented. These basic techniques provide a foundation for more advanced image processing and computer vision tasks.