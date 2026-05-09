# Week 10: Information Retrieval & Retrieval-Augmented Generation

## 📌 Briefly

> Why LLMs hallucinate and why external memory helps (calibration gap, static knowledge) \
> Classical IR: TF-IDF, BM25, inverted index, ranking metrics \
> Dense Retrieval: Cross-encoder, Bi-encoder (DPR), ColBERT \
> Training retrievers: triplet loss, hard negatives, ANN search (FAISS) \
> Hybrid Retrieval and Reciprocal Rank Fusion \
> RAG: Joint vs Modular, Lost in the Middle, relevance gap \
> Advanced RAG: query rewriting (HyDE), chunking, reranking, context compression \
> Frontier: Self-RAG, GraphRAG, Agentic RAG \
> Evaluation: RAGAS, faithfulness, answer relevance

---

## 📚 Additional Materials

### Foundations & Hallucinations
- 📄 [Hallucinating Law: Legal Mistakes with LLMs](https://arxiv.org/abs/2401.01301) — Dahl et al., 2024 (the 69-88% number)
- 📄 [LLMs Know More Than They Show](https://arxiv.org/abs/2410.02707) — Jiang et al., 2024 (knowledge in parameters but not retrieved)
- 📄 [Relying on the Unreliable: Calibration Gap](https://arxiv.org/abs/2401.13835) — Zhou et al., 2024

### Classical IR
- 📖 [Speech and Language Processing — Ch. 14: Information Retrieval](https://web.stanford.edu/~jurafsky/slp3/14.pdf) — Jurafsky & Martin (canonical reference)
- 📄 [Okapi BM25: A Non-Binary Model](https://www.staff.city.ac.uk/~sbrp622/papers/foundations_bm25_review.pdf) — Robertson & Zaragoza (the BM25 bible)
- 📄 [The Vocabulary Problem in Human-System Communication](https://dl.acm.org/doi/10.1145/32206.32212) — Furnas et al., 1987

### Dense Retrieval
- 📄 [Dense Passage Retrieval (DPR)](https://arxiv.org/abs/2004.04906) — Karpukhin et al., 2020
- 📄 [ColBERT: Efficient Passage Search via Late Interaction](https://arxiv.org/abs/2004.12832) — Khattab & Zaharia, 2020
- 📄 [ColBERTv2: Effective and Efficient Retrieval](https://arxiv.org/abs/2112.01488) — Santhanam et al., 2022
- 📄 [FAISS: Billion-Scale Similarity Search](https://arxiv.org/abs/1702.08734) — Johnson et al., 2017
- 📄 [Relevance-Guided Supervision for OpenQA with ColBERT](https://arxiv.org/abs/2007.00814) — Khattab et al., 2021

### RAG
- 📄 [Retrieval-Augmented Generation for Knowledge-Intensive NLP](https://arxiv.org/abs/2005.11401) — Lewis et al., 2020 (the original RAG paper)
- 📄 [Reading Wikipedia to Answer Open-Domain Questions](https://arxiv.org/abs/1704.00051) — Chen et al., 2017 (DrQA, retriever+reader)
- 📄 [Lost in the Middle: How LMs Use Long Contexts](https://arxiv.org/abs/2307.03172) — Liu et al., 2023
- 📄 [Enabling Large Language Models to Generate Text with Citations](https://arxiv.org/abs/2305.14627) — Gao et al., 2023

### Advanced RAG
- 📄 [Precise Zero-Shot Dense Retrieval without Relevance Labels (HyDE)](https://arxiv.org/abs/2212.10496) — Gao et al., 2022
- 🏢 [Anthropic Contextual Retrieval](https://www.anthropic.com/news/contextual-retrieval) — BM25 + contextualized embeddings + reranker [HIGHLY RECOMMENDED]
- 📄 [LongLLMLingua: Prompt Compression for Long Contexts](https://arxiv.org/abs/2310.06839) — Jiang et al., 2023
- 📄 [xRAG: Extreme Context Compression](https://arxiv.org/abs/2405.13792) — Cheng et al., 2024
- 📄 [Reciprocal Rank Fusion](https://plg.uwaterloo.ca/~gvcormac/cormacksigir09-rrf.pdf) — Cormack et al., 2009

### Frontier
- 📄 [Self-RAG: Learning to Retrieve, Generate, and Critique](https://arxiv.org/abs/2310.11511) — Asai et al., 2023
- 📄 [GraphRAG: From Local to Global](https://arxiv.org/abs/2404.16130) — Microsoft Research, 2024
- 🏢 [GraphRAG GitHub](https://github.com/microsoft/graphrag) — official Microsoft implementation
- 📄 [Survey on Agentic RAG](https://arxiv.org/abs/2501.09136) — Singh et al., 2025

### Evaluation
- 📄 [RAGAS: Automated Evaluation of RAG](https://arxiv.org/abs/2309.15217) — Es et al., 2023
- 🛠 [RAGAS Framework](https://github.com/explodinggradients/ragas) — open-source eval
- 🛠 [DeepEval](https://github.com/confident-ai/deepeval) — LLM-as-a-judge framework
- 📄 [BEIR Benchmark](https://arxiv.org/abs/2104.08663) — Thakur et al., 2021 (zero-shot retrieval eval)

### Practical / Hands-on
- 🤗 [Sentence-Transformers](https://www.sbert.net/) — easiest path to dense retrieval
- 📦 [rank_bm25](https://github.com/dorianbrown/rank_bm25) — BM25 in 30 lines of Python
- 🛠 [LlamaIndex](https://docs.llamaindex.ai/) — production RAG framework
- 🛠 [LangChain RAG](https://python.langchain.com/docs/tutorials/rag/) — alternative framework
- 📝 [Pinecone Learning Center](https://www.pinecone.io/learn/) — practical RAG tutorials [HIGHLY RECOMMENDED]