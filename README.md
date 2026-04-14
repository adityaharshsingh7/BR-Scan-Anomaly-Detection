# BR-Scan: AI-Powered Diagnostic Engine for Breast Anomaly Detection

### 🚀 Performance Milestone: 97.1% Diagnostic Accuracy

## 📌 Project Overview
The **BR-Scan Diagnostic Engine** is a specialized computer vision solution engineered for proprietary medical hardware using red-light transillumination. This project successfully navigated the "Domain Gap" where standard deep learning models—trained on traditional Ultrasound or X-ray data—fail to accurately interpret the unique red-light spectrum.

By developing a custom **Statistical Baseline Anomaly Detector**, this engine identifies malignant tissue shadows with high precision while neutralizing anatomical interference.

---

## 📸 Project Visuals

### 📂 Dataset Sample
*Samples of the red-light transillumination scans showing the contrast between healthy tissue and pathological anomalies.*
> **[INSERT IMAGE: `assets/dataset_sample.png`]**

### 📊 Diagnostic Dashboard
*The final inference interface displaying the anomaly detection mask, the 15% threshold calculation, and the final classification output.*
> **[INSERT IMAGE: `assets/dashboard_result.png`]**

---

## 🛠️ Technical Innovations

* **Statistical Baseline Architecture**: Pivoted from standard ResNet-50 deep learning to a pixel-wise differential analysis engine to better handle proprietary hardware constraints.
* **Adaptive Nipple Masking**: Engineered intensity-based circle detection logic using OpenCV to filter anatomical density, significantly reducing False Positives (FPs).
* **Differential Spatial Masking**: Implemented logic to compare live scans against a "Master Healthy Profile" to isolate pathological density clusters.
* **Threshold Calibration**: Successfully validated a **15% Anomaly Threshold** to ensure high sensitivity for malignant detections while maintaining 100% specificity on healthy samples.

---

## 📊 Performance Benchmarks
| Metric | Result |
| :--- | :--- |
| **Accuracy (Pilot Batch)** | **97.1%** |
| **Healthy Sample Specificity** | **100%** |
| **Processing Time** | Near Real-Time Inference |
| **Model Foundation** | Statistical Differential + OpenCV |

---

## 💻 Tech Stack
* **Language**: Python
* **Libraries**: OpenCV, PyTorch, NumPy, Matplotlib
* **Architecture**: Statistical Baseline Anomaly Detection
* **Development Environment**: Google Colab / Replit

---

## 🎓 Professional & Academic Context
This project served as the core technical deliverable for my AI/ML Engineering Internship at **D3S Healthcare Technologies** and contributed to my final-year capstone project at the **United World Institute of Technology (UIT), Karnavati University**.

---

### **How to add your images:**
1.  Create an `assets` folder in your GitHub repository.
2.  Upload your dataset screenshots and dashboard images to that folder.
3.  Update the `[INSERT IMAGE]` placeholders above with your actual file names (e.g., `<img src="assets/my_result.png" width="600">`).
