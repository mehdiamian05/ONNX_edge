## Files

- `edge_cnn_to_onnx.ipynb`  
This repository demonstrates a simple workflow for training a lightweight CNN model in PyTorch, exporting it to ONNX, and simplifying the ONNX graph for efficient edge deployment.

The goal is to ensure consistent model behavior across deployment environments while reducing unnecessary operations in the computation graph. This makes the model lighter, faster, and better suited for resource-constrained devices such as mobile phones, wearables, and edge trackers.

- `quantization_demo.ipynb`  
  Demonstrates the impact of dynamic quantization on a larger MLP model. It compares FP32 and quantized models in terms of accuracy, model size, size reduction, and inference time to evaluate suitability for edge deployment.