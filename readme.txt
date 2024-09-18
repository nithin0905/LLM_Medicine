# Fine-Tuning LLaMA-2 for Medical Term Analysis

This project fine-tunes the **LLaMA-2** model using **LoRA** and **4-bit quantization** for generating accurate medical term explanations. It leverages a **Wikipedia-sourced medical terms dataset** and optimizes training for efficient memory usage.

## Key Features
- **Model**: LLaMA-2 with LoRA adaptation.
- **Quantization**: 4-bit NF4, improving memory efficiency.
- **Data**: 500,000+ medical terms from Wikipedia.
- **Optimization**: FP16 precision, cosine learning rate scheduling, gradient checkpointing.

## Training Setup
- **Batch Size**: 4
- **Learning Rate**: 2e-4
- **Epochs**: 10