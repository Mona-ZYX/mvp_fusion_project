# MVP Fusion Project

This repository contains my reproduction of the **MVP (Multi-Modal Virtual Points)** fusion framework for 3D object detection.

🔗 **Original GitHub repo by Tianwei Yin et al.:** [https://github.com/tianweiy/MVP](https://github.com/tianweiy/MVP)

---

## 📌 Project Purpose

This codebase was created as part of a course research assignment. The main goals are:
- To reproduce the MVP fusion pipeline using the nuScenes mini dataset.
- To understand the virtual point lifting process combining image and LiDAR data.
- To compare fusion-based detection with LiDAR-only detection (CenterPoint).

---

## 📁 Repository Structure

- `MVP/`: Reproduction of the original MVP fusion framework.
- `CenterPoint/`: LiDAR-only baseline detector.
- `CenterNet2/`: 2D detector used to generate virtual points for fusion.

---

## 🚀 How to Run

Please refer to the original [MVP GitHub instructions](https://github.com/tianweiy/MVP) for environment setup, data preparation, training, and inference. This reproduction uses a simplified configuration based on the mini nuScenes dataset for testing and demonstration purposes.

---

## ⚠️ Disclaimer

This is **not original work**. The implementation is adapted from the official MVP project and associated repositories. It is used solely for academic purposes in a university research context.

---

## 📝 License

This repository inherits the MIT License from the original MVP codebase.
