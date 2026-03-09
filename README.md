<div align="center">

# 🚀 Complete Generative AI Roadmap — From Zero to Production

### Everything you need to become a GenAI/LLM Engineer — Free courses, YouTube videos, blogs, projects, and resources

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
![Status](https://img.shields.io/badge/Status-Learning%20in%20Progress-blue)
![Last Updated](https://img.shields.io/badge/Last%20Updated-March%202026-orange)

*A structured, hands-on roadmap covering Python → ML → DL → NLP → Transformers → LLMs → Prompt Engineering → RAG → Fine-tuning → AI Agents → Agentic AI → MCP → Multimodal AI → Voice AI → Deployment & MLOps. Organized from basics to advanced with the best free resources available.*

</div>

---

## 📌 How to Use This Roadmap

1. **Follow the levels in order** — each builds on the previous
2. **Check off topics** as you complete them (⬜ → ✅)
3. **Build projects** at every level to solidify learning
4. **Update the weekly log** to track your journey
5. **Star & fork** this repo to bookmark your progress

---

## 🗺️ Roadmap Overview

```
LEVEL 0          LEVEL 1          LEVEL 2          LEVEL 3
Prerequisites    Core GenAI       Advanced GenAI   Production & Frontier
(Wk 1-3)        (Wk 4-10)       (Wk 11-18)      (Wk 19-24)
┌──────────┐    ┌──────────┐    ┌──────────┐    ┌──────────┐
│ Python   │    │ LLM      │    │ Fine-    │    │ Voice AI │
│ ML Basics│───▶│ Basics   │───▶│ Tuning   │───▶│ MCP      │
│ DL & NLP │    │ Prompt   │    │ Adv RAG  │    │ Multi-   │
│ Math     │    │ Eng      │    │ AI Agents│    │ modal    │
│          │    │ RAG      │    │ LangGraph│    │ Deploy   │
│          │    │ LangChain│    │ Eval     │    │ MLOps    │
└──────────┘    └──────────┘    └──────────┘    └──────────┘
```

---

## 🎯 Level 0: Prerequisites (Weeks 1–3)

> *Skip if you already know Python, basic ML, and deep learning fundamentals.*

### 🐍 Python for AI/ML

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| Python basics (loops, functions, OOP) | ⬜ | [Python for Beginners — freeCodeCamp (6hr)](https://www.youtube.com/watch?v=rfscVS0vtbw) |
| NumPy | ⬜ | [NumPy Full Course — freeCodeCamp](https://www.youtube.com/watch?v=QUT1VHiLmmI) |
| Pandas | ⬜ | [Pandas Tutorial — Corey Schafer](https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS) |
| Matplotlib & Seaborn | ⬜ | [Data Visualization — freeCodeCamp](https://www.youtube.com/watch?v=UO98lJQ3QGI) |
| Python async/await | ⬜ | [AsyncIO — Tech With Tim](https://www.youtube.com/watch?v=2IW-ZEui4h4) |

### 📐 Math for AI (Just Enough)

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| Linear Algebra essentials | ⬜ | [3Blue1Brown — Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) |
| Calculus (gradients, chain rule) | ⬜ | [3Blue1Brown — Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) |
| Probability & Statistics | ⬜ | [StatQuest — Statistics Fundamentals](https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9) |

### 🤖 Machine Learning Fundamentals

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| ML concepts (supervised, unsupervised) | ⬜ | [Stanford CS229 — Andrew Ng (YouTube)](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU) |
| Scikit-learn hands-on | ⬜ | [ML with Scikit-learn — freeCodeCamp (2hr)](https://www.youtube.com/watch?v=pqNCD_5r0IU) |
| Supervised ML: Regression & Classification | ⬜ | [Coursera — Andrew Ng (free audit)](https://www.coursera.org/learn/machine-learning) |

### 🧠 Deep Learning Fundamentals

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| Neural networks from scratch | ⬜ | [3Blue1Brown — Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) |
| Backpropagation, gradient descent | ⬜ | [Andrej Karpathy — Zero to Hero (micrograd)](https://www.youtube.com/watch?v=VMj-3S1tku0) |
| PyTorch basics | ⬜ | [PyTorch for Deep Learning — freeCodeCamp (26hr)](https://www.youtube.com/watch?v=V_xro1bcAuA) |
| CNNs, RNNs, LSTMs | ⬜ | [Karpathy — makemore series](https://www.youtube.com/watch?v=PaCmpygFfXo) |
| Batch normalization, residual connections | ⬜ | [Karpathy — Building makemore Part 4](https://www.youtube.com/watch?v=P6sfmUTpUmc) |

### 📝 NLP Fundamentals

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| Text preprocessing, tokenization | ⬜ | [NLP with Python — freeCodeCamp](https://www.youtube.com/watch?v=fOvTtapxa9c) |
| Word embeddings (Word2Vec, GloVe) | ⬜ | [Stanford CS224N — Lecture 1-3 (YouTube)](https://www.youtube.com/playlist?list=PLoROMvodv4rMFqRtEuo6SGjY4XbRIVRd4) |
| Sequence models (RNN, LSTM, GRU) | ⬜ | [Karpathy — Zero to Hero (makemore)](https://karpathy.ai/zero-to-hero.html) |

### 📚 Level 0 Resources Hub

| Type | Resource | Link |
|------|----------|------|
| 🎥 Course | fast.ai — Practical Deep Learning | [course.fast.ai](https://course.fast.ai) |
| 🎥 Series | Karpathy — Neural Networks: Zero to Hero (full) | [YouTube Playlist](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) |
| 📖 Book | Dive into Deep Learning (free online) | [d2l.ai](https://d2l.ai) |
| 🎥 Course | DeepLearning.AI — ML Specialization (Coursera, free audit) | [Coursera](https://www.coursera.org/specializations/machine-learning-introduction) |
| 📂 GitHub | AI-ML Roadmap from Scratch | [aadi1011/AI-ML-Roadmap-from-scratch](https://github.com/aadi1011/AI-ML-Roadmap-from-scratch) |

---

## 🔥 Level 1: Core Generative AI (Weeks 4–10)

### ⚡ Transformers & Attention

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| Attention mechanism ("Attention Is All You Need") | ⬜ | [3Blue1Brown — Transformers (Chapter 5)](https://www.youtube.com/watch?v=wjZofJX0v4M) |
| Self-attention, multi-head attention | ⬜ | [3Blue1Brown — Attention in Transformers (Chapter 6)](https://www.youtube.com/watch?v=eMlx5fFNoYc) |
| Transformer architecture end-to-end | ⬜ | [Illustrated Transformer — Jay Alammar](https://jalammar.github.io/illustrated-transformer/) |
| Building GPT from scratch | ⬜ | [Karpathy — Let's Build GPT (2hr)](https://www.youtube.com/watch?v=kCc8FmEb1nY) |
| Tokenization (BPE, SentencePiece) | ⬜ | [Karpathy — Let's Build the GPT Tokenizer](https://www.youtube.com/watch?v=zduSFxRajkE) |

### 🧩 LLM Fundamentals

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| How LLMs work (GPT, LLaMA, Gemini) | ⬜ | [Karpathy — Intro to LLMs (1hr talk)](https://www.youtube.com/watch?v=zjkBMFhNj_g) |
| Decoder-only vs encoder-decoder | ⬜ | [Hugging Face NLP Course (free)](https://huggingface.co/learn/nlp-course) |
| Sampling (temperature, top-k, top-p) | ⬜ | [mlabonne/llm-course — Fundamentals](https://github.com/mlabonne/llm-course) |
| Context window, token limits | ⬜ | [OpenAI Documentation](https://platform.openai.com/docs) |
| Running LLMs locally (Ollama, llama.cpp) | ⬜ | [Ollama Quickstart](https://ollama.com) |

### ✍️ Prompt Engineering

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| Prompt engineering fundamentals | ⬜ | [OpenAI — Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering) |
| Zero-shot, few-shot, chain-of-thought | ⬜ | [Google — Prompt Engineering Guide (68pg PDF)](https://services.google.com/fh/files/misc/gemini-for-google-workspace-prompting-guide-101.pdf) |
| System prompts, role prompting | ⬜ | [Prompt Engineering Guide — DAIR.AI](https://www.promptingguide.ai) |
| ReAct, Tree-of-Thought prompting | ⬜ | [IBM — Prompt Engineering Basics (Coursera, free)](https://www.coursera.org/learn/generative-ai-prompt-engineering-for-everyone) |
| Structured output (JSON mode) | ⬜ | [DeepLearning.AI — ChatGPT Prompt Engineering](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) |

### 🔗 LangChain & Frameworks

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| LangChain basics (chains, models, tools) | ⬜ | [Krish Naik — GenAI Crash Course with LangChain (3hr)](https://www.youtube.com/watch?v=7qqGnuRrWxg) |
| LangChain memory, message types | ⬜ | [DeepLearning.AI — LangChain for LLM App Dev](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/) |
| LlamaIndex basics | ⬜ | [LlamaIndex Docs — Getting Started](https://docs.llamaindex.ai) |
| Hugging Face Transformers library | ⬜ | [Hugging Face Course (free)](https://huggingface.co/learn/nlp-course) |
| OpenAI API (completions, chat, embeddings) | ⬜ | [OpenAI Cookbook (GitHub)](https://github.com/openai/openai-cookbook) |

### 📚 RAG (Retrieval-Augmented Generation)

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| RAG fundamentals | ⬜ | [freeCodeCamp — RAG & MCP Crash Course (1.5hr)](https://www.youtube.com/watch?v=I7_WXKhyGms) |
| Embeddings & vector similarity | ⬜ | [KodeKloud — Complete RAG Tutorial (free labs)](https://www.youtube.com/watch?v=vT-DpLvf29Q) |
| Vector databases (ChromaDB, Qdrant, Pinecone) | ⬜ | [freeCodeCamp — GenAI Full Course Day 8-10](https://www.youtube.com/watch?v=mEsleV16qdo&t=46982s) |
| Chunking strategies (fixed, semantic, overlapping) | ⬜ | [Ansh Lamba — RAG Tutorial for Data Engineers (4hr)](https://www.youtube.com/watch?v=71MW5WeHdz8) |
| Building a basic RAG pipeline | ⬜ | [LangChain RAG Tutorial (docs)](https://python.langchain.com/docs/tutorials/rag/) |

### 📚 Level 1 Resources Hub

| Type | Resource | Link |
|------|----------|------|
| 📂 GitHub | mlabonne/llm-course (70k+ ⭐) | [github.com/mlabonne/llm-course](https://github.com/mlabonne/llm-course) |
| 🎥 Course | freeCodeCamp — GenAI Full Course (30hr) | [YouTube](https://www.youtube.com/watch?v=mEsleV16qdo) |
| 🎥 Course | DeepLearning.AI — GenAI with LLMs (Coursera, free) | [Coursera](https://www.coursera.org/learn/generative-ai-with-llms) |
| 🎥 Course | Google — Intro to Generative AI | [Cloud Skills Boost](https://www.cloudskillsboost.google/paths/118) |
| 📖 Blog | Jay Alammar — Illustrated Transformer | [jalammar.github.io](https://jalammar.github.io/illustrated-transformer/) |
| 📖 Blog | Lilian Weng — The Transformer Family V2 | [lilianweng.github.io](https://lilianweng.github.io/posts/2023-01-27-the-transformer-family-v2/) |
| 📂 GitHub | sudarshan-koirala/llm-resources | [GitHub](https://github.com/sudarshan-koirala/llm-resources) |
| 🎥 Short | DeepLearning.AI — All Free Short Courses (40+) | [deeplearning.ai/courses](https://learn.deeplearning.ai) |
| 📂 GitHub | krishnaik06/Complete-RoadMap-To-Learn-AI | [GitHub](https://github.com/krishnaik06/Complete-RoadMap-To-Learn-AI) |

---

## ⚡ Level 2: Advanced Generative AI (Weeks 11–18)

### 🎯 LLM Fine-Tuning

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| Full fine-tuning vs PEFT | ⬜ | [DeepLearning.AI — Finetuning LLMs (free short course)](https://www.deeplearning.ai/short-courses/finetuning-large-language-models/) |
| LoRA and QLoRA | ⬜ | [Krish Naik — LLM Fine Tuning Playlist (YouTube)](https://www.youtube.com/watch?v=Vg3dS-NLUT4&list=PLZoTAELRMXVN9VbAx5I2VvloTtYmlApe3) |
| Instruction tuning | ⬜ | [poloclub/Fine-tuning-LLMs (Colab, free)](https://github.com/poloclub/Fine-tuning-LLMs) |
| RLHF and DPO | ⬜ | [Hugging Face — RLHF Blog](https://huggingface.co/blog/rlhf) |
| Dataset preparation (Alpaca, ShareGPT format) | ⬜ | [LLM Fine-Tuning Guide: Zero to Hero (GitHub)](https://github.com/ajitsingh98/The-Ultimate-Guide-to-LLM-Fine-Tuning-From-Zero-to-Hero/) |
| Unsloth / Axolotl for fast training | ⬜ | [Unsloth Docs](https://unsloth.ai) |
| Quantization (GPTQ, GGUF, AWQ) | ⬜ | [mlabonne — Quantization section](https://github.com/mlabonne/llm-course#quantization) |

### 🔍 Advanced RAG

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| Multi-query RAG | ⬜ | [LangChain — Multi-query Retriever docs](https://python.langchain.com/docs/how_to/MultiQueryRetriever/) |
| Hybrid search (keyword + semantic) | ⬜ | [Qdrant — Hybrid Search Tutorial](https://qdrant.tech/articles/hybrid-search/) |
| Re-ranking (Cohere, cross-encoder) | ⬜ | [RAG Tutorial #17 — Reranking (YouTube)](https://www.youtube.com/watch?v=VWA15n6uiS4) |
| Agentic RAG | ⬜ | [LlamaIndex — Agentic RAG Tutorial](https://docs.llamaindex.ai/en/stable/examples/agent/agentic_rag/) |
| GraphRAG (knowledge graphs + RAG) | ⬜ | [Microsoft GraphRAG (GitHub)](https://github.com/microsoft/graphrag) |
| Multimodal RAG (tables, images, PDFs) | ⬜ | [LangChain — Multimodal RAG Cookbook](https://python.langchain.com/docs/tutorials/rag/) |
| RAG evaluation (RAGAS, recall, precision) | ⬜ | [DeepLearning.AI — Building & Evaluating RAG](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/) |

### 🤖 AI Agents & Agentic AI

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| AI Agents fundamentals (tools, planning, memory) | ⬜ | [DeepLearning.AI — AI Agents in LangGraph (Coursera)](https://www.coursera.org/projects/ai-agents-in-langgraph) |
| LangGraph (graphs, state, routing) | ⬜ | [LangChain Academy — Intro to LangGraph (free)](https://academy.langchain.com/courses/intro-to-langgraph) |
| LangGraph workflows (chaining, parallelization) | ⬜ | [Ansh Lamba — LangGraph Complete Course (YouTube)](https://www.youtube.com/watch?v=DtW_Lc9hYoU) |
| OpenAI Agents SDK | ⬜ | [Kody Simpson — OpenAI Agents SDK Full Series (2.5hr)](https://www.youtube.com/watch?v=gFcAfU3V1Zo) |
| CrewAI (multi-agent framework) | ⬜ | [CrewAI Docs — Getting Started](https://docs.crewai.com) |
| Human-in-the-loop patterns | ⬜ | [LangGraph — Human-in-the-loop Guide](https://langchain-ai.github.io/langgraph/how-tos/human_in_the_loop/) |
| Agentic patterns (orchestrator, evaluator, routing) | ⬜ | [Anthropic — Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) |

### 🔌 MCP (Model Context Protocol)

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| MCP fundamentals (servers, tools, resources) | ⬜ | [MCP Explained for Beginners 2026 (YouTube)](https://www.youtube.com/watch?v=wZn9XvXBnU4) |
| Building MCP servers (FastMCP, Python) | ⬜ | [DigitalOcean — MCP 101 Tutorial](https://www.digitalocean.com/community/tutorials/model-context-protocol) |
| MCP + LangChain / Agents integration | ⬜ | [freeCodeCamp — RAG & MCP Crash Course](https://www.youtube.com/watch?v=I7_WXKhyGms) |
| Advanced MCP (sampling, transports, roots) | ⬜ | [Anthropic — MCP Advanced Topics (free course)](https://anthropic.skilljar.com/model-context-protocol-advanced-topics) |
| MCP for Beginners (official course) | ⬜ | [Microsoft — MCP for Beginners (GitHub)](https://github.com/microsoft/mcp-for-beginners) |

### 📊 LLM Evaluation & Benchmarking

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| Evaluation metrics (BLEU, ROUGE, perplexity) | ⬜ | [Hugging Face — Evaluate Library](https://huggingface.co/docs/evaluate) |
| LLM-as-judge evaluation | ⬜ | [DeepLearning.AI — Evaluating LLM Apps](https://www.deeplearning.ai/short-courses/) |
| MT-Bench, HELM, Open LLM Leaderboard | ⬜ | [Hugging Face — Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) |
| Custom evaluation pipelines | ⬜ | [mlabonne — LLM AutoEval](https://github.com/mlabonne/llm-autoeval) |

### 📚 Level 2 Resources Hub

| Type | Resource | Link |
|------|----------|------|
| 📂 GitHub | Awesome LLMs Fine-Tuning | [GitHub](https://github.com/Curated-Awesome-Lists/awesome-llms-fine-tuning) |
| 📂 GitHub | End-to-End GenAI Projects (80+ projects) | [GitHub](https://github.com/GURPREETKAURJETHRA/END-TO-END-GENERATIVE-AI-PROJECTS) |
| 🎥 Course | Krish Naik — Agentic AI Bootcamp (Udemy, ₹399) | [Udemy](https://www.udemy.com/course/complete-agentic-ai-bootcamp-with-langgraph-and-langchain/) |
| 🎥 Course | freeCodeCamp — GenAI for Developers (21hr) | [YouTube](https://www.youtube.com/watch?v=mEsleV16qdo) |
| 📖 Blog | Anthropic — Building Effective Agents | [anthropic.com](https://www.anthropic.com/research/building-effective-agents) |
| 📂 GitHub | awesome-generative-ai | [GitHub](https://github.com/steven2358/awesome-generative-ai) |

---

## 🌐 Level 3: Production & Frontier (Weeks 19–24)

### 🎙️ Voice AI / Conversational AI

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| STT → LLM → TTS pipeline | ⬜ | [LiveKit Agents Docs](https://docs.livekit.io/agents/) |
| WebRTC & WebSocket for voice | ⬜ | [WebRTC.ventures — WebRTC for Voice AI](https://webrtc.ventures/2025/10/why-webrtc-is-the-best-transport-for-real-time-voice-ai-architectures/) |
| VAD, endpointing, barge-in | ⬜ | [Telnyx — How to Evaluate Voice AI](https://telnyx.com/resources/how-to-evaluate-voice-ai-the-way-real-conversations-work) |
| LiveKit Agents / Pipecat frameworks | ⬜ | [LiveKit — Voice AI Quickstart](https://docs.livekit.io/agents/start/voice-ai-quickstart/) |
| Telephony (SIP, Twilio, FreeSWITCH) | ⬜ | [Bolna Open Source (GitHub)](https://github.com/bolna-ai/bolna) |
| Speech-to-Speech models | ⬜ | [HF — Speech-to-Speech (GitHub)](https://github.com/huggingface/speech-to-speech) |

### 🖼️ Multimodal AI

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| Vision Language Models (GPT-4V, Gemini) | ⬜ | [OpenAI — Vision Guide](https://platform.openai.com/docs/guides/vision) |
| Image generation (Stable Diffusion, DALL-E) | ⬜ | [Hugging Face — Diffusers Library](https://huggingface.co/docs/diffusers) |
| Multimodal agents | ⬜ | [DeepLearning.AI — Multimodal RAG](https://www.deeplearning.ai/short-courses/) |
| Audio + Vision + Text fusion | ⬜ | [Ultravox — Multimodal LLM (GitHub)](https://github.com/fixie-ai/ultravox) |

### 🚀 Deployment & MLOps

| Topic | Status | Best Free Resource |
|-------|--------|--------------------|
| FastAPI for LLM serving | ⬜ | [FastAPI Docs](https://fastapi.tiangolo.com) |
| Docker containerization | ⬜ | [Docker — Getting Started](https://docs.docker.com/get-started/) |
| vLLM / TGI for inference | ⬜ | [vLLM Docs](https://docs.vllm.ai) |
| AWS Bedrock / SageMaker | ⬜ | [AWS — GenAI with Bedrock (free course)](https://explore.skillbuilder.aws/learn/course/external/view/elearning/17904/generative-ai-with-amazon-bedrock) |
| LLM observability (LangSmith, Phoenix) | ⬜ | [LangSmith Docs](https://docs.smith.langchain.com) |
| CI/CD for AI apps | ⬜ | [GitHub Actions — CI/CD Tutorial](https://docs.github.com/en/actions) |
| Model versioning & monitoring | ⬜ | [MLflow Docs](https://mlflow.org/docs/latest/index.html) |
| LLM security (prompt injection, jailbreaks) | ⬜ | [OWASP — LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/) |

### 📚 Level 3 Resources Hub

| Type | Resource | Link |
|------|----------|------|
| 🎥 Course | freeCodeCamp — GenAI in the Cloud (23hr) | [YouTube](https://www.youtube.com/watch?v=NxlJw7Qnqbc) |
| 📂 GitHub | awesome-voice-ai | [GitHub](https://github.com/amitdev01/awesome-voice-ai) |
| 📂 GitHub | LiveKit Agents | [GitHub](https://github.com/livekit/agents) |
| 📂 GitHub | Pipecat — Voice AI Framework | [GitHub](https://github.com/pipecat-ai/pipecat) |
| 📖 Blog | HF — Deploying Speech-to-Speech | [Blog](https://huggingface.co/blog/s2s_endpoint) |

---

## 🛠️ Projects — Beginner to Advanced

### 🟢 Beginner Projects

| # | Project | Concepts Covered | Starter Resource |
|---|---------|-----------------|-----------------|
| 1 | **Simple Chatbot with OpenAI API** | API calls, streaming, system prompts | [OpenAI Quickstart](https://platform.openai.com/docs/quickstart) |
| 2 | **PDF Q&A Bot** | Embeddings, vector DB, basic RAG | [LangChain RAG Tutorial](https://python.langchain.com/docs/tutorials/rag/) |
| 3 | **Prompt Engineering Playground** | Prompt templates, few-shot, CoT | [Streamlit + OpenAI](https://streamlit.io) |
| 4 | **Text Summarizer** | LLM API, chunking, prompt design | [Hugging Face Pipeline](https://huggingface.co/docs/transformers/main_classes/pipelines) |
| 5 | **AI-Powered Resume Screener** | Text extraction, embeddings, similarity | [spaCy + LLM](https://spacy.io) |
| 6 | **LangChain Chatbot with Memory** | Conversation memory, chains | [LangChain Memory Docs](https://python.langchain.com/docs/concepts/memory/) |

### 🟡 Intermediate Projects (Resume-Worthy)

| # | Project | Concepts Covered | Starter Resource |
|---|---------|-----------------|-----------------|
| 7 | **Multi-Document RAG System** | Advanced chunking, hybrid search, reranking | [LlamaIndex RAG](https://docs.llamaindex.ai) |
| 8 | **Customer Support Agent** | AI agents, tool calling, RAG, routing | [LangGraph Tutorials](https://langchain-ai.github.io/langgraph/) |
| 9 | **LLaMA/Mistral Fine-Tuning (LoRA)** | QLoRA, Unsloth, Hugging Face, evaluation | [poloclub/Fine-tuning-LLMs](https://github.com/poloclub/Fine-tuning-LLMs) |
| 10 | **Financial AI Agent** | Multi-agent, tool use, API integration | [CrewAI + YFinance](https://docs.crewai.com) |
| 11 | **Medical RAG Chatbot** | Domain RAG, BioMistral, Qdrant | [End-to-End GenAI Projects](https://github.com/GURPREETKAURJETHRA/END-TO-END-GENERATIVE-AI-PROJECTS) |
| 12 | **Code Assistant with RAG** | Code embeddings, GitHub integration | [OpenAI Codex / Cursor](https://platform.openai.com) |
| 13 | **Multi-Agent Research System** | CrewAI/LangGraph, web search, report gen | [CrewAI Examples](https://github.com/crewAIInc/crewAI-examples) |
| 14 | **Agentic RAG with Evaluation** | Agentic RAG, RAGAS metrics, feedback loop | [RAGAS Docs](https://docs.ragas.io) |

### 🔴 Advanced Projects (Industry-Level)

| # | Project | Concepts Covered | Starter Resource |
|---|---------|-----------------|-----------------|
| 15 | **Production RAG with CI/CD** | FastAPI, Docker, monitoring, CI/CD, cloud | [LangServe Docs](https://python.langchain.com/docs/langserve/) |
| 16 | **Voice AI Agent (Phone Calls)** | STT, LLM, TTS, WebRTC, telephony | [Pipecat Examples](https://github.com/pipecat-ai/pipecat-examples) |
| 17 | **MCP Server + AI Agent** | MCP tools/resources, client integration | [MCP for Beginners (Microsoft)](https://github.com/microsoft/mcp-for-beginners) |
| 18 | **Multimodal AI Assistant** | Vision + Text + Audio, Gemini/GPT-4V | [Google AI Studio](https://aistudio.google.com) |
| 19 | **End-to-End LLM Fine-Tuning Pipeline** | Data prep → train → eval → deploy → monitor | [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) |
| 20 | **Multi-Agent Orchestration Platform** | OpenAI Agents SDK + LangGraph + MCP | [OpenAI Agents SDK Docs](https://openai.github.io/openai-agents-python/) |
| 22 | **Open-Source Contribution** | Framework internals, testing, PR process | [Pipecat](https://github.com/pipecat-ai/pipecat) or [LangChain](https://github.com/langchain-ai/langchain) |

---

## 🎥 Best Free YouTube Channels for GenAI

| Channel | Best For | Must-Watch |
|---------|----------|-----------|
| **Andrej Karpathy** | Deep fundamentals, building from scratch | [Zero to Hero Series](https://karpathy.ai/zero-to-hero.html) |
| **3Blue1Brown** | Visual math & neural network intuition | [Neural Networks Playlist](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) |
| **Krish Naik** | GenAI roadmap, LangChain, agents, projects | [GenAI Crash Course](https://www.youtube.com/watch?v=7qqGnuRrWxg) |
| **freeCodeCamp** | Long-form free courses (10-30hr) | [GenAI 30hr Course](https://www.youtube.com/watch?v=mEsleV16qdo) |
| **DeepLearning.AI** | Structured short courses (Andrew Ng) | [deeplearning.ai/courses](https://learn.deeplearning.ai) |
| **Simplilearn** | Structured full courses for beginners | [GenAI Full Course 2026](https://www.youtube.com/watch?v=IyYr2kUG0iI) |
| **Sam Witteveen** | Advanced RAG, agents, frameworks | [YouTube Channel](https://www.youtube.com/@samwitteveen) |
| **Matt Williams** | Ollama, local LLMs, practical tutorials | [YouTube Channel](https://www.youtube.com/@technovangelist) |
| **James Briggs** | LangChain, Pinecone, RAG deep dives | [YouTube Channel](https://www.youtube.com/@jamesbriggs) |
| **Raj Kapadia** | OpenAI SDK, agents, practical coding | [Agents SDK Tutorial](https://www.youtube.com/watch?v=mQHD3-mllro) |

---

## 📖 Best Free Courses (Structured)

| Course | Platform | Duration | Level | Link |
|--------|----------|----------|-------|------|
| Generative AI for Everyone | DeepLearning.AI | 3hr | Beginner | [Coursera (free)](https://www.coursera.org/learn/generative-ai-for-everyone) |
| Generative AI with LLMs | AWS + DeepLearning.AI | 15hr | Intermediate | [Coursera (free audit)](https://www.coursera.org/learn/generative-ai-with-llms) |
| ChatGPT Prompt Engineering | DeepLearning.AI | 1hr | Beginner | [deeplearning.ai](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) |
| LangChain for LLM App Dev | DeepLearning.AI | 1hr | Intermediate | [deeplearning.ai](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/) |
| Building & Evaluating Advanced RAG | DeepLearning.AI | 1hr | Intermediate | [deeplearning.ai](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/) |
| Finetuning Large Language Models | DeepLearning.AI | 1hr | Intermediate | [deeplearning.ai](https://www.deeplearning.ai/short-courses/finetuning-large-language-models/) |
| Intro to LangGraph | LangChain Academy | 3hr | Intermediate | [academy.langchain.com](https://academy.langchain.com/courses/intro-to-langgraph) |
| AI Agents in LangGraph | Coursera | 2hr | Intermediate | [Coursera](https://www.coursera.org/projects/ai-agents-in-langgraph) |
| MCP Advanced Topics | Anthropic | 2hr | Advanced | [Anthropic Skilljar](https://anthropic.skilljar.com/model-context-protocol-advanced-topics) |
| HuggingFace NLP Course | Hugging Face | 20hr+ | All levels | [huggingface.co/learn](https://huggingface.co/learn/nlp-course) |
| Google — Intro to Generative AI | Google Cloud | 30min | Beginner | [Cloud Skills Boost](https://www.cloudskillsboost.google/paths/118) |
| AWS — GenAI Learning Plan | AWS | 4hr | Intermediate | [AWS Skill Builder](https://explore.skillbuilder.aws) |

---

## 📖 Best Free Blogs & Guides

| Resource | What It Covers | Link |
|----------|---------------|------|
| Prompt Engineering Guide (DAIR.AI) | Comprehensive prompt techniques | [promptingguide.ai](https://www.promptingguide.ai) |
| OpenAI Prompt Engineering Guide | Official best practices | [platform.openai.com](https://platform.openai.com/docs/guides/prompt-engineering) |
| Jay Alammar — Illustrated Transformer | Visual transformer explanation | [jalammar.github.io](https://jalammar.github.io/illustrated-transformer/) |
| Lilian Weng's Blog | Transformer family, agents, RLHF | [lilianweng.github.io](https://lilianweng.github.io) |
| Hugging Face Blog | Fine-tuning, RLHF, deployments | [huggingface.co/blog](https://huggingface.co/blog) |
| Anthropic Research Blog | Agent patterns, safety, Claude | [anthropic.com/research](https://www.anthropic.com/research) |
| Chip Huyen's Blog | MLOps, LLM systems design | [huyenchip.com](https://huyenchip.com) |
| Simon Willison's Blog | Practical LLM usage, tools | [simonwillison.net](https://simonwillison.net) |

---

## 📂 Must-Star GitHub Repositories

| Repository | Stars | What It Is |
|-----------|-------|-----------|
| [mlabonne/llm-course](https://github.com/mlabonne/llm-course) | 70k+ | Complete LLM roadmap with Colab notebooks |
| [krishnaik06/Complete-RoadMap-To-Learn-AI](https://github.com/krishnaik06/Complete-RoadMap-To-Learn-AI) | 5k+ | 3 paths to AI mastery with week-by-week plans |
| [GURPREETKAURJETHRA/END-TO-END-GENERATIVE-AI-PROJECTS](https://github.com/GURPREETKAURJETHRA/END-TO-END-GENERATIVE-AI-PROJECTS) | 3k+ | 80+ end-to-end GenAI projects with source code |
| [steven2358/awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) | 6k+ | Curated list of GenAI tools and services |
| [Curated-Awesome-Lists/awesome-llms-fine-tuning](https://github.com/Curated-Awesome-Lists/awesome-llms-fine-tuning) | 2k+ | Fine-tuning resources, tools, papers |
| [aadi1011/AI-ML-Roadmap-from-scratch](https://github.com/aadi1011/AI-ML-Roadmap-from-scratch) | 1k+ | Complete AI/ML roadmap with free resources |
| [openai/openai-cookbook](https://github.com/openai/openai-cookbook) | 60k+ | Official OpenAI examples and best practices |
| [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) | 5k+ | MCP tutorial from Microsoft |
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | 100k+ | LLM application framework |
| [livekit/agents](https://github.com/livekit/agents) | 5k+ | Voice AI agent framework |
| [pipecat-ai/pipecat](https://github.com/pipecat-ai/pipecat) | 5k+ | Open source voice & multimodal AI framework |

---

## 📅 Weekly Learning Log

> Update this section as you progress. Change ⬜ to ✅ in the skill tables above.

<details>
<summary><b>Weeks 1-3: Prerequisites</b></summary>

- [ ] Complete Python refresher
- [ ] Watch 3Blue1Brown math playlists
- [ ] Finish Karpathy Zero to Hero (micrograd + makemore)
- [ ] Build first neural network in PyTorch
- [ ] **Notes/Blog:** _link here_

</details>

<details>
<summary><b>Weeks 4-6: Transformers, LLMs & Prompt Engineering</b></summary>

- [ ] Watch 3Blue1Brown Transformers chapters
- [ ] Build GPT from scratch with Karpathy
- [ ] Complete DeepLearning.AI Prompt Engineering course
- [ ] Build simple chatbot with OpenAI API
- [ ] **Notes/Blog:** _link here_

</details>

<details>
<summary><b>Weeks 7-10: LangChain, RAG & First Projects</b></summary>

- [ ] Complete LangChain crash course
- [ ] Build PDF Q&A bot with RAG
- [ ] Set up vector database (ChromaDB/Qdrant)
- [ ] Complete freeCodeCamp RAG & MCP course
- [ ] Build Multi-Document RAG System (Project #7)
- [ ] **Notes/Blog:** _link here_

</details>

<details>
<summary><b>Weeks 11-14: Fine-Tuning & Advanced RAG</b></summary>

- [ ] Fine-tune LLaMA/Mistral with QLoRA
- [ ] Implement advanced RAG (hybrid search, reranking)
- [ ] Build Medical RAG Chatbot (Project #11)
- [ ] Study RAG evaluation with RAGAS
- [ ] **Notes/Blog:** _link here_

</details>

<details>
<summary><b>Weeks 15-18: AI Agents, LangGraph & MCP</b></summary>

- [ ] Complete LangGraph course
- [ ] Build Customer Support Agent (Project #8)
- [ ] Complete OpenAI Agents SDK tutorial
- [ ] Build MCP server + agent integration (Project #17)
- [ ] Build Multi-Agent Research System (Project #13)
- [ ] **Notes/Blog:** _link here_

</details>

<details>
<summary><b>Weeks 19-21: Voice AI & Multimodal</b></summary>

- [ ] Set up LiveKit Agent Starter
- [ ] Build Voice AI Agent (Project #16)
- [ ] Build Multimodal AI Assistant (Project #18)
- [ ] Study WebRTC and telephony basics
- [ ] **Notes/Blog:** _link here_

</details>

<details>
<summary><b>Weeks 22-24: Deployment, Portfolio & Contributions</b></summary>

- [ ] Deploy RAG system with FastAPI + Docker + CI/CD (Project #15)
- [ ] Build Healthcare Voice Agent (Project #21)
- [ ] Submit PR to open-source project (Project #22)
- [ ] Polish GitHub portfolio and README
- [ ] Write capstone blog post
- [ ] **Notes/Blog:** _link here_

</details>

---

## 🏗️ Tech Stack Reference

| Layer | Tools |
|-------|-------|
| **LLMs** | GPT-4o, Gemini, LLaMA 3, Mistral, DeepSeek, Qwen |
| **Frameworks** | LangChain, LlamaIndex, Hugging Face, CrewAI |
| **Agents** | OpenAI Agents SDK, LangGraph, CrewAI, AutoGen |
| **RAG** | ChromaDB, Qdrant, Pinecone, OpenSearch, Weaviate |
| **Fine-tuning** | Unsloth, Axolotl, Hugging Face TRL, LoRA/QLoRA |
| **Voice AI** | LiveKit Agents, Pipecat, Bolna, Deepgram, ElevenLabs |
| **Serving** | FastAPI, vLLM, TGI, Ollama, LangServe |
| **MLOps** | Docker, MLflow, LangSmith, Phoenix, GitHub Actions |
| **Cloud** | AWS (Bedrock, SageMaker), GCP (Vertex AI), Azure AI |
| **Frontend** | Streamlit, Gradio, React, Chainlit |

---

## 📬 Connect

- **LinkedIn:** [linkedin.com/in/pruthvi-s](https://linkedin.com/in/pruthvi-s)
- **GitHub:** [github.com/Prureddy](https://github.com/Prureddy)
- **Email:** pruthvisreddy8861@gmail.com

---

<div align="center">

**⭐ Star this repo if you find it useful! PRs and suggestions welcome.**

*Started: March 2026 | Target: Production GenAI Engineer by September 2026*

**Built with ❤️ by Pruthvi S**

</div>
