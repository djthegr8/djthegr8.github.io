---
layout: page
title: Detection of AI-Generated Images
description: Inter IIT Tech Meet 13.0 - Classify AI-generated images, identify artifacts.
importance: 3
category: work
---

- Implemented a BNN with Fourier Magnitude and Local Binary Pattern channels for classification
- Benchmarked Static & Dynamic Quantization (PTQ & QAT) in PyTorch for real-time performance
- Used Jina-Clip-V2 and ResNets for artifact identification; fine-tuned Ovis1.6 for explanation generation
- Results: 2.6× speedup (80ms → 30ms) with <1% accuracy drop using Dynamic FX Mode PTQ; 97.2% accuracy, 30ms CPU inference
