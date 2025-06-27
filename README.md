# 🌾 Grain Palette: A Deep Learning Odyssey in Rice Type Classification

## 📌 Project Overview

Grain Palette is a deep learning-powered web application designed to classify **five different varieties of rice grains** using **Transfer Learning with MobileNetV2**. This project aims to empower farmers by providing an **affordable**, **accessible**, and **fast** rice classification tool without the need for agricultural experts.

---

## 🎯 Purpose

The primary goal is to help farmers and agricultural businesses:

- Identify rice varieties quickly.
- Make informed decisions regarding **rice quality** and **market value**.
- Reduce dependency on manual expert classification.

---

## 🧠 Ideation Phase

### ✅ Problem Statement
Traditional rice classification requires expert analysis, which is often **costly and time-consuming**. This project offers an **automated, instant, and low-cost solution**.

### ✅ Empathy Mapping
We understood the farmer’s pain points and built a **simple and intuitive web interface**.

### ✅ Brainstorming Outcomes
- Use of lightweight deep learning models.
- Web-based deployment for accessibility.
- Clean UI/UX for non-technical users.

---

## 📈 Requirement Analysis

- **Image-based rice variety classification**
- **Web interface** built with **Flask (Python)**
- **Pre-trained MobileNetV2 model** for efficient inference
- Optional **SQLite database** for data storage (if needed)

---

## 📊 Data Flow & Technology Stack

### ✅ Data Flow:
1. **Image Upload (User)**
2. **Preprocessing**
3. **Model Prediction**
4. **Display Result (Rice Type)**

### ✅ Technology Stack:
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Flask (Python)
- **Model:** MobileNetV2 (TensorFlow/Keras)
- **Database:** SQLite (Optional)

---

## 🏗️ Project Design & Architecture

- **Solution Fit:** Lightweight and optimized for web deployment.
- **Architecture Overview:**  
  User uploads an image → Flask server processes it → Deep Learning model predicts rice type → Web app displays result.

---

## 📅 Project Planning & Scheduling

The project was developed in the following phases:

1. Dataset collection
2. Model training
3. Web development
4. Testing & Deployment

---

## 🧪 Testing & Results

- **Performance Testing:**  
  Evaluated for **accuracy**, **speed**, and **efficiency**.

- **Results:**  
  Output screenshots (included in `/screenshots/` folder or report PDF) demonstrate successful rice classification.

---

## ✅ Advantages

- Affordable & Accessible
- User-friendly web interface
- Real-time rice classification

## ⚠️ Limitations

- Accuracy depends on **dataset quality**
- Requires **internet connection** for web-based usage

---

## ✅ How to Run Locally

```bash
git clone 
cd Grain_Palette
pip install -r requirements.txt
python app.py
