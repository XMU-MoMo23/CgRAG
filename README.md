# CgRAG
**Enhancing Visual Question Answering with Multimodal LLMs via Chain-of-Question Guided Retrieval-Augmented Generation.**
## Overview
We introduce a logical prompting strategy that fuses Chain‑of‑Thought (CoT) reasoning with Visual Question Decomposition (VQD), termed CoVQD, to guide retrieval toward more accurate and relevant knowledge for MLLM inference. Building on this idea, we propose a new framework, **C**oVQD‑**g**uided **RAG** (CgRAG), which enables MLLMs to access more comprehensive and coherent external knowledge while benefiting from structured visual‑text reasoning guidance, thereby improving generalization and reliability in complex cross‑domain VQA scenarios. 

The proposed CgRAG framework integrates the strengths of existing augmentation strategies by introducing a multi-granular, step-by-step reasoning process based on CoVQD, together with a fine-grained and accurate RAG mechanism. Specifically, to transform the input question into a chain of questions, we fuse CoT reasoning with VQD to form CoVQD, which extracts detailed multimodal information from the input image and question and serves as structured guidance for retrieval. On this basis, we develop an MLLM-based pipeline that can be seamlessly integrated with different backbone MLLMs. A flexible prompt construction strategy is further adopted to effectively organize retrieved knowledge and align it with MLLM inference.

<img src="./images/Architecture.png" width="850">
## 
