# Hi — I'm Om Prakash Sahu 👋

**Machine Perception • Autonomous Systems • Embedded Automotive**

---
* ✅ **Focus areas:** Perception (LiDAR/Camera), 3D detection & segmentation, SLAM/localization, control (MPC), and automotive systems engineering (ISO 26262, V-Model).
* ✅ **Stack:** Python, C++, ROS1/2, TensorFlow/PyTorch, PointPillars, OpenCV, Docker, CI/CD, Plotly, Jupyter Lab.

---

## Key skills & technologies

![Python](https://img.shields.io/badge/Python-3670A0?logo=python\&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?logo=c%2B%2B\&logoColor=white) ![ROS](https://img.shields.io/badge/ROS-Blue?logo=ros) ![LiDAR](https://img.shields.io/badge/LiDAR-7C3AED) ![Deep Learning](https://img.shields.io/badge/Deep--Learning-FB8C00) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker\&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow\&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch\&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv\&logoColor=white) ![MPC](https://img.shields.io/badge/MPC-3DDC84)

> The `Notebooks` and `Docker` badges on each project indicate quick reproducibility for live demos.

---
# Projects

> **Legend:** `📒` = Notebook(s) • `🐳` = Docker • `⚙️` = C++/embedded • `🤖` = ROS • `🔬` = Research/experiments • `🏁` = Demo/reproducible

---

### 1. Visual Lane Following Robot (ACDC) — *ROS on Jetson Nano* 🤖🏁

**Short:** ROS system for lane detection, localization + steering (MPC) running on NVIDIA Jetson Nano; includes simulation + real-world tests.

**Link:** [https://github.com/infinityengi/visual-lane-following-robot-acdc](https://github.com/infinityengi/visual-lane-following-robot-acdc)

**Tags:** `ROS` `C++` `Python` `Jetson Nano` `MPC` `Simulation` `Robotics`.

---

## A. Perception & 3D Sensing

### 1. semantic-image-segmentation — *image segmentation starter kit* 📒🐳

**Short:** Reproducible starter kit: data pipelines, color→class mapping, U-Net baseline, augmentations, training & export (SavedModel/ONNX/TFLite).

**Link:** https://github.com/infinityengi/semantic-image-segmentation

**Tags:** `U-Net` `Data Pipeline` `Augmentation` `TensorFlow` `PyTorch` `Experiment Tracking` `Export`.

---

### 2. point-cloud-semantic-segmentation — *LiDAR semantic segmentation* 📒🐳🔬

**Short:** TensorFlow-based pipelines for point-cloud segmentation, cross-modal label transfer, and interactive Plotly visualizations.

**Link:** https://github.com/infinityengi/point-cloud-semantic-segmentation

**Notebooks:** `1_Semantic_Point_Cloud_Segmentation.ipynb` • `2_Boosting_Semantic_Point_Cloud_Segmentation.ipynb`

**Tags:** `Point Cloud` `Semantic Segmentation` `TensorFlow` `Augmentation` `Plotly` `Docker`.

---

### 3. 3D-object-detection — *LiDAR-based detection & visualization* 📒🔬

**Short:** Reproducible 3D detection pipeline (PointPillars) on KITTI with end-to-end notebooks for dataset prep, training/inference, and visualization.

**Link:** https://github.com/infinityengi/3D-object-detection

**Tags:** `3D Object Detection` `PointPillars` `KITTI` `LiDAR` `Visualization` `Python` `Notebooks`.

**Quick-run:** Preprocessing notebook, anchor & hyperparameter inspection, 2D/BEV visualizers.

---

### 4. Semantic Grid Mapping — *BEV & occupancy grid mapping* 📒🔬🐳

**Short:** Reproducible framework for grid-based environment representation using camera and LiDAR; demonstrates semantic segmentation → BEV and occupancy grid mapping (PointPillars baseline).

**Link:** https://github.com/infinityengi/Semantic-Grid-Mapping

**Highlights:** pillarization, evidential prediction head, IPM + multi-camera stitching for 360° BEV.

**Tags:** `LiDAR` `BEV` `Semantic Segmentation` `PointPillars` `Computer Vision` `Python` `TensorFlow` `Docker` `Notebooks`.

**Quick-run:** `notebooks/01_pointcloud_grid_mapping.ipynb` • `notebooks/02_camera_grid_mapping.ipynb`

---

### 5. inverse-perspective-mapping-cpp — *IPM in C++ / OpenCV* ⚙️

**Short:** C++ implementation of Inverse Perspective Mapping for BEV generation, with configuration and OpenCV backend. Good for embedded/real-time tasks.

**Link:** https://github.com/infinityengi/inverse-perspective-mapping-cpp

**Tags:** `C++` `OpenCV` `IPM` `BEV` `Real-time` `Embedded`.

**Quick-start:** `conda env` or `pip` + Jupyter notebooks (notebooks/ quick-run cell).

---

## B. Localization & Mapping

### 6. AutoSeg-Localization — *segmentation + localization research framework* 📒🐳🔬

**Short:** Reproducible framework combining semantic segmentation with vehicle localization; Dockerized, curated notebooks, and experiment-tracking ready.

**Link:** https://github.com/infinityengi/AutoSeg-Localization

**Tags:** `Localization` `Semantic Segmentation` `Docker` `Experiment Tracking` `Notebooks` `Research`.

---

## C. Control, Systems Engineering & Safety

### 7. control-perception-hubs — *MPC, Robust Control, Sensor Fusion learning hub* 📒🔬

**Short:** Knowledge hub with tutorials, reference implementations and small reproducible projects across MPC, robust & networked control, and sensor fusion.

**Link:** https://github.com/infinityengi/control-perception-hubs

**Tags:** `MPC` `Control Theory` `Sensor Fusion` `Tutorials` `Notebooks`.

---

### 8. v-model-automotive-portfolio — *V-Model for automotive projects* 📒⚙️🏁

**Short:** Systems-engineering toolkit that maps artifacts to V-Model phases; includes lane-keep-assist case study with traceability, tests, and firmware examples.

**Link:** https://github.com/infinityengi/v-model-automotive-portfolio

**Tags:** `V-Model` `ISO 26262` `AUTOSAR` `HIL/SIL` `Systems Engineering` `Traceability`.

---

### 9. functional-safety-iso26262 — *practical ISO 26262 notes & templates* 📒

**Short:** Concise notes, tutorials and worked case studies for ISO 26262 — includes HARA exercise, management, HW/SW guidance and templates for safety cases.

**Link:** https://github.com/infinityengi/functional-safety-iso26262

**Tags:** `ISO 26262` `Functional Safety` `HARA` `Safety Case` `Automotive`.

---

## D. ADAS

### 10. ADAS-HandsOn-Repo — *ACC, AEB, LKA mini-projects & CI-friendly examples* 📒🏁

**Short:** Hands-on repositories for common ADAS features with reproducible notebooks and CI examples.

**Link:** https://github.com/infinityengi/ADAS-HandsOn-Repo

**Tags:** `ACC` `AEB` `LKA` `CI` `Notebooks` `ADAS`.

---

### 11. Lane Detection Using K-Means Clustering — *OpenCV pipeline* ⚙️

**Short:** Color clustering + polynomial fitting pipeline for robust yellow lane detection under challenging conditions.

**Link:** [https://github.com/infinityengi/Lane-Detection-Using-K-Means-Clustering](https://github.com/infinityengi/Lane-Detection-Using-K-Means-Clustering)

**Tags:** `OpenCV` `Computer Vision` `K-Means` `Lane Detection`.

---

### 12. Curved Lane Detection (Sliding Window) — *histogram + sliding window method* ⚙️

**Short:** Classic sliding-window lane detection with polynomial fitting, tested under varying curvature & lighting conditions.

**Link:** https://github.com/infinityengi/curved-lane-detection-sliding-window

**Tags:** `Lane Detection` `Sliding Window` `Polynomial Fit`.

---

## E. Knowledge & Productivity Tools

### 13. Professional Workflow Notes — *workflow templates & docs* 📒

**Short:** Templates and a repeatable workflow from ideation → delivery: docs, diagrams, pseudocode drafts, and AI-assisted engineering docs.

**Link:** https://github.com/infinityengi/professional-workflownotes

**Tags:** `Workflow` `Templates` `Docs` `Engineering`.

---
## 📫 Contact
- Email: [op.rksahu@gmail.com](mailto:op.rksahu@gmail.com)  
- LinkedIn: [linkedin.com/in/om-prakash-sahu-74b95584](https://linkedin.com/in/om-prakash-sahu-74b95584)
---
