# Week 11: AI Agents 

## 📌 Briefly

> Origins of the Agent concept: from cybernetics and Society of Mind to RL and LLM-based agents \
> What is an LLM Agent: brain + memory + tools + environment \
> Core agentic patterns: Reflection, Tool Use, ReAct, Planning, Multi-agent \
> Types of memory: Short-term, Long-term, Episodic, Semantic \
> Agent properties: Reasoning, Reflection, Domain Knowledge, Role, Autonomy, Memory \
> Training pipeline: Pretraining → SFT on trajectories → RLHF → Tool-specific FT \
> Benchmarks: SWE-bench, GAIA, AgentBench, WebArena, MLE-Bench \
> Frameworks: LangChain, LangGraph, AutoGPT, MCP \
> Hands-on: building a Go testing agent

---

## 📚 Additional Materials

### Foundations & History
- 📖 [Society of Mind](https://en.wikipedia.org/wiki/Society_of_Mind) — Marvin Minsky, 1986 (intelligence as interacting agents)
- 📄 [Intelligent Agents: Theory and Practice](https://www.cs.ox.ac.uk/people/michael.wooldridge/pubs/ker95/ker95-html.html) — Wooldridge & Jennings, 1995 (formal definition)
- 📖 [Reinforcement Learning: An Introduction](http://incompleteideas.net/book/the-book-2nd.html) — Sutton & Barto (the RL bible)
- 🏢 [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) — Lilian Weng's seminal blog post [HIGHLY RECOMMENDED]

### Key Papers — Agent Patterns
- 📄 [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) — Yao et al., NeurIPS 2022
- 📄 [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366) — Shinn et al., NeurIPS 2023
- 📄 [Chain-of-Thought Prompting](https://arxiv.org/abs/2201.11903) — Wei et al., 2022 (foundation for reasoning)
- 📄 [Tree of Thoughts](https://arxiv.org/abs/2305.10601) — Yao et al., 2023 (deliberate problem solving)
- 📄 [Self-Refine: Iterative Refinement with Self-Feedback](https://arxiv.org/abs/2303.17651) — Madaan et al., 2023 (reflection pattern)

### Tool Use & Function Calling
- 📄 [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761) — Schick et al., 2023
- 📄 [Tool Learning with Foundation Models](https://arxiv.org/abs/2304.08354) — Qin et al., 2023 (taxonomy of tools)
- 📄 [Gorilla: Large Language Model Connected with Massive APIs](https://arxiv.org/abs/2305.15334) — Patil et al., 2023
- 🏢 [Anthropic: Tool Use Guide](https://docs.anthropic.com/en/docs/build-with-claude/tool-use) — official function calling docs
- 🏢 [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) — open standard for tool integration

### Memory
- 📄 [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560) — Packer et al., 2023
- 📄 [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) — Park et al., 2023 (episodic memory in action)
- 📄 [A Survey on the Memory Mechanism of LLM-based Agents](https://arxiv.org/abs/2404.13501) — Zhang et al., 2024

### Multi-Agent & Planning
- 📄 [AutoGen: Multi-Agent Conversation Framework](https://arxiv.org/abs/2308.08155) — Wu et al., Microsoft, 2023
- 📄 [MetaGPT: Meta Programming for Multi-Agent Collaboration](https://arxiv.org/abs/2308.00352) — Hong et al., 2023
- 📄 [Voyager: Open-Ended Embodied Agent with LLMs](https://arxiv.org/abs/2305.16291) — Wang et al., 2023 (Minecraft agent)

### Training Agents
- 📄 [FireAct: Toward Language Agent Fine-tuning](https://arxiv.org/abs/2310.05915) — Chen et al., 2023
- 📄 [AgentTuning: Enabling Generalized Agent Abilities for LLMs](https://arxiv.org/abs/2310.12823) — Zeng et al., 2023
- 📄 [Direct Preference Optimization (DPO)](https://arxiv.org/abs/2305.18290) — Rafailov et al., 2023

### Benchmarks
- 📄 [SWE-bench: Can LLMs Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770) — Jimenez et al., 2024
- 🏆 [SWE-bench Leaderboard](https://www.swebench.com/) — current SOTA on real GitHub bug fixing
- 📄 [GAIA: A Benchmark for General AI Assistants](https://arxiv.org/abs/2311.12983) — Mialon et al., Meta, 2023
- 📄 [AgentBench: Evaluating LLMs as Agents](https://arxiv.org/abs/2308.03688) — Liu et al., 2023
- 📄 [WebArena: Realistic Web Environment for Autonomous Agents](https://arxiv.org/abs/2307.13854) — Zhou et al., 2023
- 📄 [OSWorld: Benchmarking Multimodal Agents](https://arxiv.org/abs/2404.07972) — Xie et al., 2024
- 📄 [MLE-Bench: Evaluating ML Engineering Agents](https://arxiv.org/abs/2410.07095) — OpenAI, 2024

### Frameworks (Hands-on)
- 🛠 [LangChain](https://python.langchain.com/docs/concepts/agents/) — agents documentation
- 🛠 [LangGraph](https://langchain-ai.github.io/langgraph/) — graph-based agent orchestration
- 🛠 [AutoGen](https://microsoft.github.io/autogen/) — Microsoft's multi-agent framework
- 🛠 [CrewAI](https://docs.crewai.com/) — role-based multi-agent framework
- 🛠 [Smolagents](https://github.com/huggingface/smolagents) — minimalist agent library by HuggingFace
- 🛠 [Claude Agent SDK](https://docs.claude.com/en/api/agent-sdk) — Anthropic's agent building toolkit

### Practical Reading
- 🏢 [Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) — Anthropic's design principles [HIGHLY RECOMMENDED]
- 🏢 [The Rise of Agentic AI](https://www.deeplearning.ai/the-batch/issue-241/) — Andrew Ng on agentic workflows