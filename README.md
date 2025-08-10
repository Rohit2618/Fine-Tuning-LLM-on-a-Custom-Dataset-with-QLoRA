# Fine-Tuning an LLM on a Custom Dataset with QLoRA

This repository contains a Jupyter Notebook demonstrating how to fine-tune a large language model (LLM) using QLoRA. It walks through setting up the environment, preparing a dataset, applying quantization for efficiency, and training the model.

## Contents
- `Fine_Tuning_LLM_on_a_Custom_Dataset_with_QLoRA.ipynb` – Full implementation with code, explanations, and results.

## What You’ll Learn
- How QLoRA works and why it’s used for parameter-efficient fine-tuning.
- Preparing and formatting a custom dataset for LLM training.
- Training steps and configuration.
- Running inference with the fine-tuned model.

## Requirements
Install the necessary dependencies before running the notebook:
```bash
pip install transformers datasets peft bitsandbytes accelerate
