# Awesome Persian AI & MCP Hub

<div align="center">

![Awesome Persian AI Banner](assets/banner.svg)

<br/>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Organization](https://img.shields.io/badge/Org-Kalahamoon-6366f1.svg?style=flat-square)](https://github.com/Kalahamoon)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-10b981.svg?style=flat-square)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-f59e0b.svg?style=flat-square)](LICENSE)
[![Persian Docs](https://img.shields.io/badge/نسخه_فارسی-README.fa.md-0ea5e9.svg?style=flat-square)](README.fa.md)

<br/>

**The curated and comprehensive engineering directory of Model Context Protocol (MCP) servers, LLMs, Agentic tools, cloud gateways, and AI infrastructure for Persian (Farsi) and the Iranian developer ecosystem.**

[Persian Version (نسخه کامل فارسی)](README.fa.md) • [Contribution Guidelines](CONTRIBUTING.md) • [Submit Tool / Issue](https://github.com/Kalahamoon/awesome-persian-ai/issues)

</div>

---

### 🇮🇷 Tribute to the Persian AI Community Worldwide

> **A Tribute to Iranian Engineers & Researchers:**  
> Our deepest respect and congratulations to Iranian software engineers, AI researchers, open-source contributors, and entrepreneurs across the globe — from top research labs and universities worldwide to hardworking local startups and independent creators within Iran. Despite extreme sanctions, network barriers, and infrastructure constraints, your brilliance and persistence keep the torch of the Persian language, culture, and sovereign AI technology burning at the global frontier. This hub is dedicated to all of you. 🦁✨

---

## 🏷️ Badges & Taxonomy Legend

To ensure rapid technical assessment, every listed tool is tagged with standard status badges:

| Badge | Type | Description |
| :---: | :--- | :--- |
| `[MCP]` | **Model Context Protocol** | Native or compliant server exposing standardized tools and resources to LLMs |
| `[Open-Source]` | **Open Weights / Code** | Fully accessible source code or model weights on GitHub or Hugging Face |
| `[API-Gateway]` | **Inference Gateway** | Unified OpenAI / Anthropic compatible endpoint provider payable via local currency |
| `[Agent]` | **Autonomous Agent** | Systems featuring planning, tool execution loops, and autonomous workflows |
| `[Leaderboard]` | **Competitive Benchmark** | Rigorous evaluation harness or public ranking leaderboard |
| `[Security]` | **Safety & Guardrails** | Prompt injection defense, BiDi integrity, and alignment test suites |
| `[Domain-AI]` | **Specialized AI** | Fine-tuned systems for Legal, Healthcare, or Finance domains |
| `[Free]` | **Free Tier Available** | Usable at no monetary cost |
| `[Freemium]` | **Pay-As-You-Go** | Trial credit provided; pay-per-token or volume-based pricing |
| `[Commercial]` | **Enterprise / Paid** | Commercial license, subscription, or enterprise contract required |
| `[Iran-Access]` | **National Intranet** | Resilient during international connectivity dropouts |
| `[No-VPN]` | **Direct Access** | No VPN or proxy circumventing required from inside Iran |

---

## 🧭 Table of Contents

- [1. 🔌 Model Context Protocol (MCP) Servers](#1--model-context-protocol-mcp-servers)
  - [1.1. E-Commerce & Classifieds](#11-e-commerce--classifieds)
  - [1.2. Enterprise Automation & Messengers](#12-enterprise-automation--messengers)
  - [1.3. Local Time, Calendars & Financial Market Feeds](#13-local-time-calendars--financial-market-feeds)
- [2. ☁️ Cloud Platforms & API Gateways](#2-️-cloud-platforms--api-gateways)
  - [2.1. Aggregated LLM Gateways (No-VPN)](#21-aggregated-llm-gateways-no-vpn)
  - [2.2. Cloud GPU & Infrastructure Providers](#22-cloud-gpu--infrastructure-providers)
- [3. 🧠 Persian LLMs & Foundation Models](#3--persian-llms--foundation-models)
  - [3.1. Open Models & Pre-Trained Weights](#31-open-models--pre-trained-weights)
  - [3.2. Evaluation Leaderboards & Benchmarks](#32-evaluation-leaderboards--benchmarks)
- [4. 🤖 Agentic Frameworks & Production Agents](#4--agentic-frameworks--production-agents)
- [5. 🛡️ LLM Security, Guardrails & Jailbreak Defense](#5-️-llm-security-guardrails--jailbreak-defense)
- [6. ⚖️🩺 Domain-Specific AI: LegalTech & Healthcare](#6-️-domain-specific-ai-legaltech--healthcare)
  - [6.1. LegalTech, Jurisprudence & Contracts](#61-legaltech-jurisprudence--contracts)
  - [6.2. Healthcare, Medicine & Clinical Tools](#62-healthcare-medicine--clinical-tools)
- [7. 🎙️ Speech Processing: STT & TTS](#7-️-speech-processing-stt--tts)
  - [7.1. Speech-to-Text (STT / ASR)](#71-speech-to-text-stt--asr)
  - [7.2. Text-to-Speech & Voice Cloning (TTS)](#72-text-to-speech--voice-cloning-tts)
- [8. 👁️ Computer Vision, OCR & Multimodal](#8-️-computer-vision-ocr--multimodal)
- [9. 📚 Persian Embeddings & Enterprise RAG](#9--persian-embeddings--enterprise-rag)
  - [9.1. Embedding Models](#91-embedding-models)
  - [9.2. Enterprise RAG Pipelines](#92-enterprise-rag-pipelines)
- [10. 🛠️ Persian NLP Toolkits & Normalizers](#10-️-persian-nlp-toolkits--normalizers)
- [11. 🌐 Neural Machine Translation (NMT)](#11--neural-machine-translation-nmt)
- [12. 🖥️ Developer Tools, RTL Fixers & Terminals](#12-️-developer-tools-rtl-fixers--terminals)
- [13. 📊 Large-Scale Datasets & Corpora](#13--large-scale-datasets--corpora)

---

## 1. 🔌 Model Context Protocol (MCP) Servers

Anthropic's open **Model Context Protocol (MCP)** standard enables AI models (Claude Code, Cursor, OpenCode, VS Code, Windsurf) to securely query databases, invoke APIs, and inspect internal enterprise workflows.

### 1.1. E-Commerce & Classifieds

| Server / Tool | Badges | Description | Stack | Documentation / Repo |
| :--- | :---: | :--- | :---: | :---: |
| **[Basalam MCP Server](https://developers.basalam.com/docs/mcp)** | `[MCP]` `[Production]` | Official MCP server for Iran's social commerce marketplace Basalam at `mcp.basalam.com/mcp`. Enables search, store inventory lookups, and order processing | HTTP Transport / OAuth | [Basalam Docs](https://developers.basalam.com/docs/mcp) |
| **[Digikala MCP Server](https://github.com/mmdju/digikala-mcp)** | `[MCP]` `[Open-Source]` | Standalone Digikala MCP server with 16 tools for product searches, price histories, buyer review extractions, and technical specs | Cloudflare Workers / TS | [mmdju/digikala-mcp](https://github.com/mmdju/digikala-mcp) |
| **[Divar MCP Server](https://github.com/mmdju/divar-mcp)** | `[MCP]` `[Open-Source]` | Divar marketplace MCP server providing deep search, listing extractions, and real-estate/vehicle analytics | Cloudflare Workers / TS | [mmdju/divar-mcp](https://github.com/mmdju/divar-mcp) |
| **[Torob MCP Server](https://github.com/mmdju/torob-mcp)** | `[MCP]` `[Open-Source]` | Torob price comparison MCP server featuring 14 tools to track multi-vendor deals, merchant inventory, and price drops | Cloudflare Workers / TS | [mmdju/torob-mcp](https://github.com/mmdju/torob-mcp) |

### 1.2. Enterprise Automation & Messengers

| Server / Tool | Badges | Description | Stack | Access |
| :--- | :---: | :--- | :---: | :---: |
| **Kasra MCP Server** | `[MCP]` `[Internal]` | Full integration with Kasra Enterprise ERP for personnel attendance, cardex balance tracking, and automated leave requests | Python / FastMCP | Local |
| **Bale Messenger MCP** | `[MCP]` `[Open-Source]` | Connects LLM agents to Bale Messenger; reads thread history, searches channels, and sends confirmed messages | Python / Stdio | Local |
| **[Liara Cloud MCP Server](https://github.com/SalehB1/Lira-mcp)** | `[MCP]` `[Open-Source]` | Hybrid EN/FA retrieval over Liara cloud docs, deployment diagnostics, and build-log inspection with zero external API key needed | Python / Local Corpus | [SalehB1/Lira-mcp](https://github.com/SalehB1/Lira-mcp) |
| **[Aira Cognitive MCP](https://github.com/AiraChat/aira-mcp)** | `[MCP]` `[Open-Source]` | MCP connector registry for Persian cognitive intelligence workflows | TypeScript | [AiraChat/aira-mcp](https://github.com/AiraChat/aira-mcp) |
| **[Hermes Agent Iran Gateway](https://github.com/hnkwing/hermes-agent-iran-gateway)** | `[Agent]` `[Open-Source]` | Production gateway connecting Nous Hermes agents to native messengers like Bale and Rubika | Python / LangGraph | [GitHub](https://github.com/hnkwing/hermes-agent-iran-gateway) |
| **[Smart Home KNX MCP](https://github.com/SMousavi7/smart-home-knx-thingsboard)** | `[MCP]` `[IoT]` | Natural language smart home management in Persian via KNX, ThingsBoard, and local Ollama LLMs | Python / Ollama | [SMousavi7/smart-home](https://github.com/SMousavi7/smart-home-knx-thingsboard) |
| **[APIs-made-in-Iran Catalog](https://github.com/Hameds/APIs-made-in-Iran)** | `[Tools]` `[Open-Source]` | Curated catalog of hundreds of Iranian public and enterprise web APIs ready for agent tool-calling schemas | JSON / Spec | [Hameds/APIs-made-in-Iran](https://github.com/Hameds/APIs-made-in-Iran) |

### 1.3. Local Time, Calendars & Financial Market Feeds

| Server / Tool | Badges | Description | Stack | Link |
| :--- | :---: | :--- | :---: | :---: |
| **[Jalali Date Engine](https://persian-calendar.ir/)** | `[Tools]` `[Free]` | Accurate algorithmic conversion between Solar Hijri, Gregorian, and Lunar Hijri calendars with Iranian public holiday verification | TypeScript / Node | [Service](https://persian-calendar.ir/) |
| **[TGJU Live Market Feed](https://marketplace.tgju.org)** | `[Tools]` `[Freemium]` | Real-time exchange rate, gold, coin, and Tehran Stock Exchange (TSE) market feeds formatted for LLM financial analysts | Python / REST | [Docs](https://marketplace.tgju.org) |
| **[Nobitex Trading Agent Tool](https://apidocs.nobitex.ir/)** | `[Tools]` `[Freemium]` | Nobitex crypto exchange API endpoints for spot order book analysis and USDT/IRR price discovery | REST API | [Docs](https://apidocs.nobitex.ir/) |

---

## 2. ☁️ Cloud Platforms & API Gateways

Cloud gateways providing zero-VPN, low-latency, and local payment access to cutting-edge models (Claude 3.5, GPT-4o, DeepSeek R1) and native models:

### 2.1. Aggregated LLM Gateways (No-VPN)

| Platform | Badges | Supported Models | Key Features | Website |
| :--- | :---: | :--- | :--- | :---: |
| **[AIZamin](https://aizamin.ir)** | `[API-Gateway]` `[Freemium]` `[No-VPN]` | GPT-4o, Claude 3.5, Gemini, DeepSeek | Pay-per-token & volumetric credit without monthly lock-in; native support for OpenCode, VS Code, and Hermes via Tomans | [aizamin.ir](https://aizamin.ir) |
| **[Metis AI](https://www.metisai.ir)** | `[API-Gateway]` `[Enterprise]` `[Iran-Access]` | Global frontier models + native fine-tunes | Guaranteed uptime during international network cutoffs; No-Code bot workflows, token caching, and enterprise RAG | [metisai.ir](https://www.metisai.ir) |
| **[AvalAI](https://avalai.ir)** | `[API-Gateway]` `[Freemium]` `[No-VPN]` | OpenAI, Anthropic, Mistral, LLaMA | High-speed OpenAI SDK compatible endpoint with instant local billing and low ping times | [avalai.ir](https://avalai.ir) |
| **[Part AI](https://partsoftware.com)** | `[Enterprise]` `[Iran-Access]` | Dorna, Sahab, local OCR, and STT | Largest enterprise AI ecosystem in Iran; banking vision, automated KYC, and financial LLMs | [partsoftware.com](https://partsoftware.com) |
| **[Hooshio](https://hooshio.com)** | `[API-Gateway]` `[Commercial]` | Multimodal vision and generative text models | Knowledge base and enterprise subscriptions for image and text models | [hooshio.com](https://hooshio.com) |
| **[Mehparto](https://mehparto.ir)** | `[Enterprise]` `[Commercial]` | Custom LLM deployments and cloud inference | Corporate AI infrastructure and dedicated server clusters | [mehparto.ir](https://mehparto.ir) |

### 2.2. Cloud GPU & Infrastructure Providers

* **[ArvanCloud AI / GPU IaaS](https://arvancloud.ir)** `[Iran-Access]` — NVIDIA GPU cloud instances hosted inside Iranian datacenters for private model fine-tuning and inference.
* **[Derak Cloud](https://derak.cloud)** `[Cloud]` — Edge infrastructure, distributed object storage, and low-latency storage for high-dimensional vector databases.

---

## 3. 🧠 Persian LLMs & Foundation Models

Foundation models specifically pre-trained or instruction-tuned for Persian linguistic nuances:

### 3.1. Open Models & Pre-Trained Weights

| Model | Badges | Base Architecture | Parameters | Strengths & Notes |
| :--- | :---: | :---: | :---: | :--- |
| **Dorna 2** | `[Open-Source]` `[Weights]` | LLaMA-3.1 | 8B | Flagship instruction-tuned Persian model by Part AI; native GGUF support for conversational and formal Persian |
| **Maral-7B** | `[Open-Source]` `[Weights]` | Mistral-7B | 7B | Landmark Persian open LLM based on Mistral; renowned for Persian idiomatic reasoning |
| **PersianMind** | `[Open-Source]` `[Weights]` | LLaMA-2 | 7B | Academic research foundation model by University of Tehran for Persian scientific and literary QA |
| **Sina-LLM** | `[Open-Source]` `[Weights]` | LLaMA-3 | 8B | Instruction-tuned on extensive Persian corpora for complex reasoning and fluent translation |
| **AVA Series** | `[Open-Source]` `[Weights]` | LLaMA-3 / Mistral | 8B / 7B | AVA model family optimized for conversational speed and polite Persian phrasing |
| **ParsBERT** | `[Open-Source]` `[Transformers]` | BERT Base | 110M | Foundational transformer for Persian NLU with over 160,000 downloads on Hugging Face |
| **ParsGPT** | `[Open-Source]` `[Weights]` | GPT-2 | Multi | Early open-weights Persian autoregressive language model by HooshvareLab |
| **Gemma-3-Persian** | `[Open-Source]` `[Weights]` | Google Gemma | 4B | Lightweight model fine-tuned on modern instruction sets for CPU-friendly deployments |
| **Ava-LLM** | `[Open-Source]` `[Local-CPU]` | Qwen-2.5 / Gemma | 2B / 7B | Ultra-compact architectures designed for local desktop Ollama execution |
| **Hezar Models** | `[Open-Source]` `[Transformers]` | BERT / RoBERTa / T5 | Multi | All-in-one suite covering sentiment, NER, token classification, and text generation |

### 3.2. Evaluation Leaderboards & Benchmarks

* **[Open Persian LLM Leaderboard (PartAI)](https://huggingface.co/spaces/PartAI/open-persian-llm-leaderboard)** `[Leaderboard]` `[Top-Rank]` — Official competitive benchmark leaderboard evaluating Persian LLMs on Hugging Face.
* **[persian-llm-eval](https://github.com/heyparsadev/persian-llm-eval)** `[Open-Source]` `[Benchmark]` — Deterministic eval suite with 300 test items across 10 distinct tracks and bootstrap confidence intervals.
* **[PersianMMLU Benchmark](https://huggingface.co/spaces/raia-center/PersianMMLU)** `[Benchmark]` `[MMLU]` — Multitask Language Understanding benchmark covering 57 academic and specialized disciplines in Persian.
* **[ParsiEval](https://github.com/mshojaei77/ParsiEval)** `[Open-Source]` `[Benchmark]` — Rigorous test harness for evaluating logical reasoning, mathematics, and reading comprehension in Persian LLMs.
* **[ParsBench](https://github.com/ParsBench/ParsBench)** `[Open-Source]` `[Toolkit]` — Open toolkit for benchmarking frontier models on downstream Persian tasks.
* **[TAAROFBENCH](https://github.com/niktaas/TAAROFBENCH)** `[Research]` `[EMNLP 2025]` — Groundbreaking academic benchmark evaluating LLM understanding of Iranian cultural politeness (*Taarof*), sarcasm, and indirect discourse.

---

## 4. 🤖 Agentic Frameworks & Production Agents

Autonomous agent architectures and tool-orchestration engines built for Persian tasks:

* **[LangGraph Multi-Agent Persian](https://github.com/SaharZarbafi/langgraph-multi-agent-persian)** `[Open-Source]` `[Multi-Agent]` — Production-grade multi-agent architecture with Actor-Critic self-critique loops and heterogeneous model routing.
* **[Local SQL Agent (Persian)](https://github.com/alisadeghiaghili/local-sql-agent)** `[Open-Source]` `[Text-to-SQL]` — AST-validated natural-language-to-SQL engine for Persian enterprise databases with column-level ACLs.
* **[Doctor Agent](https://github.com/SirBNL/doctor-agent)** `[Open-Source]` `[Agent]` — Persian medical appointment booking agent with zero-shot local tool calling via Ollama.
* **[Phone Agent](https://github.com/sepehr071/phone-agent)** `[Open-Source]` `[Voice Agent]` — Automated PBX telephone receptionist connected over Asterisk AudioSocket (STT -> LLM -> TTS in real-time Persian).
* **[Micky Voice Assistant](https://github.com/xmannii/micky)** `[Open-Source]` `[Agent]` — Persian-first agentic voice assistant with modular system actions and modern UX.
* **[Moujez Summarizer Agent](https://github.com/kharazi/moujez)** `[Open-Source]` `[Agent]` — Structured extractive and abstractive summarization agent for long Persian documents and reports.

---

## 5. 🛡️ LLM Security, Guardrails & Jailbreak Defense

Tools, datasets, and methodologies for red-teaming and securing Persian AI systems:

* **[MCI LLM Security Hackathon Archive](https://github.com/erfnzdeh/MCI-LLM-Security-Hackathon)** `[Security]` `[Jailbreak]` — Empirical study of safety jailbreaks across 14 prohibited domains using cross-lingual transliteration and framing attacks on Persian models.
* **[Persian LLM Security Evaluation](https://github.com/Haniyesabeghi/Persian-LLM-Security-Evaluation-BA)** `[Security]` `[Prompt-Injection]` — Vulnerability analysis and defense strategies against prompt injections in Dorna and Maral.
* **[Morphological Type Guards (MTG)](https://github.com/Moshe-ship/mtg)** `[Security]` `[Tool-Defense]` — Typed runtime validation layer preventing BiDi/RTL homoglyph spoofing and Unicode confusable attacks (UTS #39) in multilingual tool arguments.
* **[PAIB Benchmark](https://github.com/Romohub/paib)** `[Security]` `[Agent-Integrity]` — Integrity benchmark verifying agent resistance against unauthorized tool calls and prompt overrides.

---

## 6. ⚖️🩺 Domain-Specific AI: LegalTech & Healthcare

### 6.1. LegalTech, Jurisprudence & Contracts
* **[Persian Legal Practice OS](https://github.com/ansariaiadmin/legal-platform)** `[Open-Source]` `[LegalTech]` — Self-hosted legal OS for Iranian attorneys featuring 6 specialized agents, tri-hybrid RAG, and case law analyzers.
* **[Persian Legal RAG Agent](https://github.com/Hamidreza-Talei/persian-legal-rag-agent)** `[Open-Source]` `[LangGraph]` — Statutory question answering for Iranian civil and penal codes using LanceDB, LangGraph, and rerankers.
* **[Smart Legal Letterhead](https://github.com/ahmadsalamifar/smart-legal-letterhead)** `[Open-Source]` `[Automation]` — Automated Persian legal document generator with formal formatting and terminology validation.

### 6.2. Healthcare, Medicine & Clinical Tools
* **[PerMed (Persian Meditron)](https://github.com/neda-kheirkhah/PerMed)** `[Open-Source]` `[Medical-LLM]` — Specialized clinical language model fine-tuned on Meditron for Persian healthcare inquiries.
* **[Persian Medical RAG Chatbot](https://github.com/yousef-mousavizade/Persian-Medical-RAG-Chatbot)** `[Open-Source]` `[Healthcare]` — Reliable pharmaceutical and clinical assistant grounded on verified Iranian medical formularies.
* **[OSCE AI Tutor](https://github.com/NafisSam/osce-tutor)** `[Open-Source]` `[Medical-Education]` — Interactive clinical OSCE examination simulator for Persian medical students.

---

## 7. 🎙️ Speech Processing: STT & TTS

### 7.1. Speech-to-Text (STT / ASR)
* **[wav2vec2-large-xlsr-53-persian](https://huggingface.co/jonatasgrosman/wav2vec2-large-xlsr-53-persian)** `[HuggingFace]` `[STT]` — Most downloaded Persian speech recognition model on Hugging Face (~1M downloads).
* **[Wav2Vec2 Persian v3 (m3hrdadfi)](https://huggingface.co/m3hrdadfi/wav2vec2-large-xlsr-persian-v3)** `[Open-Source]` — State-of-the-art acoustic model fine-tuned on clean Persian audio benchmarks.
* **[Whisper-Persian-v4 (nezamisafa)](https://huggingface.co/nezamisafa/whisper-persian-v4)** `[Open-Source]` `[Whisper]` — Whisper Large-v3 fine-tuned for colloquial Persian phrases and noisy backgrounds.
* **[Persian ASR Leaderboard](https://huggingface.co/spaces/navidved/open_persian_asr_leaderboard)** `[Leaderboard]` — Competitive WER benchmark comparing Persian speech models on public corpora.
* **[PersianScribe for Apple Silicon](https://github.com/duuuude/PersianScribe-for-Apple-Silicon)** `[Open-Source]` `[Offline]` — Native Mac speech-to-text with speaker diarization optimized for Apple Silicon (M1-M4).
* **[Nemotron ASR Streaming Farsi](https://huggingface.co/mehdi-hf/mehdi-hf/nemotron-asr-streaming-farsi)** `[Open-Source]` `[Streaming]` — Ultra-low latency streaming speech recognition based on NVIDIA Nemotron.
* **[FarsAva](https://amerandish.com)** `[Commercial]` `[API]` — Industrial-grade commercial speech recognition API by Amerandish.
* **[IoType](https://www.iotype.com/api)** `[Freemium]` `[API]` — Cloud speech-to-text API offering audio transcription and editing endpoints.

### 7.2. Text-to-Speech & Voice Cloning (TTS)
* **[Chatterbox-TTS-Persian-Farsi](https://huggingface.co/Thomcles/Chatterbox-TTS-Persian-Farsi)** `[HuggingFace]` `[TTS]` — High-fidelity natural speech synthesis model with emotional prosody.
* **[Pocket TTS Farsi (ONNX)](https://huggingface.co/Nimaone/pocket-tts-farsi-v2-onnx)** `[Open-Source]` `[Lightweight]` — Compact ONNX voice model suitable for mobile and edge devices.
* **[persian_tts (nimaone)](https://github.com/nimaone/persian_tts)** `[Open-Source]` `[Offline]` — Offline CPU voice synthesis with voice cloning capabilities.
* **[Mana Persian Piper](https://huggingface.co/MahtaFetrat/Mana-Persian-Piper)** `[Open-Source]` `[Piper]` — Piper TTS model trained on balanced multi-speaker Persian speech.
* **[dcho Voice Engine](https://github.com/AliAkrami1375/dcho)** `[Open-Source]` `[Edge]` — Fast neural TTS designed for smart speakers and microcontrollers.
* **[Gooya Bozorg](https://github.com/Reza2kn/gooya-bozorg-native)** `[Open-Source]` `[Desktop]` — Native cross-platform desktop application for offline reading of long Persian texts.

---

## 8. 👁️ Computer Vision, OCR & Multimodal

* **[CLIPfa](https://github.com/sajjjadayobi/CLIPfa)** `[Open-Source]` `[Multimodal]` — Persian dual-encoder multimodal model connecting images and Persian text for zero-shot classification and semantic visual search.
* **[Qwen2-VL Persian-Arabic OCR](https://huggingface.co/mohajesmaeili/Qwen3-VL-2B-Persian-Arabic-Ocr-v1.0)** `[Vision-LLM]` — Vision-Language Model tuned to digitize handwritten manuscripts, mixed documents, and math.
* **[Persian OCR Master](https://github.com/JENOVASir/persianAi-OCR-MASTER)** `[Open-Source]` — Web OCR suite with high-precision recognition of handwritten notes and math symbols with Word export.
* **[PDF-OCR-Math2LaTeX](https://github.com/Sadeghizad/pdf-ocr-fas-eng-math2latex)** `[Desktop]` `[LaTeX]` — Desktop app performing bilingual Persian/English OCR and converting formulas into valid LaTeX syntax.
* **[Hezar Vision](https://github.com/hezarai/hezar)** `[Open-Source]` — Pre-trained computer vision models for Iranian license plate recognition, National ID, and document parsing.
* **[Iran OCR](https://www.iranocr.ir)** `[Commercial]` `[API]` — Established commercial OCR API service for scanned documents and PDF images.

---

## 9. 📚 Persian Embeddings & Enterprise RAG

### 9.1. Embedding Models
* **[Persian Embeddings (heydariAI)](https://huggingface.co/heydariAI/persian-embeddings)** `[HuggingFace]` `[Top-Embedding]` — Top-rated Persian sentence embedding model trained on large-scale semantic similarity corpora.
* **[BGE-M3 Multilingual](https://github.com/FlagOpen/FlagEmbedding)** `[Open-Source]` — Frontier multilingual model with robust support for complex Persian semantic retrieval across dense and sparse queries.
* **[ParsBERT NLI](https://huggingface.co/parsi-ai-nlpclass/ParsBERT-nli-FarsTail-FarSick)** `[Open-Source]` — Natural language inference model for document contradiction and entailment verification.

### 9.2. Enterprise RAG Pipelines
* **[PersianRAG (TahaBakhtari)](https://github.com/TahaBakhtari/PersianRAG)** `[Open-Source]` — Ready-to-deploy question answering pipeline over Persian PDF archives.
* **[Bank Chatbot Legal RAG](https://github.com/Muhammad-davoudi/bank-chatbot)** `[Open-Source]` — Production RAG system for Iranian banking circulars with anti-hallucination guardrails.

---

## 10. 🛠️ Persian NLP Toolkits & Normalizers

| Library | Badges | Language | Description |
| :--- | :---: | :---: | :--- |
| **[DadmaTools](https://github.com/Dadmatech/DadmaTools)** | `[Open-Source]` | Python | Comprehensive Persian NLP toolkit from Dadmatech; lemmatizer, dependency parser, POS tagger, and summarizer |
| **[Hezar](https://github.com/hezarai/hezar)** | `[Open-Source]` | Python | High-level library unifying Hugging Face transformers, vision, and speech under a clean API |
| **[ParsiNLU](https://github.com/persiannlp/parsinlu)** | `[Open-Source]` | Python | High-level evaluation benchmark suite covering reading comprehension, entailment, and question generation |
| **[Persian-Tools](https://github.com/persian-tools/persian-tools)** | `[Open-Source]` | TS / Py / Go / Rust | Battle-tested library for National Code, Sheba, card validation, and Jalali date parsing across 8 languages |
| **[Hazm](https://github.com/roshan-research/hazm)** | `[Open-Source]` | Python | Pioneer Persian text tokenization, stemming, and POS tagging toolkit by Roshan Research |
| **[Parsivar](https://github.com/ICTRC/Parsivar)** | `[Open-Source]` | Python | Text pre-processing library adhering strictly to the Academy of Persian Language and Literature rules |
| **[Persian-NER](https://github.com/Text-Mining/Persian-NER)** | `[Open-Source]` | Dataset | Largest tagged Named Entity Recognition (NER) corpus and toolkit for Persian |
| **[Persian AI Glossary](https://github.com/snrazavi/Persian-AI-and-Machine-Learning-Glossary)** | `[Docs]` | MD | Standard Persian translations for AI, Deep Learning, and data science terminology |

---

## 11. 🌐 Neural Machine Translation (NMT)

* **[mT5-ParsiNLU Opus Translation (FA-EN)](https://huggingface.co/persiannlp/mt5-small-parsinlu-opus-translation_fa_en)** `[HuggingFace]` `[NMT]` — High-quality bidirectional English/Persian neural translation model (>50k downloads).
* **[Persian-To-English LoRA Translator](https://github.com/Mahdi-Maaref/Persian-To-English-Translator)** `[Open-Source]` `[PEFT]` — Resource-efficient LoRA adapter for fast real-world translation serving on modest hardware.
* **[EPUB AI Translator](https://github.com/Retro-Zero/epub-ai-translator)** `[Web-App]` `[Translator]` — Translates entire e-books into fluent Persian while preserving chapter styling and RTL layout.

---

## 12. 🖥️ Developer Tools, RTL Fixers & Terminals

* **[RTL Support for VS Code Agents](https://github.com/GuyRonnen/rtl-for-vs-code-agents)** `[VS-Code-Extension]` — Native-like Right-to-Left (RTL) rendering in VS Code AI agents (GitHub Copilot, Cursor) while keeping English code blocks cleanly LTR formatted.
* **[Kivun Terminal](https://github.com/noambrand/kivun-terminal-wsl)** `[DevTool]` `[Terminal]` — Cross-platform terminal with a native BiDi engine ensuring Anthropic's Claude Code and agent outputs render without reversed Persian characters.
* **[BiDi Shaper](https://github.com/cc1a2b/bidi-shaper)** `[Open-Source]` `[Text-Shaping]` — Zero-dependency Unicode UAX #9 engine and contextual glyph shaper for Canvas, WebGL, three.js, and terminals.
* **[Nimruz Desktop](https://github.com/xmannii/nimruz-desktop)** `[Open-Source]` `[Desktop UI]` — Elegant desktop client with Persian-first typography for chatting with local and remote LLMs.
* **[Hermes Agent Farsi](https://github.com/m4tinbeigi-official/hermes-agent-farsi)** `[UI-Mod]` — One-click localization, RTL layout, and Vazirmatn font styling for Nous Hermes Agent dashboards.
* **[Persian AI RTL Assistant](https://github.com/tig-ndi/persian-ai-rtl-assistant)** `[Browser-Extension]` — Browser extension automatically enforcing RTL text alignment on ChatGPT, Claude, and DeepSeek.
* **[Persian Text to PDF Converter](https://github.com/Ho3seinTork/Persian-Text-to-PDF-Converter)** `[Web-App]` — Converts markdown LLM outputs into cleanly shaped Persian PDF documents.
* **[Reply RTL Viewer](https://github.com/shahriyar3/reply-rtl-viewer)** `[Open-Source]` — Single-file markdown viewer with BiDi isolation preventing mixed Latin/Persian code garbling.

---

## 13. 📊 Large-Scale Datasets & Corpora

* **[PersianQA](https://github.com/sajjjadayobi/PersianQA)** `[Dataset]` `[QA]` — Gold-standard Persian reading comprehension dataset based on Persian Wikipedia with 9,000+ QA pairs.
* **[ManaTTS Speech Dataset](https://github.com/MahtaFetrat/ManaTTS-Persian-Speech-Dataset)** `[Audio Dataset]` — Largest open transcribed Persian speech corpus containing 114+ hours of high-quality speech.
* **[Persian Raw Text (80GB)](https://github.com/persiannlp/persian-raw-text)** `[Corpus]` — Approximately 80 GB of deduplicated, cleaned text for pre-training large language models.
* **[SentiPers Corpus](https://github.com/phosseini/SentiPers)** `[Research]` `[Sentiment]` — Standard sentiment analysis corpus for Persian reviewed and published on arXiv.
* **[FarsInstruct](https://huggingface.co/datasets/ParsiAI/FarsInstruct)** `[Dataset]` — Large-scale instruction-tuning dataset for aligning Persian assistants and chat models.
* **[Alpaca Persian](https://huggingface.co/datasets/sinarashidi/alpaca-persian)** `[Dataset]` — Persian translation and cultural adaptation of the Stanford Alpaca 52k dataset.
* **[Persian Voice v1](https://huggingface.co/datasets/vhdm/persian-voice-v1)** `[Audio Dataset]` — Multi-speaker speech dataset for voice cloning and acoustic modeling.
* **[Persian Wikipedia QA](https://huggingface.co/datasets/fibonacciai/Persian-Wikipedia-QA)** `[Dataset]` — Open QA dataset extracted from encyclopedic articles for training RAG retrievers.
* **[GPTInformal Speech Dataset](https://github.com/MahtaFetrat/GPTInformal-Persian-Speech-Dataset)** `[Dataset]` — 6+ hours of informal speech-to-text pairs for conversational fine-tuning.
* **[MirasText & Hamshahri Corpus](https://github.com/mhbashari/awesome-persian-nlp-ir)** `[Corpus]` — Multi-million-article journalistic corpora for historical and language modeling research.

---

## 👥 Maintainers & Community

Maintained and curated by the **[Kalahamoon](https://github.com/Kalahamoon)** organization alongside the Iranian AI and open-source engineering community worldwide.

---

## 📜 License

Released under the permissive **[MIT License](LICENSE)**.
