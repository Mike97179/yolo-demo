# yolo-demo

Object detection demo using YOLOv8.

## Contents

- `images/` — test images (cats, dogs, combined)
- `notebooks/` — Jupyter notebooks step by step
- `datasets/` — annotated datasets for fine-tuning

## Notebooks

| Notebook | Description |
|----------|-------------|
| `01_preprocessing.ipynb` | Image preprocessing pipeline for YOLO |
| `02_detection_demo.ipynb` | Object detection with pretrained YOLOv8 |
| `03_fine_tuning.ipynb` | Fine-tuning on custom dataset |

## Setup

```bash
git clone https://github.com/Mike97179/yolo-demo.git
cd yolo-demo
pip install ultralytics
```

## Usage in Google Colab

```python
!git clone https://github.com/Mike97179/yolo-demo.git
%cd yolo-demo
```
