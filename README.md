# Computer-Vision-and-Image-Processing

## 📝 Take Home Assignment 2

### This repository contains Python code and results for Assignment 2 of EC7212, focusing on image segmentation techniques.

---

## 📌 Assignment Tasks

### 1. **Otsu’s Thresholding with Gaussian Noise**
- Creates a synthetic grayscale image with:
  - 2 foreground objects
  - 1 background
- Adds Gaussian noise to simulate real-world imperfections.
- Applies Otsu’s algorithm for automatic image segmentation.

### 2. **Region Growing Segmentation**
- Implements a region-growing technique from a given seed point.
- Adds neighboring pixels to the region if their intensities fall within a pre-defined range (e.g., ±20 of seed).
- Useful for segmenting regions with similar characteristics.

---

## 💻 Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib

---

## 🖼️ Sample Synthetic Image

- The image is generated programmatically using rectangles and background pixel values.
- Pixel intensities used:
  - Background: 0
  - Object 1: 85
  - Object 2: 170

---

## ▶️ How to Run

### Requirements:
- Libraries:
  ```bash
  pip install opencv-python numpy matplotlib
