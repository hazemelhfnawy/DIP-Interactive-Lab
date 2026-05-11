# ⚙️ DIP Interactive Lab
**Precision Image Processing & Computer Vision Environment**

A robust, object-oriented desktop application built with Python. Designed for rigorous academic and professional use, this studio provides an interactive GUI to apply, tweak, and visualize advanced digital image processing (DIP) algorithms in real-time.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

---

## 💎 Core Features

* 🔬 **Smart Auto-Enhance:** An algorithmic diagnostic tool that statistically analyzes images for noise, low variance (blur), and exposure issues, automatically applying targeted corrections with a detailed diagnostic report.
* 🌓 **Real-Time Dual View:** Side-by-side comparative analysis of the original and processed images.
* 📊 **Live Statistical Histograms:** Dynamic, real-time pixel distribution histograms rendered via Matplotlib to monitor contrast and illumination shifts.
* 🎛️ **Academic-Grade Filtering:** * **Low-Pass:** Mean, Median, and Gaussian Blurring for noise reduction.
  * **High-Pass:** Laplacian, Unsharp Masking, Sobel, and Canny Edge Detection for structural analysis.
* 📐 **Morphological Mathematics:** Erosion, Dilation, Opening, and Closing with customizable structural kernels.
* 🧮 **Safe Arithmetic Operations:** Direct scalar Addition, Subtraction, Multiplication, and Division utilizing OpenCV's native saturation capabilities to prevent byte-overflow artifacts.
* 💡 **Point Operations:** Logarithmic transformations, Histogram Equalization, and interactive Gamma correction.

## 🛠️ Tech Stack

* **CustomTkinter:** For a sleek, modern, and fully responsive Dark Mode interface.
* **OpenCV (`cv2`):** Driving the core mathematical operations and filtering logic.
* **Matplotlib:** Handling the backend rendering of dynamic UI histograms.
* **NumPy:** For high-performance matrix manipulation and look-up tables (LUT).
* **Pillow (PIL):** Bridging computer vision arrays with GUI rendering.

## 🚀 Quick Start Guide

**1. Clone the repository:**
```bash
git clone [https://github.com/your-username/DIP-Interactive-Lab.git](https://github.com/hazemelhfnawy/DIP-Interactive-Lab.git)
cd DIP-Interactive-Lab
```
**2. Install dependencies:**
Make sure you have Python 3.x installed, then run:
```bash
pip install customtkinter opencv-python numpy matplotlib Pillow
```
3. Launch the studio:

```bash
python main.py
```
📸 Interface Preview
<img width="1920" height="1030" alt="DIP Interactive Lab" src="https://github.com/user-attachments/assets/7913c890-0377-4a41-b4d6-b56cd565783f" />

👨‍💻 About The Developer
Hazem Mohamed Hafez Elhefnawy Computer Engineering | Menoufia National University (Class of 2028) Developed as a comprehensive showcase of integrating Object-Oriented Programming (OOP) architectures with complex Computer Vision mathematics and modern GUI principles.

Building the future, one pixel at a time. — Half Engineer. 🔧
