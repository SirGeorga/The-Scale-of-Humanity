# 🌍 Scale of Humanity

An interactive web experiment designed to visualize massive numbers.  
This project lets you *see* what a crowd from **1 person to 8 billion (Earth’s population)** looks like by comparing it to real-world objects.

🔗 **Demo:** https://sirgeorga.github.io/The-Scale-of-Humanity/

---

## 📖 About

The human brain struggles to comprehend extremely large numbers like **8,000,000,000**.

This project solves that problem by:
- Letting you control a **logarithmic slider**
- Dynamically scaling a crowd in real time
- Automatically adjusting the camera to maintain context
- Comparing the crowd with **familiar landmarks**

---

## ✨ Features

### 📊 Logarithmic scaling
Smooth transition from **1 → billions** using a logarithmic slider.

### 🌻 Dense mathematical distribution
Uses a **Fibonacci spiral (sunflower pattern)**.

### ⚡ Performance optimizations
- InstancedMesh (Three.js)
- Dynamic shadow disabling (>300 objects)
- Switch to single mesh for performance (~60 FPS)

### 🎥 Isometric projection
OrthographicCamera eliminates distortion.

### 🌬 Micro animation
Subtle floating animation for realism.

### 🧭 Smart UI
2D labels that follow 3D objects.

---

## 🛠 Tech Stack

- HTML5 / CSS3  
- Vanilla JavaScript  
- Three.js  

---

## 🚀 Getting Started

### Clone repository
```bash
git clone https://github.com/YOUR_NICKNAME/humanity-scale.git
