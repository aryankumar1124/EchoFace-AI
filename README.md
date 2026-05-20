# EchoFace AI

AI-powered real-time face swapping and enhancement system built using ONNX Runtime, CoreML, OpenCV, and Gradio.

---

## Overview

EchoFace AI is a deep-learning-based face manipulation platform capable of performing high-quality face swaps, age modification, facial enhancement, and real-time AI-powered image processing.

The project was customized and optimized for macOS Apple Silicon devices using CoreML acceleration and ONNX Runtime for improved local inference performance.

---

## Features

- Real-time AI face swapping
- Facial enhancement and restoration
- Age modification
- Face masking and detection
- ONNX Runtime accelerated inference
- CoreML support for Apple Silicon
- Interactive Gradio-based web interface
- Local processing with no cloud dependency

---

## Tech Stack

- Python
- OpenCV
- ONNX Runtime
- CoreML
- Gradio
- NumPy
- Deep Learning Models

---

## Architecture

EchoFace AI uses a modular AI inference pipeline:

1. Face Detection  
2. Landmark Extraction  
3. Face Embedding Generation  
4. Neural Face Swapping  
5. Post-processing & Enhancement  
6. Final Rendering

The system leverages ONNX Runtime and CoreML execution providers for optimized local inference.

---

## Installation

```bash
git clone https://github.com/aryankumar1124/EchoFace-AI.git
cd EchoFace-AI