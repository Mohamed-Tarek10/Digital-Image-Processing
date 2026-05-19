# 🖼️ Digital Image Processing

A structured collection of Python notebooks covering the full spectrum of digital image processing — from fundamental pixel-level operations to machine learning–based image classification — built with **OpenCV** and **Pillow**.

---

## 📁 Repository Structure

```
Digital-Image-Processing/
│
├── 📂 Digital Images/
│   ├── Image representation (grayscale, RGB, HSV color spaces)
│   ├── Reading, displaying, and saving images with OpenCV & Pillow
│   ├── Histograms and pixel intensity distributions
│   └── Color channel decomposition and analysis
│
├── 📂 Pixel Transformations/
│   ├── Point operations: brightness, contrast, gamma correction
│   ├── Thresholding (global, Otsu's, adaptive)
│   ├── Histogram equalization and CLAHE
│   └── Intensity mapping and LUT-based transforms
│
├── 📂 Manipulating Images/
│   ├── Geometric transforms: rotation, scaling, flipping, translation
│   ├── Spatial filtering: blurring (Gaussian, median, bilateral)
│   ├── Edge detection: Canny, Sobel, Laplacian
│   ├── Morphological operations: erosion, dilation, opening, closing
│   └── Image arithmetic: addition, blending, bitwise operations
│
└── 📂 Machine Learning Image Classification/
    ├── Feature extraction (HOG, pixel flattening)
    ├── Classical ML classifiers: SVM, KNN, Decision Trees
    ├── Evaluation: accuracy, confusion matrix, classification report
    └── Comparison of model performance on image datasets
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| OpenCV (`cv2`) | Image I/O, filtering, geometric ops, edge detection |
| Pillow (`PIL`) | Image manipulation, format conversion |
| NumPy | Array operations and pixel math |
| Matplotlib | Visualization and comparison plots |
| scikit-learn | ML classifiers and evaluation metrics |
| Jupyter Notebook | Interactive, annotated experiments |

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/Mohamed-Tarek10/Digital-Image-Processing.git
cd Digital-Image-Processing

# Install dependencies
pip install opencv-python pillow numpy matplotlib scikit-learn jupyter

# Launch notebooks
jupyter notebook
```

Open any folder and run the `.ipynb` notebooks in order — each is self-contained with explanations and visual outputs.

---

## 📌 Key Concepts Covered

- **Color spaces** — RGB, Grayscale, HSV and when to use each
- **Pixel-level ops** — intensity scaling, thresholding, histogram equalization
- **Spatial filters** — smoothing noise vs. sharpening edges
- **Edge & contour detection** — Canny pipeline, Sobel gradients
- **Morphological processing** — structuring elements, opening/closing for noise removal
- **Image classification** — feature engineering → ML model → evaluation loop

---

## 🎯 Purpose

This repo was built as a hands-on companion to coursework in Digital Image Processing and Computer Vision, demonstrating practical implementations beyond theory — from raw pixel arithmetic to deployable ML classifiers.

---

## 👤 Author

**Mohamed Tarek**  
B.Sc. Communications & Electronics Engineering — Mansoura University  
[GitHub](http://www.github.com/Mohamed-Tarek10) · [LinkedIn](http://www.linkedin.com/in/1mohamed-tarek)

---
