# 🌙 Night time Image Processing using Histogram Equalization

This project focuses on image processing techniques to enhance low-light grayscale images using Histogram Equalization.  
The dataset consists of nighttime road images captured in rural areas, making it suitable for contrast enhancement experiments.

---

## 📂 Dataset Overview

### 1️⃣ Origin and Type of Data
The images used in this project were collected with a grayscale camera while driving at night on rural country roads in Germany.

Dataset characteristics:
- Image type: Grayscale (black and white)
- Lighting condition: Low-light (nighttime)
- Environment: Rural roads
- Image resolution: 960 × 1280 pixels
- Image content: Vehicles, road surfaces, light reflections from headlights and surroundings

This dataset is ideal for testing image enhancement techniques such as histogram equalization due to its low contrast and limited illumination.

---

### 2️⃣ Data Structure and Annotations

Each image is accompanied by a JSON annotation file.  
The annotation format is similar to the COCO (Common Objects in Context) dataset, commonly used in computer vision tasks.

#### Key Elements in the JSON Annotation

| Key | Description | Purpose |
|----|------------|--------|
| image_id | Unique image identifier | Links annotation to a specific image |
| annotations | List of detected vehicles | Describes vehicle objects in the image |
| blurs | List of blurred regions | Used to hide sensitive areas (e.g., license plates) |
| oid | Object ID | Identifies each vehicle uniquely |
| pos | Vehicle position | Coordinates where the vehicle appears |
| instances | Vehicle lights | Contains one or more light sources |
| direct | Boolean (true/false) | Indicates whether the vehicle is directly visible |
| rear | Boolean (true/false) | Indicates vehicle direction (front or rear view) |

---

## 🛠️ Image Processing Method

### Histogram Equalization
Histogram Equalization is applied to:
- Improve image contrast
- Enhance visibility of dark regions
- Redistribute pixel intensity values more evenly

This method is especially effective for grayscale images captured under poor lighting conditions.

---

## 📊 Results
After applying histogram equalization:
- Dark areas become more distinguishable
- Vehicle shapes and road details are clearer
- Overall image contrast is significantly improved

---

## 💻 Technologies Used
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="50"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/opencv/opencv-original-wordmark.svg" width="50"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" width="50"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/googlecolab/googlecolab-original.svg" width="50"/>

---

## 🎯 Project Purpose
This project was created as part of an academic image processing study, focusing on enhancing low-light images and understanding how contrast enhancement techniques work in real-world conditions.

---

## 👩‍🎓 Author
Elsa Anggraini  
Computer Science Student
