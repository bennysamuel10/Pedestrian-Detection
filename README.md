[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bennysamuel10/Pedestrian-Detection/blob/main/notebooks/object_detection_pipeline.ipynb)

# TensorFlow 2 Object Detection Pipeline

This project builds a custom object detection pipeline using TensorFlow 2's Object Detection API. The model is trained to detect gestures like ThumbsUp, ThumbsDown, ThankYou, and LiveLong.

## 📁 Folder Structure

```
Tensorflow/
├── models/
├── scripts/
└── workspace/
    ├── annotations/
    ├── images/
    ├── models/
    └── pre-trained-models/
```

## 🚀 How to Run

1. Set up paths and folders (see the notebook).
2. Install required dependencies.
3. Download a pretrained model from TensorFlow model zoo.
4. Create label maps and TFRecord files.
5. Update config and train your model.

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

## 📓 Notebook

See `notebooks/object_detection_pipeline.ipynb` for the full implementation.
