# 🎨 Color Detection using KMeans Clustering

This project uses **KMeans Clustering** to detect the most dominant colors in an image and group similar shades using **Euclidean Distance**. It also matches detected colors to their closest named color using a provided CSV file (`color_names.csv`) and displays them with RGB codes and names in a visual grid.

---

## 📌 Features

- Load and preprocess image using OpenCV
- Convert image to RGB format
- Extract dominant colors using KMeans clustering
- Group similar color shades using Euclidean distance
- Match detected colors to closest human-readable names
- Visualize the results as color patches with RGB codes and names

---

## 🖼️ Example Output

- Shows a grid of dominant colors extracted from the image
- Displays RGB values and closest matching names
- Groups visually similar colors using clustering and distance metrics

---

## 🧾 Dataset

- `color_names.csv`  
  Contains a list of named colors with their corresponding RGB values:
  - `Name`
  - `Red (8 bit)`
  - `Green (8 bit)`
  - `Blue (8 bit)`

---

## 🧠 Technologies Used

- **Python**
- **OpenCV**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn** (KMeans Clustering)
- **SciPy** (Euclidean Distance Calculation)

---

---

## 🔧 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/color-detection-kmeans.git
   cd color-detection-kmeans

pip install -r requirements.txt

