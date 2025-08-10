# Animal Behaviour Detection

This project uses custom YOLOv5 and YOLOv8 models trained to detect **zebra** and **giraffe** from images and videos. It compares performance between the two models and outputs annotated media files showing detected animals.

---

## Features

- Custom-trained YOLOv5 and YOLOv8 models focused on detecting zebras and giraffes.
- Uses a pretrained YOLOv8 model for class name mapping.
- Supports detection on images and videos.
- Saves annotated images/videos with bounding boxes.
- Reports detection and performance metrics (precision, recall, F1, mAP, FPS).

---

## Model Details

| Model        | Precision | Recall | F1 Score | mAP@50 | FPS |
|--------------|-----------|--------|----------|--------|-----|
| YOLOv5 (custom) | 0.96      | 0.96   | 0.80     | 0.84   | 27  |
| YOLOv8 (custom) | 1.00      | 0.95   | 0.80     | 0.85   | 27  |

---

## Setup

#### 1. Clone the repo:

```bash
git clone
cd animal-behaviour-detection
```
## Install dependencies:
```bash
pip install -r requirements.txt
```

## Output Screenshot
![Animal Behaviour Detection](/assets/images/output.png)

