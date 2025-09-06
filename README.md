An **AI-powered Skin Tone Analyzer** built using **Next.js** and **Machine Learning (ML)** techniques.  
This application analyzes uploaded images and detects **skin tones** using **computer vision** and **color clustering algorithms**.

---

## 🚀 Features
- 🖼️ **AI-powered skin tone detection**
- 🎨 Detects multiple tones from uploaded images
- 📊 Generates **HEX, RGB, and LAB color values**
- ⚡ Built with **Next.js 15** for high performance
- 📱 **Responsive UI** for mobile and desktop

---

## 🧠 Machine Learning & AI Concepts Used

This project uses **Computer Vision** and **Machine Learning** for analyzing skin tones:

### **1. Image Preprocessing**
- Uses **OpenCV / PIL** for image enhancement
- Removes background noise & smoothens color regions

### **2. Color Space Conversion**
- Converts uploaded images into **RGB, HSV, and LAB** color spaces
- More accurate tone detection than RGB-only

### **3. Clustering Algorithm**
- Uses **K-Means Clustering** to group similar pixel values
- Determines dominant skin tones within the selected region

### **4. Statistical Analysis**
- Calculates **mean, median, and mode** of detected tones
- Outputs accurate color predictions

### **5. AI/ML Metrics**
- Uses **Euclidean Distance** for color similarity
- Optimized for precision and performance

---

