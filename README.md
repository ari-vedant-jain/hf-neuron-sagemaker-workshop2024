# Hugging Face Neuron on SageMaker Workshop 2024

## Overview
This repository contains code and materials for the **Hugging Face Neuron** workshop using **AWS SageMaker**. The goal is to demonstrate how to fine-tune and perform inference with models like TinyLlama and Mistral using AWS infrastructure and Hugging Face libraries optimized for the AWS Neuron SDK.

## Contents
- **01_finetuning_tinyLlama/**: Code for fine-tuning the TinyLlama model on AWS SageMaker.
- **02_inference_mistral/**: Code for running inference with the Mistral model using the Neuron SDK.
- **additional_content/**: Additional resources, scripts, or content related to the workshop.

## Requirements
- **AWS Account**: Ensure you have access to AWS SageMaker services.
- **Neuron SDK**: Installed to work with AWS Inferentia hardware.
- **Hugging Face Transformers**: Required for model fine-tuning and inference.
  
To install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Fine-Tuning TinyLlama
Navigate to the `01_finetuning_tinyLlama` directory and follow the notebook to fine-tune the model on SageMaker.

### Inference with Mistral
In the `02_inference_mistral` directory, run the provided scripts to load the Mistral model and perform inference on SageMaker.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
