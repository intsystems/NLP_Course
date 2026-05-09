# Week 9: Efficient Inference with Quantization, Distillation Methods, Launch
 
## 📌 Briefly
> Post-training quantization (PTQ): GPTQ
> Quantization data types: INT8, INT4, FP8, NF4  
> Quantization-aware training (QAT)  
> Knowledge distillation 
> Speculative decoding and inference optimization  
> Serving architectures: batching, KV cache, PagedAttention  
 
---
 
## 📚 Additional Materials
 
### Post-Training Quantization
- 📄 [GPTQ](https://arxiv.org/abs/2210.17323) — accurate PTQ for generative pre-trained transformers
- 📄 [AWQ](https://arxiv.org/abs/2306.00978) — activation-aware weight quantization
- 📄 [LLM.int8()](https://arxiv.org/abs/2208.07339) — 8-bit matrix multiplication for transformers (bitsandbytes)
- 📄 [GGUF / llama.cpp](https://github.com/ggerganov/llama.cpp) — CPU-friendly quantization formats
### Quantization-Aware Training
- 📄 [LLM-QAT](https://arxiv.org/abs/2305.17888) — data-free quantization-aware training
- 📄 [BitNet](https://arxiv.org/abs/2310.11453) — 1-bit LLMs for large language models
- 📄 [BitNet b1.58](https://arxiv.org/abs/2402.17764) — every weight is -1, 0, or +1
### Knowledge Distillation
- 📄 [Knowledge Distillation (Hinton et al., 2015)](https://arxiv.org/abs/1503.02531) — original paper, soft targets
- 📄 [DistilBERT](https://arxiv.org/abs/1910.01108) — distilling BERT, 40% smaller, 60% faster
- 📄 [MiniLLM](https://arxiv.org/abs/2306.08543) — distillation for generative LLMs via reverse KL
- 📄 [DistiLlama / Distilling Step-by-Step](https://arxiv.org/abs/2305.02301) — distillation with chain-of-thought rationales
### Inference Optimization & Frameworks
- 📄 [vLLM / PagedAttention](https://arxiv.org/abs/2309.06180) — efficient KV cache management [HIGHLY RECOMMENDED]
- 📄 [Speculative Decoding](https://arxiv.org/abs/2211.17192) — faster inference with draft models
- 📄 [FlashAttention-2](https://arxiv.org/abs/2307.08691) — fast and memory-efficient exact attention
- 📄 [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) — NVIDIA inference optimization toolkit
- 🤗 [HF Text Generation Inference (TGI)](https://github.com/huggingface/text-generation-inference) — production inference server
- 🤗 [Quantization Concepts (HuggingFace)](https://huggingface.co/docs/transformers/quantization/overview) — practical overview [HIGHLY RECOMMENDED]
 
