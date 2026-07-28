# Sanskrit Phi-4 Fine-Tuning

A project for fine-tuning Microsoft's **Phi-4** language model on a Sanskrit dataset using **LoRA (Low-Rank Adaptation)**. This repository contains the complete training notebook, dataset, evaluation outputs, trained models, and generated predictions.

---

## 📖 Project Overview

This project demonstrates the end-to-end workflow for adapting a pre-trained Phi-4 language model to Sanskrit using parameter-efficient fine-tuning techniques.

The workflow includes:

- Dataset preprocessing
- Fine-tuning using LoRA
- Model evaluation
- Text generation
- Saving trained checkpoints and final models

---

## 📂 Repository Structure

```text
Sanskrit_Phi4_Finetuning/
│
├── dataset/
├── evaluation/
├── models/
├── outputs/
├── Anustubh_Experiment.ipynb
├── requirements.txt
└── README.md
```

---

## 📁 Repository Contents

### 📓 Anustubh_Experiment.ipynb

The primary notebook containing the complete workflow:

- Loading the Sanskrit dataset
- Data preprocessing
- Tokenization
- LoRA configuration
- Phi-4 fine-tuning
- Model evaluation
- Text generation
- Saving trained models

### 📂 dataset/

Contains the Sanskrit dataset used for training and evaluation.

### 📂 evaluation/

Stores evaluation scripts and generated evaluation results for the fine-tuned model.

### 📂 models/

Contains trained LoRA adapters, checkpoints, and exported model files.

### 📂 outputs/

Stores generated outputs such as predictions, logs, and intermediate results produced during training and inference.

---

## 🚀 Features

- Fine-tuning Microsoft's Phi-4
- LoRA (Parameter-Efficient Fine-Tuning)
- Sanskrit language dataset
- Evaluation pipeline
- Model checkpointing
- Text generation and inference
- Reproducible notebook workflow

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (LoRA)
- Accelerate
- TensorBoard
- Jupyter Notebook

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/BhuviSinghal04/Sanskrit_Phi4_Finetuning.git
cd Sanskrit_Phi4_Finetuning
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Launch the notebook:

```bash
jupyter notebook Anustubh_Experiment.ipynb
```

Run the notebook cells sequentially to:

1. Load the dataset
2. Configure the Phi-4 model
3. Fine-tune using LoRA
4. Evaluate the model
5. Generate Sanskrit text

---

## 📊 Results

The repository contains:

- Fine-tuned Phi-4 model
- Training outputs
- Evaluation results
- Generated predictions
- Saved checkpoints

---

## 📄 License

This project is intended for educational and research purposes.

---

## 👤 Author

**Bhuvi Singhal**

GitHub: https://github.com/BhuviSinghal04
