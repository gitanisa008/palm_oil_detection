# Palm Oil Detection

A side project for detecting palm oil trees using YOLOv8. This project is mainly built to process training data exported from **ArcGIS Pro** in the form of **image chips**, since running the training locally is too resource-heavy.

## Notebook
- `train_palm_yolov8.ipynb` — end-to-end training pipeline with YOLOv8

## Tech Stack
- [YOLOv8 (Ultralytics)](https://github.com/ultralytics/ultralytics)
- Python / Jupyter Notebook
- Google Colab (recommended)

## Getting Started
1. Export your training data from ArcGIS Pro as image chips.
2. Upload the image chips to Google Drive.
3. Open `train_palm_yolov8.ipynb` in Google Colab.
4. Connect to your dataset and run all cells to train and evaluate the model.

## License
[Apache 2.0](LICENSE)
