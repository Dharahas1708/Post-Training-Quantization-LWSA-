# Edge AI Plant Disease Detection

## Overview

This project presents an Edge AI-based plant disease detection system using a lightweight deep learning model. The goal is to enable accurate and fast disease detection directly on mobile or edge devices without requiring an internet connection.

The model is based on **MobileNetV3** and is optimized using **Layer Wise Sensitivity Analysis (LWSA)** and **Post-Training Quantization (PTQ)** to reduce memory usage while maintaining high accuracy.

## Features

- Offline plant disease detection
- Lightweight MobileNetV3 model
- INT8 post-training quantization
- Fast inference on edge devices
- Reduced memory footprint
- Suitable for mobile deployment

## Model

- **Base Model:** MobileNetV3
- **Optimization:** Layer Wise Sensitivity Analysis (LWSA)
- **Quantization:** Float32 → INT8

## Results

| Metric | Value |
|--------|-------|
| Model Size | 8.0 MB → 2.0 MB |
| Memory Reduction | 75% |
| Inference Time | 0.05 seconds |
| Accuracy Loss | Minimal |
| Internet Requirement | Not Required |

Compared to cloud-based inference, the proposed approach eliminates network latency and provides reliable offline predictions.

## Technologies Used

- Python
- TensorFlow
- TensorFlow Lite
- MobileNetV3
- NumPy
- OpenCV
- Google Colab

## Project Structure

```
.
├── Plant_Disease_Detection.ipynb
├── README.md
└── requirements.txt
```
