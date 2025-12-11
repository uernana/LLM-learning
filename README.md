# LLM-learning
This repository focuses on basic concepts and components in a Large Language Model. Roadmap to Learn LLMs (from Zero → Full Stack LLM Engineer):
Includes foundations → transformers → fine-tuning → agents → RAG → deployment.

## Reference
LLMs from scratch: https://github.com/rasbt/LLMs-from-scratch/tree/main

## Foundations

1. Math + Probability Basics

+ Vectors, matrices

+ Dot product, projections

+ Softmax, cross-entropy loss

+ Probability distributions

2. Python for ML

+ NumPy

+ PyTorch basics

+ Data loading, tensor operations

## Deep Learning Fundamentals
3. Neural Networks

+ Backpropagation

+ Activation functions

+ Optimization (SGD, Adam)

4. Sequence Modeling

+ RNN, GRU, LSTM

+ Why they fail (long-term dependencies → vanishing gradient)

5. Attention Mechanism (key concept!)

+ Self-attention (Q, K, V)

+ Multi-head attention

+ Positional embeddings

## Transformers Mastery
1. Transformer
2. Implement a mini Transformer

## Modern LLM Architectures
1. Popular Models

+ GPT-2 → decode-only

+ GPT-3 → scaling laws

+ Llama 2/3 → Grouped Query Attention (GQA)

+ Mistral → sliding window attention

+ DeepSeek-V2 → MoE

+ Qwen → multilingual optimizations

2.  Understand Efficiency Methods

+ Rotary embeddings (RoPE)

+ KV-cache

+ FlashAttention

+ Grouped Query Attention

+ Sliding window attention

+ MoE (Mixture of Experts)

+ Quantization (INT8, GPTQ, GGUF, AWQ)

## Fine-tuning & Training

1. Supervised Fine-tuning (SFT)

+ HuggingFace transformers

+ PEFT (LoRA)

+ QLoRA (4-bit training)

2. RLHF (Reinforcement Learning from Human Feedback)

+ Reward models

+ PPO, DPO

+ Safety alignment

## LLM Applications

1. Retrieval-Augmented Generation (RAG)

+ Chunking strategies

+ Embedding models (BGE, nomic, instructor)

+ Vector DBs (Qdrant, Milvus, FAISS)

2. Agents & Tool Use

+ Call external tools

+ Use function calling

+ Plan & reason (ReAct, MRKL, AutoGPT-style loops)

3. Multimodal LLMs

+ Vision transformers (ViT)

+ How LLaVA works (attention projection)

+ Audio models (Whisper, GPT-4o-mini)

  ## Scaling & Deployment
1. Inference & Optimization

+ vLLM

+ Ollama

+ LMDeploy

+ llama.cpp

+ TensorRT-LLM

2. Hosting & Serving

+ GPU servers (RunPod, LambdaLabs)

+ Kubernetes scaling

+ API gateways

+ Caching strategies

## Update knowledge
