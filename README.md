---
title: Chain Snatching Detection
emoji: ""
colorFrom: blue
colorTo: red
sdk: gradio
sdk_version: 3.50.2
app_file: app.py
pinned: false
---

# Chain Snatching Detection

Upload a video to detect chain snatching activity using AI-powered computer vision.

## Features

- Video analysis through Gradio web UI
- TensorFlow/Keras model loaded from `model.h5`
- Binary classification: Normal vs Chain Snatching

## Usage

1. Upload a video file (`.mp4`, `.avi`, `.mov`)
2. Wait for inference to complete
3. Read the prediction result and confidence
