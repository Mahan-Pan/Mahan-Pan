<h1 align="center">Mahan Panahandeh</h1>

<p align="center">
  MASc Researcher · Toronto Metropolitan University<br>
  Deep Learning & Image Processing
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mahan-p-1433b1364/">LinkedIn</a> ·
  <a href="mailto:mahanpanahande@gmail.com">mahanpanahande@gmail.com</a> ·
  Toronto, ON · Canadian Permanent Resident
</p>

---

## What I work on

I develop deep learning models and image processing pipelines, applying them to real-world problems across clinical and industrial settings.

My MASc research at TMU is in medical image processing and deep learning, supervised by Prof. Javad Alirezaei. Previously, I built U-Net models for brain tumor segmentation and a two-stage DenseNet121 pipeline for COVID-19 classification from chest X-rays.

My background spans analog and digital systems, signal processing, embedded systems, and power electronics, which means I think about problems end-to-end, not just the model.

---

## Projects

### 🧠 Brain Tumor Segmentation · [repo →](https://github.com/Mahan-Pan/brain-tumor-segmentation)
U-Net trained on 2,146 brain MRI images (COCO-annotated). Achieved **97.99% test accuracy** on an independent held-out set.

Key engineering decisions:
- Custom data generator for COCO bounding box → binary mask conversion (batch processing on 640×640 images)
- Resolved exploding gradients via Adam with norm clipping + numerically stable custom loss
- Early stopping converged at epoch 15; trained on NVIDIA A100-40GB in ~25 min

`Python` `TensorFlow` `Keras` `U-Net` `COCO` `MRI`

---

### 🫁 COVID-19 Detection from Chest X-Rays · [repo →](https://github.com/Mahan-Pan/covid19-xray-detection)
Two-stage pipeline: U-Net lung segmentation → fine-tuned DenseNet121 four-class classifier (COVID-19 / Pneumonia / Lung Opacity / Normal). Built on the COVID-19 Radiography Database (21,165 images). Includes Grad-CAM visualization for interpretability.

`Python` `TensorFlow` `DenseNet121` `U-Net` `Transfer Learning` `Grad-CAM`

---

### ⚡ PID-Controlled Buck Converter · [repo →](https://github.com/Mahan-Pan/pid-buck-converter)
Designed and simulated a DC-DC buck converter in MATLAB/Simulink, then implemented the PID controller on an ESP32 microcontroller and validated the closed-loop system via hardware-in-the-loop (HIL) testing.

`MATLAB` `Simulink` `ESP32` `C` `Power Electronics` `HIL`

---

## Skills

| Area | Tools |
|---|---|
| Deep Learning | TensorFlow, Keras, U-Net, CNNs, DenseNet, Transfer Learning |
| Medical Imaging | Segmentation, CT, MRI, COCO annotations |
| Programming | Python, C, C++, C#, Assembly (AVR, 8086) |
| Hardware | ESP32, AVR, PCB Design, Power Electronics, Oscilloscope |
| Simulation | MATLAB, Simulink, HIL Testing |

---

## Background

- **MASc, Electrical & Computer Engineering** — Toronto Metropolitan University *(GPA: 4.33/4.33)*
- **BSc, Electrical Engineering** — Yazd University / Shiraz University, Iran
- Teaching Assistant: Signals & Systems I & II, Digital Image Processing (TMU, 2025–present)

---

<p align="center">
  <sub>Open to research collaborations and ML engineering roles · Canadian Permanent Resident</sub>
</p>
