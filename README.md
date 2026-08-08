# Exp 4 - Geometric Transformations Using OpenCV

---

## Aim

To write a Python program using OpenCV to perform various geometric transformations on an image.

The program performs the following operations:

- Image Translation  
- Image Scaling (Resizing)  
- Image Shearing  
- Image Reflection (Flipping)  
- Image Rotation  

---

##  Software Used

- Anaconda – Python 3.7  
- Jupyter Notebook / VS Code  
- OpenCV (`cv2`)  
- NumPy  
- Matplotlib  

---

##  Algorithm

### Step 1:
Import the required libraries: OpenCV, NumPy, and Matplotlib.

### Step 2:
Read the input image in color mode.

### Step 3: Image Translation
- Create a translation matrix to shift the image  
- Move the image 50 pixels to the right and 80 pixels down  
- Apply transformation using `cv2.warpAffine()`  
- Display original and translated images  

### Step 4: Image Scaling
- Resize the image to 0.5× (downscale)  
- Resize the image to 2× (upscale)  
- Use `cv2.resize()`  
- Display original, downscaled, and upscaled images  

### Step 5: Image Shearing
- Create transformation matrices for:
  - Horizontal shearing  
  - Vertical shearing  
- Apply transformations using `cv2.warpAffine()`  
- Display original and sheared images  

### Step 6: Image Reflection
- Perform flipping using `cv2.flip()`:
  - Horizontal reflection  
  - Vertical reflection  
  - Both axes  
- Display all reflected images  

### Step 7: Image Rotation
- Create rotation matrices for:
  - 45° rotation  
  - 90° rotation  
- Use `cv2.getRotationMatrix2D()` and `cv2.warpAffine()`  
- Display original and rotated images  

---

##  Program

### Developed By: SABEESHWARAN. P

### Register No: 212225230234

---

##  Output

### Image Translation
- Original image is displayed  
- Translated image (shifted right and down) is displayed  
<img width="915" height="543" alt="Screenshot 2026-08-09 001723" src="https://github.com/user-attachments/assets/d7f40dfa-53ce-4c99-ace8-9f00c02391ab" />




### Image Scaling
- Original image is displayed  
- Downscaled image (0.5×) is displayed  
- Upscaled image (2×) is displayed  


<img width="1387" height="542" alt="Screenshot 2026-08-09 001732" src="https://github.com/user-attachments/assets/2fea7251-8bfc-4063-a8e1-15a67659b776" />


### Image Shearing
- Original image is displayed  
- Horizontally sheared image is displayed  
- Vertically sheared image is displayed  

<img width="1362" height="532" alt="Screenshot 2026-08-09 001740" src="https://github.com/user-attachments/assets/fb6924b9-ea32-4b10-81c9-c6148f5b6e99" />



### Image Reflection
- Original image is displayed  
- Horizontally flipped image is displayed  
- Vertically flipped image is displayed  
- Both-axis flipped image is displayed  

<img width="1371" height="397" alt="Screenshot 2026-08-09 001749" src="https://github.com/user-attachments/assets/8c7105da-5255-466a-ba05-eb6fead7b720" />



### Image Rotation
- Original image is displayed  
- 45° rotated image is displayed  
- 90° rotated image is displayed  
<img width="1382" height="548" alt="Screenshot 2026-08-09 001756" src="https://github.com/user-attachments/assets/4fd1af4a-2b37-42d5-a648-c85b9ce44815" />



---

##  Result

Thus, various geometric transformations such as translation, scaling, shearing, reflection, and rotation are successfully performed using OpenCV. These transformations demonstrate how images can be spatially manipulated for different computer vision applications.
