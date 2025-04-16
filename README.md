# K-Means Image Compression 🎨

This project uses the K-Means clustering algorithm to perform **image compression** by reducing the number of unique colors in an image.

## 💡 What the Project Does

- Compresses an image by clustering similar colors
- Replaces each pixel with the nearest centroid (color)
- Visualizes original vs compressed image using only **K=16** colors

## 📁 Contents

- Python code implementing:
  - `find_closest_centroids`
  - `compute_centroids`
  - K-means loop with visualization
- Input image: `bird_small.png`
- Final compressed output and centroid visualization

## 🔧 Technologies Used

- Python
- NumPy
- Matplotlib
- Unsupervised Learning (K-Means)

## 🚀 Result

Reduced a full-color image to just 16 colors — while preserving visual quality.

---

⭐ Created as part of the **Machine Learning Specialization**  
📚 Guided by practice exercises from Andrew Ng’s course

