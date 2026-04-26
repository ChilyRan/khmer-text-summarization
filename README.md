# 🇰🇭 Khmer Text Summarization

Fine-tuning large language models for **Khmer text summarization** using QLoRA (4-bit) with [Unsloth](https://github.com/unslothai/unsloth).

## 📌 Overview

This project fine-tunes 3 models on 2 different Khmer datasets and evaluates them using ROUGE scores.

| Model | Base Model |
|-------|-----------|
| Gemma | unsloth/gemma-2b-bnb-4bit |
| LLaMA | unsloth/Llama-3.2-3B-Instruct-bnb-4bit |
| Qwen | unsloth/Qwen2.5-7B-Instruct-bnb-4bit |

| Dataset | Description |
|---------|-------------|
| Raw (Title-based) | Real Khmer news articles |
| Synthetic | 2000 synthetic Khmer samples |

---

## 📂 Project Structure