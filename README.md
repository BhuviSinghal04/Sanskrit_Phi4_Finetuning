# Sanskrit Phi-4 Fine-Tuning

A project for fine-tuning Microsoft's **Phi-4** language model on a Sanskrit dataset using **LoRA (Low-Rank Adaptation)** for efficient parameter-efficient training.

## 📌 Project Overview

This repository contains the complete pipeline for:

- Dataset preprocessing and cleaning
- Training/validation/test dataset creation
- LoRA fine-tuning of the Phi-4 model
- Model checkpointing
- Evaluation and inference
- Comparison between baseline and fine-tuned model outputs

---

## 📂 Project Structure

```
Sanskrit_Phi4_Finetuning/
│
├── configs/                     # Configuration files
├── dataset/                     # Original dataset
├── evaluation/                  # Evaluation scripts
├── logs/                        # TensorBoard logs
├── models/                      # LoRA checkpoints & trained models
├── notebooks/                   # Jupyter notebooks
├── outputs/
│   ├── dataset_splits/
│   ├── generation_results/
│   └── config/
├── requirements.txt
└── README.md
```

---

## ✨ Features

- Dataset cleaning and preprocessing
- Automatic train/validation/test split
- Parameter-efficient fine-tuning using LoRA
- Model checkpoint saving
- TensorBoard logging
- Baseline vs Fine-tuned evaluation
- CSV export of generated outputs

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (LoRA)
- Accelerate
- TensorBoard
- Pandas

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/<your-username>/Sanskrit_Phi4_Finetuning.git
cd Sanskrit_Phi4_Finetuning
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## 📊 Dataset

The project uses a Sanskrit dataset that undergoes:

- Duplicate removal
- Data validation
- Cleaning
- Train/Validation/Test split

Processed datasets are stored in:

```
outputs/dataset_splits/
```

---

## 🧠 Training

The project fine-tunes the **Phi-4** model using **LoRA**, reducing GPU memory usage while maintaining strong performance.

Training outputs include:

- LoRA adapters
- Checkpoints
- TensorBoard logs
- Configuration files

---

## 📈 Evaluation

Evaluation scripts are located in:

```
evaluation/
```

Generated outputs are saved under:

```
outputs/generation_results/
```

These include comparisons between:

- Baseline model
- Fine-tuned model
- Zero-shot generation
- Three-shot generation

---

## 📁 Outputs

The repository stores:

- Trained LoRA adapters
- Checkpoints
- Dataset splits
- Evaluation results
- Training configuration
- TensorBoard logs

---

## 📦 Requirements

Install all required packages using:

```bash
pip install -r requirements.txt
```

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is intended for educational and research purposes.

---

## 👤 Author

**Bhuvi Singhal**

GitHub: https://github.com/BhuviSinghal04
