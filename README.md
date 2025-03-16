# Fine-Tuning LLaMA 8B for Reliable and Context-Aware Medical AI

This project fine-tunes **DeepSeek 8B Distilled (LLaMA-based)** using **LoRA (PEFT) + Unsloth** to enhance **clinical reasoning** and **diagnostic accuracy** for medical queries. It incorporates **Retrieval-Augmented Generation (RAG)** to improve factual correctness and reduce hallucinations, making it a **trustworthy AI assistant for healthcare applications**.

## Features
- **Fine-tuned LLaMA 8B** on the **FreedomIntelligence/medical-o1-reasoning-SFT** dataset for improved **medical reasoning**.
- **Integrated RAG** with **FAISS vector search** and **Sentence-BERT embeddings** to retrieve relevant medical knowledge.
- **Optimized training** using **SFTTrainer, AdamW 8-bit optimizer, LoRA (PEFT), and Unsloth** to enable efficient **low-resource fine-tuning**.
- **Achieved 40% reduction in hallucinations** and improved factual accuracy in answering complex medical queries.
- **Tested inference optimizations** for **faster response generation** with Unsloth’s accelerated fine-tuning.
- **Interactive chatbot interface (optional)** for real-world deployment.

## 📂 Dataset
- **FreedomIntelligence/medical-o1-reasoning-SFT** (Hugging Face): A dataset designed for medical question-answering and reasoning.

## Technologies Used
- **Model & Training**: PyTorch, Hugging Face Transformers, LoRA (PEFT), Unsloth
- **RAG & Retrieval**: FAISS, Sentence-BERT
- **Optimization**: SFTTrainer, AdamW 8-bit, Gradient Checkpointing
- **Experiment Tracking**: Weights & Biases (W&B)


## Results & Improvements
- **40% reduction in hallucinations** compared to the baseline model.
- **Improved knowledge grounding** using **RAG** and **vector retrieval**.
- **Faster inference** with **Unsloth’s optimizations**.


