# Eye Disease Image Classification (TFLite)

This project is a deep learning image classification model trained to identify multiple eye diseases using retinal eye images.

## Model
- Architecture: MobileNetV2 / EfficientNet (Transfer Learning)
- Framework: TensorFlow
- Export format: TensorFlow Lite (.tflite)
- Accuracy: ~81% validation accuracy

## Dataset
- Source: Kaggle Eye Disease Image Dataset
- Classes include:
  - Diabetic Retinopathy
  - Glaucoma
  - Retinal Detachment
  - Myopia
  - Healthy
  - etc.

## Purpose
This model was built as a proof-of-concept for applying AI to medical imaging and early disease screening.

## Notes
The `.tflite` format allows deployment on mobile or edge devices.
