# 🏆 Face & Color Recognition using Huskylens & OpenCV  


## 🚀 **Project : Face Recognition using Huskylens (Arduino)**  
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


## 🛠️ **Troubleshooting**
### 🔹 **Huskylens Issues**
- Ensure Huskylens is properly wired and trained for recognition.  
- Verify that Huskylens is in the correct **Face Recognition Mode**.  


