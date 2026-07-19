# 🖼️ AI342 Professional Digital Image Processing System

> An interactive image processing application that restores images, extracts shape features, and classifies objects into different categories using Principal Component Analysis (PCA).

---

## ✨ Features

- 📷 Image Upload
- 🔊 Noise Generation
  - Gaussian
  - Salt & Pepper
  - Periodic
  - Uniform
- 🧹 Image Restoration
  - Spatial Domain Filtering
  - Frequency Domain Filtering
- 📊 Image Quality Evaluation
  - MSE
  - PSNR
- 🎯 Image Segmentation
- 🧩 Morphological Operations
- 📐 Feature Extraction
  - Area
  - Perimeter
  - Circularity
- 🧠 PCA Visualization
- 🏷️ Shape Classification

---

# 🖥️ Application Interface

<p align="center">
  <img src="Screenshot 2026-07-19 024141.png" width="900" alt="Application Interface">
</p>

> Replace **interface.png** with a screenshot of your application.

---

# 🎥 Demo Video

Or click here:

▶️ **[Project Demo Video](https://youtu.be/Gy7mM6QsP14)**

---

# 📂 Dataset

The project classifies five different object categories.

| Object | Category |
|---------|----------|
| ⚽ Soccer Ball | Circular |
| 🪵 Wooden Stick | Elongated |
| 🔩 Hex Nut | Polygonal |
| ☕ Coffee Stain | Irregular |
| 🛟 Swim Ring | Hollow |

---

# ⚙️ Processing Pipeline

## 📌 Phase 1 – Image Restoration

- Add different types of image noise.
- Restore images using spatial and frequency domain filters.
- Evaluate restoration performance using **MSE** and **PSNR**.

---

## 📌 Phase 2 – Segmentation

- Thresholding
- Morphological Operations
  - Opening
  - Closing
  - Erosion
  - Dilation
  - Boundary Extraction

This stage generates a clean binary mask for the target object.

---

## ⭐ Phase 3 – Feature Extraction & Shape Classification

The final stage focuses on recognizing object shapes.

The system automatically extracts the following geometric features:

- 📐 Area
- 📏 Perimeter
- ⭕ Circularity

These features are projected into a lower-dimensional feature space using **Principal Component Analysis (PCA)**.

Finally, each object is classified into one of the following categories:

- ⚽ Circular
- 🪵 Elongated
- 🔩 Polygonal
- ☕ Irregular
- 🛟 Hollow

This approach enables accurate shape recognition while providing a clear visualization of the feature distribution.

---

# 🛠️ Technologies

- Python
- OpenCV
- NumPy
- Scikit-learn
- Gradio
- Matplotlib

---

# 📸 Results

The application provides:

- ✅ Restored Images
- ✅ Segmented Objects
- ✅ Morphological Results
- ✅ Feature Extraction
- ✅ PCA Visualization
- ✅ Final Shape Classification
- ✅ MSE & PSNR Evaluation

---

# 👨‍💻 Author

**Abdulrahman Alhazmi**



---

# 📜 License

This project was developed for educational purposes as part of the **AI342 Professional Digital Image Processing** course.
