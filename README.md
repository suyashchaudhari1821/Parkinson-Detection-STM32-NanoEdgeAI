# Parkinson Disease Detection using STM32 & Edge AI

## 📘 Project Description
This project aims to detect motion abnormalities related to Parkinson’s disease using STM32 microcontroller and MPU6050 motion sensor.  
NanoEdge AI Studio is used to train and deploy a lightweight AI model that runs directly on the STM32, classifying tremor intensity as *Normal (Low)* or *Abnormal (High)* in real time.

---

## 🧩 Objectives
- Capture real-time motion data from the MPU6050 sensor.
- Analyze accelerometer and gyroscope patterns.
- Classify motion into Low and High tremor stages.
- Deploy a NanoEdge AI model for on-device classification.

---

## ⚙️ Tools & Technologies
**Hardware:**  
- STM32 Microcontroller  
- MPU6050 Accelerometer + Gyroscope  

**Software:**  
- STM32CubeIDE (Firmware Development)  
- NanoEdge AI Studio (Model Training & Deployment)  

---

## 🧠 Methodology
1. **Sensor Data Logging** — Interface MPU6050 with STM32 over I2C, capture motion data.  
2. **Model Creation** — Use NanoEdge AI Studio to train classification model (Low/High).  
3. **Integration** — Embed trained model into STM32 firmware and perform real-time inference.

---

## 📈 Results
| Motion Stage | Classification | Output |
|---------------|----------------|--------|
| Low           | Normal          | LED OFF |
| High          | Abnormal        | LED ON |

---

## 🧾 QA Issues Logged
1. Sensor not initializing on first boot – fixed by adjusting I2C delay.  
2. Classification threshold tuning required for stable results.  
3. Memory optimization for model integration.

---

## 💬 Collaboration Summary
- Logged issues in GitHub.
- Added comments and resolved issues iteratively.
- Verified AI inference consistency via live console monitoring.

---

## 🎯 Learning Outcomes
- Learned practical deployment of Edge AI models on STM32.  
- Understood data collection, preprocessing, and embedded inference.  
- Experienced QA documentation and issue tracking using GitHub.

---

## 📎 References
- [NanoEdge AI Studio Documentation](https://www.st.com/en/development-tools/nanoedgeaistudio.html)  
- [MPU6050 Datasheet](https://invensense.tdk.com/products/motion-tracking/6-axis/mpu-6050/)  

---

**Author:** [Your Name]  
**GitHub Repo:** https://github.com/[yourusername]/Parkinson-Detection-STM32-NanoEdgeAI
