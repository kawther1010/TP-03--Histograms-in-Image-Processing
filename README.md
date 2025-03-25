# 📊 TP 03: Histograms in Image Processing  BY Dr Guessoum

## 🎯 Objectives  
- Display the brightness and contrast of an image.  
- Compute and display histograms manually for grayscale and color images (RGB channels).  
- Apply different brightness and contrast enhancement techniques.  

## 📝 Steps  

### 🔹 1. Grayscale Image Processing  
Start by loading a **grayscale** image (**`rose_1024.tif`**).  

#### 📌 1.1 Load the Image  
- Load the specified image and convert it to grayscale.  

#### 📌 1.2 Compute Brightness  
- Calculate the **brightness** using the formula provided in class.  

#### 📌 1.3 Compute Contrast  
- Evaluate the **contrast** using the formula provided in class.  

#### 📌 1.4 Compute the Histogram  
- Initialize an array of zeros for **256 grayscale levels**.  
- Iterate through each pixel and update the corresponding intensity value in the histogram.  

#### 📌 1.5 Display Results  
- Show the **calculated brightness and contrast**.  
- Plot and display the **histogram of pixel intensities**.  

---

### 🔹 2. Color Image Processing  
Start by loading a **color** image.  

#### 📌 2.1 Load the Image  
- Load any available color image.  

#### 📌 2.2 Split Color Channels  
- Split the image into **Blue, Green, and Red (BGR)** channels using:  
  ```python
  b, g, r = cv2.split(image)
