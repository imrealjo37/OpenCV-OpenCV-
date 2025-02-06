# 🏆 Face & Color Recognition using Huskylens & OpenCV  

## 📌 Overview  
This repository contains two implementations of **AI-based recognition**:  
1. **Huskylens with Arduino**  
   - **Face Recognition** – Detects and identifies faces using Huskylens AI camera.  
2. **OpenCV with Python**  
   - **Color Recognition** – Detects and labels colors in uploaded images.  

---

## 🚀 **Project 1: Face Recognition using Huskylens (Arduino)**  
### 📌 **Requirements**  
- 🛠️ **Hardware**:  
  - Huskylens AI Camera  
  - Arduino Uno (or compatible board)  
  - Jumper wires (for I2C connection)  
- 💾 **Software**:  
  - Arduino IDE  
  - Huskylens Library (install via Library Manager)  

### 🔧 **Wiring Huskylens to Arduino (I2C)**  
| Huskylens | Arduino |
|-----------|---------|
| VCC       | 5V      |
| GND       | GND     |
| SDA       | 10      |
| SCL       | 11      |

### 🎯 **How Face Recognition Works?**
1. Huskylens **detects a face** and assigns it a unique **Face ID**.  
2. The **Face ID** is stored and used for recognition.  
3. When the same face is detected, it retrieves the stored ID.  
4. You can **assign custom names** to specific Face IDs for easier identification.  

### 🖼️ **Huskylens Output**  
![image](https://github.com/user-attachments/assets/506341d2-3908-4dae-8082-ee41233338c0)

---

## 🎯 **Project 2: Color Recognition using OpenCV (Python)**
### 📌 **Requirements**
- 💻 **Software**:
  - Python 3.x  
  - OpenCV  
  - NumPy  
  - Google Colab or Jupyter Notebook (if running online)  

### 🎯 **How Color Recognition Works?**
1. Loads an **image** and converts it to **HSV color space**.  
2. Predefined color ranges are used to detect specific colors (**Red, Green, Blue, Yellow**).  
3. The script highlights detected colors and labels them.  
4. Displays the processed image with **color names**.  

### 🖼️ **OpenCV Color Recognition Output**  
![image](https://github.com/user-attachments/assets/27f6346f-10b2-4b8c-9a25-a5d342885794)
 

---

## 🛠️ **Troubleshooting**
### 🔹 **Huskylens Issues**
- Ensure Huskylens is properly wired and trained for recognition.  
- Verify that Huskylens is in the correct **Face Recognition Mode**.  

### 🔹 **OpenCV Color Recognition Issues**
- Ensure the image is not too dark or blurry.  
- Adjust the **HSV color range** to improve detection accuracy.  

