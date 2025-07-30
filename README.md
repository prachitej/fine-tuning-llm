# LLM Fine-Tuning for German-French Translation

This project demonstrates fine-tuning a large language model for German-French translation, including synthetic data generation and performance evaluation.

## Project Overview

### Key Objectives:

- Fine-tune a pre-trained LLM for translation tasks
- Generate synthetic training data using larger models
- Evaluate different fine-tuning approaches
- Create an optimized translation model

## Project Structure

project/
├── fine_tuning.ipynb          # Main implementation notebook
├── data/                      # All dataset files
│   ├── original/              # Original benchmark data
│   │   ├── train_dataset_a.json
│   │   ├── val_dataset_a.json
│   │   └── test_dataset_a.json
│   ├── synthetic/             # Generated data
│   │   └── dataset_b.json
│   └── processed/            # Combined datasets
│       └── dataset_c.json
├── app/                       # Interface implementation
│   └── translation_ui.py      # Gradio app file
└── README.md                  # Project documentation
