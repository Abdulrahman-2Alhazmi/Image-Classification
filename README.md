# 🖼️ AI342 Professional Digital Image Processing System

A complete Digital Image Processing application developed for the **AI342** course. The project demonstrates the full image processing pipeline, including image restoration, segmentation, feature extraction, and object classification using **PCA (Principal Component Analysis)**.

---

## ✨ Features

- 📷 Image Upload
- 🔊 Noise Generation
  - Gaussian
  - Salt & Pepper
  - Periodic
  - Uniform
- 🧹 Image Restoration
  - Spatial Domain Filters
  - Frequency Domain Filters
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
<img src="Screenshot 2026-07-19 024141.png" width="900">
</p>

> Replace **interface.png** with a screenshot of your application.

---

# 🎥 Demo Video

Watch the project demonstration here:

🔗 **Video Link**

```
**[Project Demo Video](https://youtu.be/Gy7mM6QsP14)**

---

# 📂 Dataset

The project classifies five different object categories:

| Object | Category |
|---------|----------|
| ⚽ Soccer Ball | Circular |
| 🪵 Wooden Stick | Elongated |
| 🔩 Hex Nut | Polygonal |
| ☕ Coffee Stain | Irregular |
| 🛟 Swim Ring | Hollow |

---

# ⚙️ Processing Pipeline

### 📌 Phase 1 – Image Restoration

- Add different noise models.
- Restore images using spatial and frequency domain filtering.
- Evaluate restoration performance using MSE and PSNR.

---

### 📌 Phase 2 – Segmentation

- Thresholding
- Morphological Operations
  - Opening
  - Closing
  - Erosion
  - Dilation
  - Boundary Extraction

---

### 📌 Phase 3 – Feature Extraction & Classification ⭐

The classification stage is the main objective of the project.

Each segmented object is analyzed by extracting geometric features:

- 📐 Area
- 📏 Perimeter
- ⭕ Circularity

The extracted features are projected into a lower-dimensional feature space using **Principal Component Analysis (PCA)**.

Finally, the system classifies every object into one of the following categories:

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
- ✅ Shape Classification
- ✅ MSE & PSNR Evaluation

---

# 👨‍💻 Author

**Abdulrahman Alhazmi**


---

# 📜 License

This project was developed for educational purposes as part of the **AI342 Professional Digital Image Processing** course.
