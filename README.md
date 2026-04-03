# 🎬 Video Action Recognition using Deep Learning

This project implements a video action recognition system using CNN + LSTM on the UCF101 dataset.

## 🚀 Features
- Extract frames from videos
- CNN (ResNet18) for spatial features
- LSTM for temporal modeling
- Predict action from input video

## 📊 Results
- Training Accuracy: ~60–70% (subset)
- Model improves with more data and epochs

## 📂 Dataset
UCF101 (101 human action classes)

## ▶️ How to Run

### Train
```bash
python src/train.py