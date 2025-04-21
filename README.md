# 🚀 Speeding Up Training and Inference in PyTorch Models

This repository provides a **practical guide to optimizing the performance of PyTorch models** for both training and inference, particularly in **CPU environments**. It walks through various techniques to speed up execution, reduce model size, and improve deployment readiness — all using a simple neural network on MNIST-style datasets.

---

## 🔍 Techniques Covered

| Optimization Method            | Purpose                                |
|--------------------------------|----------------------------------------|
| ✅ JIT Compilation (`torch.jit`)        | Speeds up inference via graph compilation |
| ✅ Dynamic Quantization                | Reduces model size and improves CPU performance |
| ✅ ONNX Export & Runtime               | Enables hardware-agnostic inference and cross-platform support |
| ✅ ONNX Quantization (INT8)            | Further model compression with minor accuracy loss |
| ✅ `torch.compile()` (PyTorch 2.x)     | Compiler-based backend acceleration |
| ✅ TorchDynamo + TorchInductor         | Just-in-time graph capture and compiler backend |
| 📦 Model Size, Accuracy & Speed Report | Analyze trade-offs visually with an inference summary |

---
