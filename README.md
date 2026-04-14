This `README.md` is structured to highlight the technical complexity and the successful **97.1% accuracy milestone** you achieved during your internship. Use the code block below to copy and paste directly into your GitHub repository.

-----

# BR-Scan: AI-Powered Diagnostic Engine for Breast Anomaly Detection

### 🚀 Performance Milestone: 97.1% Diagnostic Accuracy

## 📌 Project Overview

The **BR-Scan Diagnostic Engine** is a specialized computer vision solution engineered for proprietary medical hardware using red-light transillumination. This project addresses the "Domain Gap" where standard deep learning models (trained on traditional Ultrasound or X-ray data) fail to accurately interpret the unique red-light spectrum.

By developing a custom **Statistical Baseline Anomaly Detector**, this engine identifies malignant tissue shadows with high precision while neutralizing anatomical interference.

-----

## 📸 Project Visuals

### 📊 Diagnostic Dashboard

*The final inference interface displaying the anomaly detection mask, the 15% threshold calculation, and the final classification output.*

### 📂 Dataset Sample

*Samples of the red-light transillumination scans showing the contrast between healthy tissue and pathological anomalies.*

> **<img src="assets/Healthy_detected.png" width="3000px" alt="Healthy"/>**
> **<img src="assets/unhealthy_detected.png" width="3000px" alt="Unhealthy"/>**

-----

## 🛠️ Technical Innovations

  * **Statistical Baseline Architecture**: Pivoted from standard ResNet-50 deep learning to a pixel-wise differential analysis engine to better handle proprietary hardware constraints.
  * **Adaptive Nipple Masking**: Engineered intensity-based circle detection logic using OpenCV to filter anatomical density, significantly reducing False Positives (FPs).
  * **Differential Spatial Masking**: Implemented logic to compare live scans against a "Master Healthy Profile" to isolate pathological density clusters.
  * **Threshold Calibration**: Successfully validated a **15% Anomaly Threshold** through blind testing with unseen healthy samples.

-----

## 📊 Performance Benchmarks

| Metric | Result |
| :--- | :--- |
| **Accuracy (Pilot Batch)** | **97.1%** |
| **Healthy Sample Specificity** | **100%** |
| **Processing Time** | Near Real-Time Inference |
| **Model Foundation** | Statistical Differential + OpenCV |

**<img src="assets/dashboard_result.png" width="3000px" alt="Dashboard"/>**
-----

## 💻 Tech Stack

  * **Language**: Python
  * **Libraries**: OpenCV, PyTorch, NumPy, Matplotlib
  * **Environment**: Google Colab / Replit

-----

## 🎓 Professional & Academic Context

This project served as the core technical deliverable for my Software Development Engineering Internship at **D3S Healthcare Technologies**, which began on January 19, 2024. It also contributes to my technical portfolio as a final-year B.Sc. (Hons) Computer Science student at the **United World Institute of Technology (UIT), Karnavati University**.

-----
