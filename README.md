# 🦙 Fine-Tuning LLaMA Model

This repository contains Jupyter notebooks for fine-tuning [Meta's LLaMA](https://ai.meta.com/llama/) model using Hugging Face Transformers. The goal is to explore and experiment with adapting LLaMA for downstream tasks using custom datasets.


## 🔧 Features

- Model loading via Hugging Face Transformers  
- Dataset preprocessing  
- LoRA-based (Low-Rank Adaptation) fine-tuning support  
- Training with PEFT (Parameter-Efficient Fine-Tuning)  
- Use of `transformers`, `datasets`, `peft`, and `accelerate` libraries  
- GPU-accelerated training using Colab or local setups  

## 🚀 Quickstart

### 1. Clone the Repository

```bash
git clone https://github.com/shruti-29/GenAI.git
cd GenAI
```

### 2. Install Requirements

Create a virtual environment (optional) and install dependencies:

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install transformers datasets peft accelerate bitsandbytes
```

### 3. Run the Notebook

Open any notebook in Jupyter or Colab:

```bash
jupyter notebook
```

Alternatively, you can use Google Colab for quick experiments.

## 🧠 Notes

- You will need access to LLaMA models through Hugging Face (some models may require application/request).  
- Training can be GPU-intensive. For large models like LLaMA 3B, use Colab Pro or a local GPU with sufficient VRAM (16GB+ recommended).
