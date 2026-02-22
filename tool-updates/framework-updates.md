# AI Framework & Library Updates (2025)

## Major Framework Updates

### PyTorch
- **Current:** PyTorch 2.x (stable)
- **Key updates (2024–2025):**
  - `torch.compile` — JIT compilation for 2x+ speedups (now default recommended)
  - `torch.export` — Production model export (replacing TorchScript)
  - FlexAttention — Flexible attention variants in pure PyTorch
  - Distributed training improvements (FSDP2)
  - Better Apple Silicon / MPS support
  - `torch.distributed` enhancements for multi-node training
- **Ecosystem:** Still dominant in research (~80% of ML papers)

### TensorFlow / JAX
- **TensorFlow:** Maintenance mode for most use cases
- **JAX:** Growing in Google and research
  - Pallas — Custom GPU kernels in JAX
  - Stronger TPU integration
  - Equinox, Flax, Optax ecosystem maturing
- **Keras 3:** Multi-backend (TF, JAX, PyTorch)

### Hugging Face Transformers
- **Current:** v4.x (continuous releases)
- **Key updates:**
  - 300,000+ models on Hub
  - PEFT (LoRA, QLoRA, AdaLoRA) built-in
  - AutoGPTQ, BitsAndBytes quantization integration
  - Text Generation Inference (TGI) for serving
  - Optimum for hardware-specific optimization
  - Multimodal pipeline support (vision, audio, text)

### LangChain
- **Current:** v0.3.x
- **Key updates:**
  - LangGraph for agent workflows (graph-based)
  - LangSmith for observability and tracing
  - Simplified chain API (LCEL — LangChain Expression Language)
  - Multi-agent orchestration patterns
  - Tool calling improvements for function calling
- **Competitors:** LlamaIndex, Haystack, Semantic Kernel

### LlamaIndex
- **Current:** v0.11.x
- **Key updates:**
  - Workflows API for complex RAG pipelines
  - LlamaParse for document parsing
  - Improved multi-modal RAG
  - Better agent abstractions
  - Property graph index for structured retrieval

## Inference & Serving

### vLLM
- **Current:** v0.6.x
- **What:** High-throughput LLM serving engine
- **Key features:** PagedAttention, continuous batching, speculative decoding
- **Performance:** 24x+ throughput vs naive serving
- **Supported:** Most popular open models

### Ollama
- **Current:** v0.5.x
- **What:** Run LLMs locally with one command
- **Key features:** Model library, API compatibility, easy setup
- **Supported:** LLaMA, Mistral, Gemma, Phi, CodeLlama, and more

### TensorRT-LLM (NVIDIA)
- **What:** Optimized LLM inference on NVIDIA GPUs
- **Key features:** INT4/INT8 quantization, inflight batching, KV cache optimization
- **Performance:** Fastest inference on NVIDIA hardware

### llama.cpp
- **What:** CPU/GPU inference for LLMs in C/C++
- **Key features:** GGUF format, 2/3/4/5/6/8-bit quantization
- **Platform:** Runs on everything (laptops, phones, Raspberry Pi)

## Training & Fine-Tuning

### Axolotl
- **What:** Easy LLM fine-tuning tool
- **Supports:** Full fine-tune, LoRA, QLoRA, DPO, RLHF
- **Models:** LLaMA, Mistral, Phi, Gemma, and more

### Unsloth
- **What:** 2-5x faster LLM fine-tuning
- **Key feature:** Memory-efficient training, free Colab notebooks
- **Supported:** LLaMA, Mistral, Gemma, Phi

### PEFT (Hugging Face)
- **Methods:** LoRA, QLoRA, AdaLoRA, prefix tuning, prompt tuning
- **Integration:** Native Hugging Face Transformers support
- **Key benefit:** Fine-tune large models on consumer GPUs

## Vector Databases & RAG

| Database | Type | Key Features |
|----------|------|-------------|
| **Pinecone** | Cloud-managed | Serverless, hybrid search, metadata filtering |
| **Weaviate** | Open-source | Multi-modal, GraphQL API, hybrid search |
| **Chroma** | Open-source | Simple API, in-memory or persistent |
| **Qdrant** | Open-source | Rust-based, filtering, sparse vectors |
| **Milvus** | Open-source | Distributed, GPU-accelerated |
| **pgvector** | PostgreSQL ext | Familiar SQL, easy setup |
| **FAISS** | Library (Meta) | Fastest similarity search |

## AI Agent Frameworks

| Framework | Provider | Key Features |
|-----------|----------|-------------|
| **LangGraph** | LangChain | Graph-based agent workflows |
| **CrewAI** | Open-source | Multi-agent role-playing |
| **AutoGen** | Microsoft | Multi-agent conversations |
| **Semantic Kernel** | Microsoft | Enterprise AI orchestration |
| **Haystack** | deepset | Pipeline-based NLP framework |
| **Autogen Studio** | Microsoft | Visual agent builder |
| **Claude MCP** | Anthropic | Model Context Protocol for tool use |

## MLOps & Deployment

| Tool | Category | Key Features |
|------|----------|-------------|
| **MLflow** | Experiment tracking | Model registry, deployments |
| **Weights & Biases** | Experiment tracking | Visualization, sweeps, artifacts |
| **DVC** | Data versioning | Git for data/models |
| **BentoML** | Model serving | Unified serving framework |
| **Modal** | Serverless compute | GPU functions, easy deployment |
| **Replicate** | Model hosting | Run models via API |
| **Together AI** | Inference API | Open model serving |

---

*Updated: February 2025*
