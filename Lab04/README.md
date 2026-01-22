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
  <img width="379" height="465" alt="image" src="https://github.com/user-attachments/assets/f73d8349-2964-4ef9-8590-0f83755a89b0" />
 
* Grayscale and binary images obtained
  <img width="260" height="325" alt="image" src="https://github.com/user-attachments/assets/0fe030eb-3d0c-4b5d-8a00-ab77bb4f1c75" />
  <img width="255" height="317" alt="image" src="https://github.com/user-attachments/assets/230da9d7-174d-4421-a399-9dae1c90aca9" />

* Image resized, rotated, and flipped correctly
  <img width="627" height="492" alt="image" src="https://github.com/user-attachments/assets/c4ab77fe-a464-45e0-a876-9e4da9fa10ca" />
  <img width="384" height="495" alt="image" src="https://github.com/user-attachments/assets/52a2ed41-7e06-4226-b02c-efb503c70a9d" />
  <img width="375" height="504" alt="image" src="https://github.com/user-attachments/assets/cab8d95d-d7ce-496b-b79b-e33399be2a88" />



* Region of interest cropped from the image
  <img width="471" height="499" alt="image" src="https://github.com/user-attachments/assets/673ba671-f17e-40ab-b00f-322db16a875e" />


---

## Conclusion
In this lab, the fundamentals of digital image processing were explored using Python and OpenCV. Basic operations such as loading images, converting color models, applying image transformations, and extracting regions of interest were successfully implemented. These techniques form a strong foundation for advanced image processing and computer vision applications.

--- 
