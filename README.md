# 🤖 Awesome AI Agents & Frameworks

A curated collection of the best open-source AI agent frameworks, tools, and resources available on GitHub.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/sushantamishra79/awesome-ai-agents?style=social)](https://github.com/sushantamishra79/awesome-ai-agents)

---

## Table of Contents

- [Agent Frameworks](#agent-frameworks)
- [LLM Orchestration](#llm-orchestration)
- [Multi-Agent Systems](#multi-agent-systems)
- [Autonomous Agents](#autonomous-agents)
- [RAG & Knowledge](#rag--knowledge)
- [Agent Tools & Skills](#agent-tools--skills)
- [Code Agents](#code-agents)
- [Voice & Multimodal Agents](#voice--multimodal-agents)
- [Agent Infrastructure](#agent-infrastructure)
- [Learning Resources](#learning-resources)

---

## Agent Frameworks

| Project | GitHub | Description |
|---------|--------|-------------|
| **LangChain** | [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | The most popular framework for building LLM-powered applications |
| **LangGraph** | [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | Build stateful, multi-actor applications with LLMs as graphs |
| **DeepAgents** | [langchain-ai/deepagents](https://github.com/langchain-ai/deepagents) | LangChain's deep research and planning agents |
| **OpenAI Agents SDK** | [openai/openai-agents-python](https://github.com/openai/openai-agents-python) | OpenAI's official Python SDK for building agents |
| **CrewAI** | [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | Framework for orchestrating role-playing autonomous AI agents |
| **AutoGen** | [microsoft/autogen](https://github.com/microsoft/autogen) | Microsoft's framework for multi-agent conversation |
| **AG2** | [ag2ai/ag2](https://github.com/ag2ai/ag2) | Next-gen AutoGen — open-source AgentOS |
| **Semantic Kernel** | [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) | Microsoft's SDK for integrating AI into apps |
| **Google ADK** | [google/adk-python](https://github.com/google/adk-python) | Google's Agent Development Kit for building AI agents |
| **PydanticAI** | [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | Agent framework from the Pydantic team, type-safe |
| **Mastra** | [mastra-ai/mastra](https://github.com/mastra-ai/mastra) | TypeScript AI agent framework with built-in workflows |
| **Agno** | [agno-agi/agno](https://github.com/agno-agi/agno) | Lightweight library for building multi-modal AI agents |
| **LlamaIndex** | [run-llama/llama_index](https://github.com/run-llama/llama_index) | Data framework for LLM applications (RAG, agents, workflows) |
| **Haystack** | [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | End-to-end NLP framework for building AI pipelines |
| **Smolagents** | [huggingface/smolagents](https://github.com/huggingface/smolagents) | Hugging Face's lightweight agent library |
| **Phidata** | [phidatahq/phidata](https://github.com/phidatahq/phidata) | Build AI agents with memory, knowledge, and tools |
| **Agency Swarm** | [VRSEN/agency-swarm](https://github.com/VRSEN/agency-swarm) | Framework for creating collaborative AI agent swarms |
| **Atomic Agents** | [BrainBlend-AI/atomic-agents](https://github.com/BrainBlend-AI/atomic-agents) | Lightweight, modular framework for building AI agents |

---

## LLM Orchestration

| Project | Stars | Description |
|---------|-------|-------------|
| [LiteLLM](https://github.com/BerriAI/litellm) | 15k+ | Call 100+ LLM APIs in OpenAI format |
| [Ollama](https://github.com/ollama/ollama) | 120k+ | Run LLMs locally with a simple API |
| [vLLM](https://github.com/vllm-project/vllm) | 40k+ | High-throughput LLM serving engine |
| [LocalAI](https://github.com/mudler/LocalAI) | 30k+ | Self-hosted, OpenAI-compatible API |
| [LMStudio](https://github.com/lmstudio-ai) | - | Desktop app to run local LLMs (free) |
| [Guidance](https://github.com/guidance-ai/guidance) | 20k+ | Microsoft's language for controlling LLM generation |
| [DSPy](https://github.com/stanfordnlp/dspy) | 25k+ | Stanford's framework for programming (not prompting) LLMs |
| [LMQL](https://github.com/eth-zurich-nlp/lmql) | 4k+ | Query language for LLMs combining prompting and programming |

---

## Multi-Agent Systems

| Project | Stars | Description |
|---------|-------|-------------|
| [OpenAI Swarm](https://github.com/openai/swarm) | 20k+ | Educational framework for multi-agent orchestration |
| [MetaGPT](https://github.com/geekan/MetaGPT) | 50k+ | Multi-agent framework - assign roles like a software company |
| [ChatDev](https://github.com/OpenBMB/ChatDev) | 30k+ | Virtual software company with AI agents |
| [AutoGen Studio](https://github.com/microsoft/autogen) | 40k+ | Visual multi-agent workflow builder |
| [Camel AI](https://github.com/camel-ai/camel) | 10k+ | Communicative agents for exploring multi-agent behaviors |
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | 20k+ | Autonomous agent for comprehensive online research |
| [Storm](https://github.com/stanford-oval/storm) | 15k+ | Stanford's knowledge curation system with multi-agent research |

---

## Autonomous Agents

| Project | Stars | Description |
|---------|-------|-------------|
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | 170k+ | The original autonomous AI agent |
| [BabyAGI](https://github.com/yoheinakajima/babyagi) | 20k+ | Simple autonomous task-driven agent |
| [AgentGPT](https://github.com/reworkd/AgentGPT) | 33k+ | Deploy autonomous AI agents in the browser |
| [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) | 16k+ | Dev-first open-source autonomous AI framework |
| [OpenDevin](https://github.com/OpenDevin/OpenDevin) | 40k+ | Autonomous AI software engineer |
| [Devon](https://github.com/entropy-research/Devon) | 3k+ | Open-source pair programmer |
| [Devika](https://github.com/stitionai/devika) | 20k+ | Agentic AI software engineer |
| [SWE-Agent](https://github.com/princeton-nlp/SWE-agent) | 15k+ | Princeton's agent that fixes real GitHub issues |

---

## RAG & Knowledge

| Project | Stars | Description |
|---------|-------|-------------|
| [LlamaIndex](https://github.com/run-llama/llama_index) | 40k+ | The leading data framework for RAG |
| [Chroma](https://github.com/chroma-core/chroma) | 18k+ | Open-source embedding database |
| [Weaviate](https://github.com/weaviate/weaviate) | 15k+ | AI-native vector database |
| [Qdrant](https://github.com/qdrant/qdrant) | 22k+ | High-performance vector search engine |
| [Milvus](https://github.com/milvus-io/milvus) | 32k+ | Scalable vector database for AI apps |
| [RAGFlow](https://github.com/infiniflow/ragflow) | 30k+ | Deep document understanding RAG engine |
| [Mem0](https://github.com/mem0ai/mem0) | 25k+ | Memory layer for AI agents (long-term memory) |
| [GraphRAG](https://github.com/microsoft/graphrag) | 25k+ | Microsoft's graph-based RAG approach |
| [Kotaemon](https://github.com/Cinnamon/kotaemon) | 20k+ | Open-source RAG-based document QA tool |

---

## Agent Tools & Skills

| Project | Stars | Description |
|---------|-------|-------------|
| [Composio](https://github.com/ComposioHQ/composio) | 15k+ | Integration platform for AI agents (200+ tools) |
| [LangChain Tools](https://github.com/langchain-ai/langchain/tree/master/libs/community) | - | Extensive collection of agent tools |
| [Browser Use](https://github.com/browser-use/browser-use) | 20k+ | Make AI agents interact with websites |
| [Playwright MCP](https://github.com/anthropics/anthropic-quickstarts) | - | Browser automation for AI agents |
| [E2B](https://github.com/e2b-dev/e2b) | 5k+ | Secure sandboxes for AI agents to run code |
| [Toolformer](https://github.com/lucidrains/toolformer-pytorch) | 2k+ | Implementation of "Toolformer: LLMs Can Teach Themselves to Use Tools" |
| [OpenTools](https://github.com/ShishirPatil/gorilla) | 12k+ | UC Berkeley's Gorilla - LLM connected to APIs |

---

## Code Agents

| Project | Stars | Description |
|---------|-------|-------------|
| [Aider](https://github.com/paul-gauthier/aider) | 25k+ | AI pair programming in your terminal |
| [Continue](https://github.com/continuedev/continue) | 20k+ | Open-source AI code assistant (VS Code/JetBrains) |
| [Tabby](https://github.com/TabbyML/tabby) | 25k+ | Self-hosted AI coding assistant |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 45k+ | AI-powered software development agents |
| [Cline](https://github.com/cline/cline) | 20k+ | Autonomous coding agent for VS Code |
| [GPT Engineer](https://github.com/gpt-engineer-org/gpt-engineer) | 55k+ | Specify what you want - AI builds it |
| [Sweep](https://github.com/sweepai/sweep) | 8k+ | AI-powered junior developer for GitHub |
| [Mentat](https://github.com/AbanteAI/mentat) | 3k+ | AI coding assistant that works with your codebase |

---

## Voice & Multimodal Agents

| Project | Stars | Description |
|---------|-------|-------------|
| [Whisper](https://github.com/openai/whisper) | 75k+ | OpenAI's speech recognition model |
| [Bark](https://github.com/suno-ai/bark) | 38k+ | Text-to-speech model by Suno |
| [Coqui TTS](https://github.com/coqui-ai/TTS) | 36k+ | Deep learning toolkit for text-to-speech |
| [LLaVA](https://github.com/haotian-liu/LLaVA) | 22k+ | Large language and vision assistant |
| [MiniGPT-4](https://github.com/Vision-CAIR/MiniGPT-4) | 26k+ | Multimodal GPT-4 like capabilities |
| [AudioGPT](https://github.com/AIGC-Audio/AudioGPT) | 10k+ | Audio understanding and generation |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | 5k+ | Framework for building voice and multimodal AI agents |

---

## Agent Infrastructure

| Project | Stars | Description |
|---------|-------|-------------|
| [LangSmith](https://github.com/langchain-ai/langsmith-sdk) | 5k+ | Observability and testing for LLM apps |
| [LangFuse](https://github.com/langfuse/langfuse) | 10k+ | Open-source LLM observability and analytics |
| [Phoenix](https://github.com/Arize-ai/phoenix) | 8k+ | ML/LLM observability by Arize |
| [Weights & Biases](https://github.com/wandb/wandb) | 10k+ | ML experiment tracking and monitoring |
| [Prefect](https://github.com/PrefectHQ/prefect) | 18k+ | Workflow orchestration for data pipelines |
| [Temporal](https://github.com/temporalio/temporal) | 13k+ | Durable execution for distributed systems |
| [Modal](https://github.com/modal-labs/modal-client) | 2k+ | Serverless cloud for AI/ML workloads |
| [MCP (Model Context Protocol)](https://github.com/modelcontextprotocol) | 10k+ | Anthropic's protocol for connecting AI to tools |

---

## Learning Resources

| Project | Stars | Description |
|---------|-------|-------------|
| [LLM Course](https://github.com/mlabonne/llm-course) | 45k+ | Complete course on LLMs with roadmaps |
| [Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners) | 70k+ | Microsoft's 21-lesson course |
| [LangChain Cookbook](https://github.com/langchain-ai/langchain/tree/master/cookbook) | - | Official recipes and examples |
| [AI Agent Tutorials](https://github.com/NirDiamant/GenAI_Agents) | 10k+ | Comprehensive tutorials on AI agents |
| [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) | 55k+ | Comprehensive prompt engineering resources |
| [OpenAI Cookbook](https://github.com/openai/openai-cookbook) | 62k+ | Examples and guides for using OpenAI API |
| [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM) | 20k+ | Curated list of LLM resources |
| [Build a Large Language Model](https://github.com/rasbt/LLMs-from-scratch) | 40k+ | Build an LLM from scratch (book code) |
| [Deep Learning AI Short Courses](https://www.deeplearning.ai/short-courses/) | - | Free courses by Andrew Ng on AI agents |

---

## Contributing

Found a great open-source AI agent project? Open a PR or issue to add it!

## License

This list is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — feel free to use it however you like.

---

⭐ **Star this repo** if you find it useful! Updated regularly with new projects.
