🚀 Quantized LLM Project
📌 Overview

This project demonstrates quantization of a large language model (LLM) to reduce memory usage and improve inference speed, making it possible to run on resource-constrained devices (e.g., laptops or mobile devices).

The project also supports supervised fine-tuning (SFT) with LoRA adapters and provides an example training configuration.

✨ Features

🔹 Model quantization with bitsandbytes

🔹 LoRA-based fine-tuning (peft)

🔹 Supervised fine-tuning with TRL’s SFTTrainer

🔹 Support for GPU training (device_map={"": 0})

🔹 Configurable hyperparameters (warmup ratio, sequence length, logging steps, etc.)

⚙️ Installation

Clone the repository

git clone https://github.com/yourusername/quantization-project.git
cd quantization-project


Create environment & install dependencies

pip install -r requirements.txt


Key dependencies

torch
transformers
trl==0.4.5
peft
bitsandbytes
datasets
accelerate
