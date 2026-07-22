# MediaPipeHandLandmarkerExample

This repository contains ONNX models converted from the original MediaPipe TFLite models.

## Original Models

- https://github.com/google-ai-edge/mediapipe

## License

These models are licensed under the **Apache License 2.0**, the same license as the original MediaPipe models.

## Conversion Process

The models were converted from TFLite to ONNX using the following workflow:

```text
.tflite
    ↓
tf2onnx
    ↓
.onnx
    ↓
onnx-simplifier
```