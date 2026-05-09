# Week 8: 5D Parallelism, Mixture of Experts
 
## 📌 Briefly
> 5D Parallelism: Data, Tensor, Pipeline, Sequence, Expert  
> Tensor Parallelism and Megatron-LM  
> Pipeline Parallelism: GPipe, PipeDream, micro-batches  
> Sequence Parallelism for long-context models  
> Mixture of Experts (MoE): architecture and routing  
> Sparse vs Dense models: trade-offs and use cases  
> Load balancing and auxiliary loss  
> Expert Parallelism and All-to-All communication  
 
---
 
## 📚 Additional Materials
 
### 5D Parallelism & Scaling
- 📄 [Megatron-LM](https://arxiv.org/abs/1909.08053) — tensor and pipeline parallelism
- 📄 [Megatron-LM v3](https://arxiv.org/abs/2205.05198) — sequence parallelism + selective recomputation
- 📄 [GPipe](https://arxiv.org/abs/1811.06965) — pipeline parallelism with micro-batches
- 📄 [PipeDream](https://arxiv.org/abs/1806.03377) — async pipeline parallelism
- 📄 [DeepSpeed Ulysses](https://arxiv.org/abs/2309.14509) — sequence parallelism for long contexts
### Mixture of Experts
- 📄 [Outrageously Large Neural Networks (Shazeer et al., 2017)](https://arxiv.org/abs/1701.06538) — original sparse MoE + Noisy Top-k Gating
- 📄 [GShard](https://arxiv.org/abs/2006.16668) — scaling transformers to 600B+ with MoE
- 📄 [Switch Transformer](https://arxiv.org/abs/2101.03961) — simplified Top-1 routing, 1.6T parameters
- 📄 [ST-MoE](https://arxiv.org/abs/2202.08906) — stable and transferable MoE, router z-loss
- 📄 [Mixtral 8x7B](https://arxiv.org/abs/2401.04088) — open-weight sparse MoE, top-2 routing
- 📄 [DeepSeek-V2](https://arxiv.org/abs/2405.04434) — shared + routed experts, MLA attention
- 📄 [DeepSeek-V3](https://arxiv.org/abs/2412.19437) — 671B total / 37B active, auxiliary-loss-free balancing
- 🤗 [Mixture of Experts Explained (HuggingFace)](https://huggingface.co/blog/moe) — deep-dive blog post [HIGHLY RECOMMENDED]
- 📊 [A Visual Guide to MoE (Maarten Grootendorst)](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-mixture-of-experts) — 50+ visualizations [HIGHLY RECOMMENDED]
