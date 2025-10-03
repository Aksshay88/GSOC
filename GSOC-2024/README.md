# GSOC 2024: Desktop Chat Bot Application with OpenVINO

This repository contains the project for the Google Summer of Code 2024. The project is a desktop chatbot application that operates offline and utilizes the OpenVINO toolkit for optimized performance of NLP models.

## About the Project

The goal of this project is to create a versatile and efficient desktop chatbot that provides a seamless conversational experience without needing an internet connection. By integrating advanced NLP models and leveraging the OpenVINO toolkit, the application will deliver fast and reliable responses on resource-constrained devices.

## The Power of OpenVINO

The Intel Distribution of OpenVINO (Open Visual Inference & Neural Network Optimization) toolkit is a comprehensive suite of tools for optimizing and deploying AI inference. It helps developers to increase the performance of deep learning models, reduce resource demands, and simplify the deployment process.

### Key Components and Functionalities of the OpenVINO Python toolkit:

*   **OpenVINO Runtime (Python API):** The core component for loading, compiling, and executing optimized deep learning models in Python.
*   **Model Optimizer:** A tool to convert models from various frameworks (PyTorch, TensorFlow, ONNX) into the OpenVINO Intermediate Representation (IR) format.
*   **Post-Training Optimization Toolkit (POT):** Provides methods for post-training quantization to reduce model size and improve inference performance without retraining.
*   **Neural Network Compression Framework (NNCF):** A library for advanced model compression techniques like quantization-aware training and pruning.
*   **Optimum Intel:** Integrates OpenVINO with Hugging Face Transformers and Diffusers for seamless deployment of models from the Hugging Face Hub.
*   **Open Model Zoo:** A collection of pre-trained models and pre-converted OpenVINO IR models.
*   **OpenVINO Samples:** Python-based examples demonstrating the use of the OpenVINO API for various tasks.

### Benefits of using the OpenVINO Python toolkit:

*   **Performance Optimization:** Accelerates deep learning inference on Intel CPUs, GPUs, and NPUs.
*   **Framework Agnostic:** Supports models from a wide range of deep learning frameworks.
*   **Simplified Deployment:** Streamlines the process from training to inference.
*   **Reduced Resource Demands:** Enables efficient deployment on edge devices.
*   **Active Community and Ecosystem:** Benefits from ongoing development and community support.

## OpenVINO Workflow

Here is a typical workflow for using the OpenVINO toolkit in a deep learning project:

```
1. Train a Model
   (using TensorFlow, PyTorch, etc.)
      |
      v
2. Convert the Model to OpenVINO IR format
   (using Model Optimizer)
      |
      v
3. Optimize the Model (Optional)
   (using POT or NNCF for quantization)
      |
      v
4. Deploy the Model for Inference
   (using OpenVINO Runtime)
      |
      v
5. Application
   (Desktop Chatbot)
```

## Project Timeline

| Weeks   | Task                                        |
| ------- | ------------------------------------------- |
| 1-2     | Research and Setup (Electron, OpenVINO)     |
| 3-4     | UI Design and Implementation                |
| 5-6     | NLP Integration and Testing                 |
| 7-8     | OpenVINO Integration and Performance Testing|
| 9-10    | Error Handling and Testing                  |
| 11-12   | Documentation and Finalization              |
