# 🎨 Color Object Detection System — Real-Time Vision Fundamentals

<p align="center">
  <b>Detect and track color-based objects using classical Computer Vision techniques</b><br>
  Built with OpenCV + Gradio for interactive and real-time experimentation
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/UI-Gradio-red?style=flat-square"/>
  <img src="https://img.shields.io/badge/Focus-Image%20Processing-orange?style=flat-square"/>
</p>

---

## 💡 What This Project Does

This application detects objects based on their **color (Red, Green, Blue)** and highlights them with bounding boxes.

👉 Built to demonstrate **core computer vision fundamentals** used in real-world systems.

---

## Demo Images

![demo](https://github.com/Tanmay1112004/color-object-detection-opencv/blob/main/color%20detection/screenshots/Screenshot%202025-09-04%20142530.png)

![demo](https://github.com/Tanmay1112004/color-object-detection-opencv/blob/main/color%20detection/screenshots/Screenshot%202025-09-04%20142614.png)

![demo](https://github.com/Tanmay1112004/color-object-detection-opencv/blob/main/color%20detection/screenshots/Screenshot%202025-09-04%20142730.png)


---

## 🚨 Problem Statement

In many real-world scenarios:

* Object detection models may be overkill
* Lightweight solutions are needed
* Real-time processing is critical

👉 Example: Robotics, tracking colored markers, industrial sorting

---

## 🎯 Solution

A lightweight **color-based detection system** that:

✅ Detects objects using HSV color segmentation
✅ Works in real-time without heavy models
✅ Provides an interactive UI for experimentation
✅ Runs efficiently on low-resource systems

---

## ⚡ Key Features

### 🎨 Multi-Color Detection

* Detect:

  * 🟥 Red
  * 🟩 Green
  * 🟦 Blue
* Option to detect all colors together

---

### ⚡ Real-Time Processing

* Fast execution using OpenCV
* No GPU required

---

### 📸 Flexible Input

* Upload images
* Capture via webcam

---

### 💻 Interactive UI

* Built with Gradio
* Clean and user-friendly interface

---

## 🧠 Why This Project Matters (Recruiter POV)

Most candidates:
👉 Jump directly to deep learning

This project:

✅ Demonstrates **fundamental CV concepts**
✅ Shows understanding of **image processing pipelines**
✅ Focuses on **efficiency and simplicity**
✅ Acts as a base for advanced detection systems

👉 Translation: *You understand the building blocks, not just libraries.*

---

## 🧬 Detection Pipeline

```id="colorflow1"
Input Image
   │
   ▼
Color Space Conversion (RGB → HSV)
   │
   ▼
Color Masking (Thresholding)
   │
   ▼
Noise Reduction (Morphology)
   │
   ▼
Contour Detection
   │
   ▼
Bounding Box Rendering
   │
   ▼
Gradio UI Output
```

---

## 🛠 Tech Stack

| Layer           | Technology           |
| --------------- | -------------------- |
| Computer Vision | OpenCV               |
| UI              | Gradio               |
| Processing      | NumPy                |
| Deployment      | Google Colab / Local |

---

## 🚀 Quick Start

```bash id="runcolor1"
git clone https://github.com/Tanmay1112004/color-object-detection-opencv.git
cd color-object-detection-opencv
pip install -r requirements.txt
python app.py
```

---

## ☁️ Run on Google Colab

👉 Open the notebook and execute cells
👉 Upload image → detect colors instantly

---

## 🎯 Real-World Applications

* Industrial object sorting
* Robot navigation (color markers)
* Traffic signal detection
* Quality control systems
* Simple tracking systems

---

## 📈 What This Project Demonstrates

* Image processing fundamentals
* Color segmentation techniques
* Object detection without ML
* Pipeline-based CV thinking
* UI + backend integration

---

## 🔮 Future Enhancements

* [ ] Real-time video tracking
* [ ] Add more colors (custom ranges)
* [ ] Object tracking across frames
* [ ] Combine with YOLO detection
* [ ] Performance optimization

---

## 🤝 Contributing

```bash id="contri_color1"
git checkout -b feature/enhancement
git commit -m "Added new feature"
git push origin feature/enhancement
```

---

## ⭐ Support

If you found this useful:

* ⭐ Star the repo
* 🍴 Fork it
* 🚀 Build on it

---

## 👨‍💻 Developer Mindset

**From simple pixels → meaningful detection → scalable systems**

---

## 🔥 Final Thought

Not every problem needs deep learning.

👉 Sometimes, **simple and efficient solutions win.**

---

<p align="center">
  🎨 <b>Detect smarter. Build faster. Think fundamentals.</b>
</p>

---
