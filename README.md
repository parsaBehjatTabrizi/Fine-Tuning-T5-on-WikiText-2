# Fine-Tuning T5 on WikiText-2

This project demonstrates how to **fine-tune the T5 transformer model** on the [WikiText-2 dataset](https://huggingface.co/datasets/wikitext) using the Hugging Face `transformers` library and PyTorch.

---

## 🚀 Features
- Fine-tunes the **T5-small** model on WikiText-2 (language modeling).
- Uses **PyTorch** with GPU acceleration (if available).
- Includes a **training loop** with validation.
- Saves the trained model & tokenizer for later use.
- Provides a **text generation example** with a custom prompt.

---

## 📦 Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/t5-wikitext-finetune.git
cd t5-wikitext-finetune
pip install -r requirements.txt
