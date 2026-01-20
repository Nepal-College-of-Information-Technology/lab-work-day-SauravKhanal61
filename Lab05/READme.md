# MMS Lab 5  
## Image Classification Using OpenCV and Pre-trained Deep Learning Model

---

## Title
**Image Classification Using OpenCV and Pre-trained Deep Learning Model**

---

## Objectives
1. To find and use a pre-trained Convolutional Neural Network (CNN) model for gender classification.  
2. To load the pre-trained deep learning model and test images using OpenCV.  
3. To detect the Region of Interest (ROI), specifically the face region, and classify the test image.

---

## Background Theory

### Image Detection and Recognition
Image detection involves locating objects or regions of interest (such as faces) within an image, while image recognition focuses on identifying or classifying those detected objects. In this lab, face detection was performed before classification.

### OpenCV for Image Processing
OpenCV is an open-source computer vision library widely used for image processing tasks such as image loading, resizing, face detection, and visualization. The Python interface of OpenCV allows easy integration with deep learning models.

### Classical Machine Learning vs Deep Learning
Classical machine learning techniques rely on manual feature extraction, whereas deep learning models automatically learn features from raw data. Deep learning models provide higher accuracy for image-based tasks.

### Convolutional Neural Network (CNN)
A Convolutional Neural Network (CNN) is a deep learning architecture specifically designed for image analysis. It uses convolutional layers to extract features such as edges and textures, followed by fully connected layers for classification. Pre-trained CNN models were reused in this lab for gender classification.

---

## Tools and Technologies Used
* Python  
* OpenCV  
* Pre-trained CNN Model  
* NumPy  

---

## Procedure

### Step 1: Import Required Libraries
The required libraries such as OpenCV and NumPy were imported for image processing and numerical operations.

### Step 2: Load the Pre-trained Model
The pre-trained CNN model used for gender classification was loaded.

### Step 3: Read the Input Image
The input image was read using OpenCV for further processing.

### Step 4: Detect Face Region (ROI)
The face region was detected from the image and extracted as the Region of Interest (ROI).

### Step 5: Preprocess the ROI
The extracted face image was resized and preprocessed according to the input requirements of the CNN model.

### Step 6: Classify the Image
The processed ROI was passed to the pre-trained CNN model to classify the gender.

### Step 7: Display the Result
The classification result was displayed along with the detected face region.

---

## Output
* Face region detected successfully  
* Image preprocessed correctly  
* Gender classified using the pre-trained CNN model  
* Classification result displayed on the image  

---

## Conclusion
In this lab, image classification was successfully performed using OpenCV and a pre-trained deep learning model. Face detection was used to extract the region of interest, which was then classified using a CNN. This experiment demonstrates the effectiveness of deep learning-based approaches over traditional machine learning methods and provides a strong foundation for advanced computer vision applications. 

---