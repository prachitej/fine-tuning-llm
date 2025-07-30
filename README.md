# LLM Fine-Tuning for German-French Translation

This project demonstrates fine-tuning a large language model for German-French translation, including synthetic data generation and performance evaluation.

## Project Overview

### Key Objectives:

- Fine-tune a pre-trained LLM for translation tasks
- Generate synthetic training data using larger models
- Evaluate different fine-tuning approaches
- Create an optimized translation model

## Project Structure
<pre>
project/
├── fine_tuning.ipynb               # Jupyter notebook with implementation
├── data/                           # Dataset files
│   ├── dataset_b.json              # Generated synthetic data
│   ├── dataset_c.json              # Combined dataset of original and synthetic data
│   ├── test_dataset_a.json         # Test data of the original benchmark dataset
│   ├── train_dataset_a.json        # Train data of the original benchmark dataset
│   └── val_dataset_a.json          # Val data of the original benchmark dataset
├── app/                            # Gradio interface
└── README.md
</pre>
