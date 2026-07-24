# Road Damage Detection and Captioning using YOLOv8 + BLIP (LoRA)

## Overview

This project presents an end-to-end deep learning pipeline for automatic road damage detection and image caption generation. The system first detects road damages using YOLOv8 and then generates descriptive captions using BLIP with LoRA-based fine-tuning.

The objective is to assist road maintenance authorities by automatically identifying damaged road regions and producing natural language descriptions.

---

## Features

- Road damage detection using YOLOv8
- Automatic image caption generation using BLIP
- LoRA-based parameter-efficient fine-tuning
- Optimized feature extraction and caching
- End-to-end inference pipeline

---

## Model Architecture

Input Image
↓
YOLOv8
↓
Detected Damage Region
↓
BLIP + LoRA
↓
Generated Caption

---

## Technologies Used

- Python
- PyTorch
- YOLOv8
- BLIP
- LoRA
- OpenCV

---

## Evaluation

BLEU Scores

| Metric | Score |
|---------|-------|
| BLEU-1 | 0.777 |
| BLEU-2 | 0.749 |
| BLEU-3 | 0.720 |
| BLEU-4 | 0.681 |

---

## Repository Structure

```
dataset/
models/
train.py
inference.py
caption.py
requirements.txt
README.md
```

---

## Future Work

- Real-time deployment
- Mobile application
- Multi-language caption generation

---

## Author

Vishnu K.
M.Tech Data Science
Amrita Vishwa Vidyapeetham
