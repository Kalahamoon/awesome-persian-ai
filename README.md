# Awesome Persian AI & MCP Hub

<div align="center">

![Awesome Persian AI Banner](assets/banner.svg)

<br/>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Organization](https://img.shields.io/badge/Organization-Kalahamoon-6366f1.svg?style=flat-square)](https://github.com/Kalahamoon)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-10b981.svg?style=flat-square)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-f59e0b.svg?style=flat-square)](LICENSE)
[![Persian Version](https://img.shields.io/badge/Language-Persian_README-0ea5e9.svg?style=flat-square)](README.fa.md)

<br/>

**The definitive community directory of Model Context Protocol (MCP) servers, LLMs, Agentic tools, and AI infrastructure strictly focused on Persian (Farsi) and the Iranian AI ecosystem.**

---

### 🇮🇷 مطالعه به زبان فارسی
> **کاربران و توسعه‌دهندگان گرامی:** برای مطالعه متن کامل و دسته‌بندی‌ها به زبان فارسی، لطفاً به **[مستندات فارسی (README.fa.md)](README.fa.md)** مراجعه فرمایید.

---

</div>

### 🦁 Tribute to the Persian AI Community Worldwide

> **Honoring Iranian Engineers & Researchers:**  
> Our deepest respect and congratulations to Iranian software engineers, AI researchers, open-source contributors, and entrepreneurs across the globe — from top research labs and universities worldwide to hardworking local startups and independent creators within Iran. Despite extreme sanctions, network barriers, and infrastructure constraints, your brilliance and persistence keep the torch of the Persian language, culture, and sovereign AI technology burning at the global frontier. This hub is dedicated to all of you. 🦁✨

---

## 🧭 Navigation & Directory

| # | Section | Overview |
| :---: | :--- | :--- |
| **01** | [🔌 Model Context Protocol (MCP) Servers](#1--model-context-protocol-mcp-servers) | Native MCP servers for marketplaces, cloud deployment, web scraping & messengers |
| **02** | [☁️ AI Cloud Platforms & Inference Gateways](#2-️-ai-cloud-platforms--inference-gateways) | Low-latency LLM gateways, pay-as-you-go tokens & GPU compute clouds |
| **03** | [🧠 Persian LLMs & Foundation Models](#3--persian-llms--foundation-models) | Open-weight foundation models, GGUFs, BERT/RoBERTa backbones & benchmarks |
| **04** | [🤖 Agentic Frameworks & Production Agents](#4--agentic-frameworks--production-agents) | Multi-agent swarms, Text-to-SQL, financial trading agents & voice PBX agents |
| **05** | [🛡️ LLM Security & Guardrails](#5-️-llm-security-guardrails--jailbreak-defense) | Prompt injection defense, BiDi integrity & jailbreak research |
| **06** | [⚖️🩺 Specialized Domain AI: Legal & Healthcare](#6-️-domain-specific-ai-legaltech--healthcare) | AI legal operating systems, medical LLMs & clinical simulators |
| **07** | [🎙️ Speech Processing (STT & TTS)](#7-️-speech-processing-stt--tts) | Speech-to-text models, voice cloning & offline speech synthesis |
| **08** | [👁️ Computer Vision, OCR & Multimodal](#8-️-computer-vision-ocr--multimodal) | Persian CLIP multimodal models, OCR suites & LaTeX extraction |
| **09** | [📚 Persian Embeddings & Enterprise RAG](#9--persian-embeddings--enterprise-rag) | Vector embedding models & enterprise document RAG pipelines |
| **10** | [🛠️ Persian NLP Toolkits & Normalizers](#10-️-persian-nlp-toolkits--normalizers) | Industrial text cleaners, tokenizers & morphology toolkits |
| **11** | [🌐 Neural Machine Translation (NMT)](#11--neural-machine-translation-nmt) | Bidirectional neural translation models & e-book translators |
| **12** | [🖥️ AI Interfaces, Agent DevTools & RTL Tools](#12-️-ai-interfaces-agent-devtools--rtl-tools) | VS Code agent RTL fixers, opencode plugins, BiDi terminals & desktop clients |
| **13** | [📊 AI Datasets & Corpora](#13--ai-datasets--corpora) | 80GB pre-training corpora, instruction datasets & speech corpora |

---

## 🏷️ Badges & Taxonomy Legend

| Badge | Meaning & Classification |
| :--- | :--- |
| ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) | **Model Context Protocol:** Exposes standardized agent tools & resources |
| ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | **Open Source:** Public source code or weights hosted on GitHub / Hugging Face |
| ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) | **Inference Gateway:** OpenAI/Claude compatible API with local currency billing |
| ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) | **Autonomous Agent:** Executes multi-step tool-calling loops autonomously |
| ![Leaderboard](https://img.shields.io/badge/Leaderboard-pink?style=flat-square) | **Leaderboard & Eval:** Public competitive benchmarking suite |
| ![Security](https://img.shields.io/badge/Security-red?style=flat-square) | **Security & Guardrail:** Adversarial testing, prompt protection & integrity layer |
| ![LegalTech](https://img.shields.io/badge/LegalTech-violet?style=flat-square) ![Healthcare](https://img.shields.io/badge/Healthcare-teal?style=flat-square) | **Domain Specific:** Tailored architectures for law, jurisprudence or medicine |
| ![No-VPN](https://img.shields.io/badge/No--VPN-sky?style=flat-square) | **Direct Connection:** Fully accessible without VPN from inside Iran |
| ![Iran-Access](https://img.shields.io/badge/Iran--Access-green?style=flat-square) | **Intranet Resilient:** Guaranteed availability during national network isolations |
| ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) | **Pricing Model:** Free quotas / pay-as-you-go vs. enterprise contracts |

---

## 1. 🔌 Model Context Protocol (MCP) Servers

Anthropic's open **Model Context Protocol (MCP)** standard enables AI models (Claude Code, Cursor, OpenCode, VS Code, Windsurf) to securely query databases, invoke APIs, and inspect internal enterprise workflows.

### 1.1. E-Commerce & Classifieds

| Server / Tool | Badges | Description | Stack | Documentation / Repo |
| :--- | :---: | :--- | :---: | :---: |
| **[Basalam MCP Server](https://developers.basalam.com/docs/mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Commercial](https://img.shields.io/badge/Production-blue?style=flat-square) | Official MCP server for Iran's social commerce marketplace Basalam at `mcp.basalam.com/mcp`. Enables search, store inventory lookups, and order processing | HTTP Transport / OAuth | [Basalam Docs](https://developers.basalam.com/docs/mcp) |
| **[Digikala MCP Server](https://github.com/mmdju/digikala-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Standalone Digikala MCP server with 16 tools for product searches, price histories, buyer review extractions, and technical specs | Cloudflare Workers / TS | [mmdju/digikala-mcp](https://github.com/mmdju/digikala-mcp) |
| **[Divar MCP Server](https://github.com/mmdju/divar-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Divar marketplace MCP server providing deep search, listing extractions, and real-estate/vehicle analytics | Cloudflare Workers / TS | [mmdju/divar-mcp](https://github.com/mmdju/divar-mcp) |
| **[Torob MCP Server](https://github.com/mmdju/torob-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Torob price comparison MCP server featuring 14 tools to track multi-vendor deals, merchant inventory, and price drops | Cloudflare Workers / TS | [mmdju/torob-mcp](https://github.com/mmdju/torob-mcp) |

### 1.2. Cloud Infrastructure & Web Crawling

| Server / Tool | Badges | Description | Stack | Documentation / Repo |
| :--- | :---: | :--- | :---: | :---: |
| **[Liara Cloud MCP Server](https://github.com/razavioo/liara-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Full infrastructure management MCP server for Liara cloud: deploy apps, manage databases, view DNS records, and control disks with natural language | TypeScript / Node.js | [GitHub](https://github.com/razavioo/liara-mcp) |
| **[Crawlemoon MCP Server](https://github.com/razavioo/crawlemoon)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Advanced web crawling & scraping platform designed for the AI agent era; extracts clean markdown, structures tables, and exposes deep inspection tools | Python / FastMCP | [GitHub](https://github.com/razavioo/crawlemoon) |
| **[Liara Docs MCP](https://github.com/SalehB1/Lira-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Offline hybrid EN/FA retrieval over Liara cloud documentation, build-log diagnosis, and deployment configs | Python / Local Corpus | [SalehB1/Lira-mcp](https://github.com/SalehB1/Lira-mcp) |

### 1.3. Enterprise Automation & Messengers

| Server / Tool | Badges | Description | Stack | Access |
| :--- | :---: | :--- | :---: | :---: |
| **[Kasra MCP Server](https://github.com/razavioo/kasra-mcp-server)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Full integration with Kasra Enterprise ERP for personnel attendance, cardex balance tracking, shift punches, and automated leave/mission requests | Python / FastMCP | [GitHub](https://github.com/razavioo/kasra-mcp-server) |
| **[Userbot Bale MCP](https://github.com/razavioo/userbot-bale)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Comprehensive Bale Messenger client core & MCP server; search messages, inspect dialogs, and safely execute approved messaging | Python / Stdio | [GitHub](https://github.com/razavioo/userbot-bale) |
| **[Aira Cognitive MCP](https://github.com/AiraChat/aira-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | MCP connector registry for Persian cognitive intelligence workflows | TypeScript | [AiraChat/aira-mcp](https://github.com/AiraChat/aira-mcp) |
| **[Hermes Agent Iran Gateway](https://github.com/hnkwing/hermes-agent-iran-gateway)** | ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Production gateway connecting Nous Hermes agents to native messengers like Bale and Rubika | Python / LangGraph | [GitHub](https://github.com/hnkwing/hermes-agent-iran-gateway) |
| **[Smart Home KNX MCP](https://github.com/SMousavi7/smart-home-knx-thingsboard)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![IoT](https://img.shields.io/badge/IoT-blue?style=flat-square) | Natural language smart home management in Persian via KNX, ThingsBoard, and local Ollama LLMs | Python / Ollama | [SMousavi7/smart-home](https://github.com/SMousavi7/smart-home-knx-thingsboard) |

---

## 2. ☁️ AI Cloud Platforms & Inference Gateways

| Platform / Service | Badges | Supported Models & Offerings | Key Architectural Capabilities | Endpoint / Website |
| :--- | :---: | :--- | :--- | :---: |
| **[AIZamin](https://aizamin.ir)** | ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![No-VPN](https://img.shields.io/badge/No--VPN-sky?style=flat-square) ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) | GPT-4o, Claude 3.5, Gemini 1.5, DeepSeek R1 | Volumetric pay-as-you-go tokens without monthly subscriptions; native setup for OpenCode, VS Code, and Hermes | [aizamin.ir](https://aizamin.ir) |
| **[Metis AI](https://www.metisai.ir)** | ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![Iran-Access](https://img.shields.io/badge/Iran--Access-green?style=flat-square) ![Enterprise](https://img.shields.io/badge/Enterprise-slate?style=flat-square) | Frontier models + local fine-tunes | Guaranteed uptime during international network cutoffs, token caching, No-Code workflows & RAG memory | [metisai.ir](https://www.metisai.ir) |
| **[AvalAI](https://avalai.ir)** | ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![No-VPN](https://img.shields.io/badge/No--VPN-sky?style=flat-square) ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) | OpenAI, Anthropic, Mistral, LLaMA-3 | Standardized OpenAI SDK compatibility, low latency, and Iranian debit card (Shetab) billing | [avalai.ir](https://avalai.ir) |
| **[Part AI](https://partsoftware.com)** | ![Enterprise](https://img.shields.io/badge/Enterprise-slate?style=flat-square) ![Iran-Access](https://img.shields.io/badge/Iran--Access-green?style=flat-square) | Dorna 2, TookaBERT, Sahab, local OCR & ASR | National enterprise AI infrastructure; automated banking KYC, financial LLMs, and computer vision | [partsoftware.com](https://partsoftware.com) |
| **[Hooshio](https://hooshio.com)** | ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) | Image synthesis, LLMs & multimodal tools | Enterprise subscriptions and developer API endpoints for generative design | [hooshio.com](https://hooshio.com) |
| **[Mehparto](https://mehparto.ir)** | ![Enterprise](https://img.shields.io/badge/Enterprise-slate?style=flat-square) ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) | Private LLM deployments & enterprise fine-tuning | Dedicated on-premise clusters and corporate AI inference infrastructure | [mehparto.ir](https://mehparto.ir) |
| **[ArvanCloud GPU](https://arvancloud.ir)** | ![Iran-Access](https://img.shields.io/badge/Iran--Access-green?style=flat-square) ![Infrastructure](https://img.shields.io/badge/GPU--Cloud-blue?style=flat-square) | NVIDIA A100 / RTX GPU compute instances | High-bandwidth domestic GPU compute for training, model serving, and private embedding clusters | [arvancloud.ir](https://arvancloud.ir) |

---

## 3. 🧠 Persian LLMs & Foundation Models

### 3.1. Open Models & Pre-Trained Weights

| Model | Badges | Architecture | Size | Strengths & Notes | Repository / Hub |
| :--- | :---: | :---: | :---: | :--- | :---: |
| **Dorna 2** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | LLaMA-3.1 | 8B | Flagship instruction-tuned Persian model by Part AI; native GGUF support for conversational and formal Persian | [Hugging Face](https://huggingface.co/aeranginkaman/Dorna2-Llama3.1-8B-Instruct-Q4_K_M-GGUF) |
| **Maral-7B** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | Mistral-7B | 7B | Landmark Persian open LLM based on Mistral; renowned for Persian idiomatic reasoning | [Hugging Face](https://huggingface.co/models?search=Maral-7B) |
| **TookaBERT** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Transformers](https://img.shields.io/badge/Transformers-yellow?style=flat-square) | BERT Base / Large | Multi | Industrial-strength Persian representation model by Part AI trained on billions of tokens | [Hugging Face](https://huggingface.co/PartAI/TookaBERT-Base) |
| **PersianMind** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | LLaMA-2 | 7B | Academic research foundation model by University of Tehran for Persian scientific and literary QA | [Hugging Face](https://huggingface.co/universitytehran/PersianMind-v1.0) |
| **Sina-LLM** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | LLaMA-3 | 8B | Instruction-tuned on extensive Persian corpora for complex reasoning and fluent translation | [GitHub](https://github.com/snrazavi) |
| **AVA Series** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | LLaMA-3 / Mistral | 8B / 7B | AVA model family optimized for conversational speed and polite Persian phrasing | [GitHub](https://github.com/mehdihosseinimoghadam/AVA-Llama-3) |
| **ParsBERT** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Transformers](https://img.shields.io/badge/Transformers-yellow?style=flat-square) | BERT Base | 110M | Foundational transformer for Persian NLU with over 160,000 downloads on Hugging Face | [Hugging Face](https://huggingface.co/HooshvareLab/bert-base-parsbert-uncased) |
| **ParsGPT** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | GPT-2 | Multi | Early open-weights Persian autoregressive language model by HooshvareLab | [GitHub](https://github.com/hooshvare/parsgpt) |
| **Gemma-3-Persian** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | Google Gemma | 4B | Lightweight model fine-tuned on modern instruction sets for CPU-friendly deployments | [Hugging Face](https://huggingface.co/mshojaei77/gemma-3-4b-persian-v0) |
| **Ava-LLM** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Local-CPU](https://img.shields.io/badge/Local--CPU-cyan?style=flat-square) | Qwen-2.5 / Gemma | 2B / 7B | Ultra-compact architectures designed for local desktop Ollama execution | [Hugging Face](https://huggingface.co/models?search=ava-llm) |
| **Hezar Models** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Transformers](https://img.shields.io/badge/Transformers-yellow?style=flat-square) | BERT / RoBERTa / T5 | Multi | All-in-one suite covering sentiment, NER, token classification, and text generation | [GitHub](https://github.com/hezarai/hezar) |

### 3.2. Evaluation Leaderboards & Benchmarks

| Benchmark / Leaderboard | Badges | Domain & Track | Description | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[Open Persian LLM Leaderboard](https://huggingface.co/spaces/PartAI/open-persian-llm-leaderboard)** | ![Leaderboard](https://img.shields.io/badge/Leaderboard-pink?style=flat-square) | General LLM Evaluation | Official competitive benchmark evaluating open and proprietary Persian LLMs on Hugging Face | [Hugging Face Space](https://huggingface.co/spaces/PartAI/open-persian-llm-leaderboard) |
| **[persian-llm-eval](https://github.com/heyparsadev/persian-llm-eval)** | ![Benchmark](https://img.shields.io/badge/Benchmark-emerald?style=flat-square) | Deterministic Eval | 300 test items across 10 distinct tracks with bootstrap confidence intervals | [GitHub](https://github.com/heyparsadev/persian-llm-eval) |
| **[PersianMMLU Benchmark](https://huggingface.co/spaces/raia-center/PersianMMLU)** | ![Benchmark](https://img.shields.io/badge/Benchmark-emerald?style=flat-square) | Academic Multitask (MMLU) | Multitask Language Understanding benchmark covering 57 academic and specialized disciplines | [Hugging Face Space](https://huggingface.co/spaces/raia-center/PersianMMLU) |
| **[ParsiEval](https://github.com/mshojaei77/ParsiEval)** | ![Benchmark](https://img.shields.io/badge/Benchmark-emerald?style=flat-square) | Reasoning & Math | Evaluates logical reasoning, mathematics, and reading comprehension in Persian LLMs | [GitHub](https://github.com/mshojaei77/ParsiEval) |
| **[ParsBench](https://github.com/ParsBench/ParsBench)** | ![Toolkit](https://img.shields.io/badge/Toolkit-slate?style=flat-square) | Downstream Task Suite | Benchmarking toolkits and synthetic test suites for frontier Persian tasks | [GitHub](https://github.com/ParsBench/ParsBench) |
| **[TAAROFBENCH](https://github.com/niktaas/TAAROFBENCH)** | ![Research](https://img.shields.io/badge/EMNLP_2025-blue?style=flat-square) | Pragmatics & Culture | Evaluates LLM understanding of Iranian cultural politeness (*Taarof*), irony, and indirect discourse | [GitHub](https://github.com/niktaas/TAAROFBENCH) |

---

## 4. 🤖 Agentic Frameworks & Production Agents

| Project | Badges | Type | Capabilities & Production Scope | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[LangGraph Multi-Agent Persian](https://github.com/SaharZarbafi/langgraph-multi-agent-persian)** | ![Agent](https://img.shields.io/badge/Multi--Agent-amber?style=flat-square) | Multi-Agent Swarm | Production architecture with Actor-Critic self-critique loops and heterogeneous model routing | [GitHub](https://github.com/SaharZarbafi/langgraph-multi-agent-persian) |
| **[Rebex (IranRebate AI Agent)](https://github.com/razavioo/iranrebate-ai-agent)** | ![Agent](https://img.shields.io/badge/Finance--Agent-amber?style=flat-square) | Financial Agent | Persian workspace for market analysis, trader research, and forex broker transparency | [GitHub](https://github.com/razavioo/iranrebate-ai-agent) |
| **[Local SQL Agent (Persian)](https://github.com/alisadeghiaghili/local-sql-agent)** | ![Agent](https://img.shields.io/badge/Text--to--SQL-amber?style=flat-square) | Text-to-SQL | AST-validated natural-language-to-SQL engine for enterprise databases with column ACLs | [GitHub](https://github.com/alisadeghiaghili/local-sql-agent) |
| **[Doctor Agent](https://github.com/SirBNL/doctor-agent)** | ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) | Medical Scheduler | Persian appointment booking agent with zero-shot local tool calling via Ollama | [GitHub](https://github.com/SirBNL/doctor-agent) |
| **[Phone Agent](https://github.com/sepehr071/phone-agent)** | ![Agent](https://img.shields.io/badge/Voice--Agent-amber?style=flat-square) | Telephony Receptionist | Automated PBX receptionist connected over Asterisk AudioSocket (STT -> LLM -> TTS in real-time) | [GitHub](https://github.com/sepehr071/phone-agent) |
| **[Micky Voice Assistant](https://github.com/xmannii/micky)** | ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) | Desktop Assistant | Persian-first agentic voice assistant with modular system actions and modern UX | [GitHub](https://github.com/xmannii/micky) |
| **[Moujez Summarizer Agent](https://github.com/kharazi/moujez)** | ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) | Summarization | Structured extractive and abstractive summarization agent for long Persian documents | [GitHub](https://github.com/kharazi/moujez) |

---

## 5. 🛡️ LLM Security, Guardrails & Jailbreak Defense

| Tool / Research | Badges | Focus Area | Description | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[MCI LLM Security Hackathon Archive](https://github.com/erfnzdeh/MCI-LLM-Security-Hackathon)** | ![Security](https://img.shields.io/badge/Security-red?style=flat-square) | Jailbreak Testing | Empirical study of safety jailbreaks across 14 prohibited domains using cross-lingual framing attacks | [GitHub](https://github.com/erfnzdeh/MCI-LLM-Security-Hackathon) |
| **[Persian LLM Security Evaluation](https://github.com/Haniyesabeghi/Persian-LLM-Security-Evaluation-BA)** | ![Security](https://img.shields.io/badge/Security-red?style=flat-square) | Prompt Injection | Vulnerability analysis and defense strategies against prompt injections in Dorna and Maral | [GitHub](https://github.com/Haniyesabeghi/Persian-LLM-Security-Evaluation-BA) |
| **[Morphological Type Guards (MTG)](https://github.com/Moshe-ship/mtg)** | ![Security](https://img.shields.io/badge/Security-red?style=flat-square) | Tool Call Integrity | Typed validation layer preventing BiDi/RTL homoglyph spoofing and Unicode confusable attacks (UTS #39) | [GitHub](https://github.com/Moshe-ship/mtg) |
| **[PAIB Benchmark](https://github.com/Romohub/paib)** | ![Security](https://img.shields.io/badge/Security-red?style=flat-square) | Agent Integrity | Integrity benchmark verifying agent resistance against unauthorized tool calls and prompt overrides | [GitHub](https://github.com/Romohub/paib) |

---

## 6. ⚖️🩺 Specialized Domain AI: LegalTech & Healthcare

| Project | Badges | Domain | Functional Capabilities | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[Persian Legal Practice OS](https://github.com/ansariaiadmin/legal-platform)** | ![LegalTech](https://img.shields.io/badge/LegalTech-violet?style=flat-square) | LegalTech | Self-hosted legal OS for Iranian attorneys featuring 6 specialized agents and tri-hybrid RAG | [GitHub](https://github.com/ansariaiadmin/legal-platform) |
| **[Persian Legal RAG Agent](https://github.com/Hamidreza-Talei/persian-legal-rag-agent)** | ![LegalTech](https://img.shields.io/badge/LegalTech-violet?style=flat-square) | Case Law QA | Statutory question answering for Iranian civil and penal codes using LanceDB and rerankers | [GitHub](https://github.com/Hamidreza-Talei/persian-legal-rag-agent) |
| **[Smart Legal Letterhead](https://github.com/ahmadsalamifar/smart-legal-letterhead)** | ![LegalTech](https://img.shields.io/badge/LegalTech-violet?style=flat-square) | Document Automation | Automated Persian legal document generator with formal formatting and terminology validation | [GitHub](https://github.com/ahmadsalamifar/smart-legal-letterhead) |
| **[PerMed (Persian Meditron)](https://github.com/neda-kheirkhah/PerMed)** | ![Healthcare](https://img.shields.io/badge/Healthcare-teal?style=flat-square) | Clinical LLM | Specialized clinical language model fine-tuned on Meditron for Persian healthcare inquiries | [GitHub](https://github.com/neda-kheirkhah/PerMed) |
| **[Persian Medical RAG Chatbot](https://github.com/yousef-mousavizade/Persian-Medical-RAG-Chatbot)** | ![Healthcare](https://img.shields.io/badge/Healthcare-teal?style=flat-square) | Pharma Assistant | Reliable pharmaceutical and clinical assistant grounded on verified Iranian medical formularies | [GitHub](https://github.com/yousef-mousavizade/Persian-Medical-RAG-Chatbot) |
| **[OSCE AI Tutor](https://github.com/NafisSam/osce-tutor)** | ![Healthcare](https://img.shields.io/badge/Healthcare-teal?style=flat-square) | Clinical Simulation | Interactive clinical OSCE examination simulator for Persian medical students | [GitHub](https://github.com/NafisSam/osce-tutor) |

---

## 7. 🎙️ Speech Processing: STT & TTS

### 7.1. Speech-to-Text (STT / ASR)

| Model / Service | Badges | Architecture / Type | Highlights | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[wav2vec2-large-xlsr-53-persian](https://huggingface.co/jonatasgrosman/wav2vec2-large-xlsr-53-persian)** | ![STT](https://img.shields.io/badge/STT-blue?style=flat-square) | Wav2Vec2 | Most downloaded Persian speech recognition model on Hugging Face (~1M downloads) | [Hugging Face](https://huggingface.co/jonatasgrosman/wav2vec2-large-xlsr-53-persian) |
| **[Wav2Vec2 Persian v3](https://huggingface.co/m3hrdadfi/wav2vec2-large-xlsr-persian-v3)** | ![STT](https://img.shields.io/badge/STT-blue?style=flat-square) | Wav2Vec2 | State-of-the-art acoustic model fine-tuned on clean Persian audio benchmarks | [Hugging Face](https://huggingface.co/m3hrdadfi/wav2vec2-large-xlsr-persian-v3) |
| **[Whisper-Persian-v4](https://huggingface.co/nezamisafa/whisper-persian-v4)** | ![Whisper](https://img.shields.io/badge/Whisper-purple?style=flat-square) | Whisper Large-v3 | Fine-tuned for colloquial Persian phrases, mixed vocabularies, and noisy backgrounds | [Hugging Face](https://huggingface.co/nezamisafa/whisper-persian-v4) |
| **[Video Transcript Tool](https://github.com/razavioo/video-transcript-tool)** | ![Offline](https://img.shields.io/badge/Audio--Tool-emerald?style=flat-square) | Local CLI / App | Practical CLI tool turning Persian/English videos into clean reviewed transcripts and AI dubbing | [GitHub](https://github.com/razavioo/video-transcript-tool) |
| **[Persian ASR Leaderboard](https://huggingface.co/spaces/navidved/open_persian_asr_leaderboard)** | ![Leaderboard](https://img.shields.io/badge/Leaderboard-pink?style=flat-square) | Benchmark | Competitive Word Error Rate (WER) benchmark comparing Persian speech models | [Hugging Face Space](https://huggingface.co/spaces/navidved/open_persian_asr_leaderboard) |
| **[PersianScribe](https://github.com/duuuude/PersianScribe-for-Apple-Silicon)** | ![Offline](https://img.shields.io/badge/Offline-emerald?style=flat-square) | Apple Silicon Optimized | Native Mac speech-to-text with speaker diarization optimized for Apple Silicon (M1-M4) | [GitHub](https://github.com/duuuude/PersianScribe-for-Apple-Silicon) |
| **[Nemotron ASR Streaming Farsi](https://huggingface.co/mehdi-hf/nemotron-asr-streaming-farsi)** | ![Streaming](https://img.shields.io/badge/Streaming-cyan?style=flat-square) | NVIDIA Nemotron | Ultra-low latency streaming speech recognition based on NVIDIA Nemotron architecture | [Hugging Face](https://huggingface.co/mehdi-hf/nemotron-asr-streaming-farsi) |
| **[FarsAva](https://amerandish.com)** | ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) | Commercial API | Industrial-grade commercial speech recognition API by Amerandish | [amerandish.com](https://amerandish.com) |
| **[IoType](https://www.iotype.com/api)** | ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) | Cloud API | Cloud speech-to-text API offering audio transcription and editing endpoints | [iotype.com](https://www.iotype.com/api) |

### 7.2. Text-to-Speech & Voice Cloning (TTS)

| Model / System | Badges | Type | Strengths & Characteristics | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[Chatterbox-TTS-Persian-Farsi](https://huggingface.co/Thomcles/Chatterbox-TTS-Persian-Farsi)** | ![TTS](https://img.shields.io/badge/TTS-purple?style=flat-square) | Neural TTS | High-fidelity natural speech synthesis model with emotional prosody and clean pitch | [Hugging Face](https://huggingface.co/Thomcles/Chatterbox-TTS-Persian-Farsi) |
| **[Pocket TTS Farsi](https://huggingface.co/Nimaone/pocket-tts-farsi-v2-onnx)** | ![Lightweight](https://img.shields.io/badge/Lightweight-teal?style=flat-square) | ONNX Runtime | Compact ONNX voice model suitable for mobile, embedded devices, and low-power servers | [Hugging Face](https://huggingface.co/Nimaone/pocket-tts-farsi-v2-onnx) |
| **[persian_tts](https://github.com/nimaone/persian_tts)** | ![Offline](https://img.shields.io/badge/Offline-emerald?style=flat-square) | Voice Cloning | Offline CPU voice synthesis with zero-shot voice cloning capabilities | [GitHub](https://github.com/nimaone/persian_tts) |
| **[Mana Persian Piper](https://huggingface.co/MahtaFetrat/Mana-Persian-Piper)** | ![Piper](https://img.shields.io/badge/Piper-orange?style=flat-square) | Piper TTS | Piper TTS model trained on balanced multi-speaker Persian speech with correct phonemes | [Hugging Face](https://huggingface.co/MahtaFetrat/Mana-Persian-Piper) |
| **[dcho Voice Engine](https://github.com/AliAkrami1375/dcho)** | ![Edge](https://img.shields.io/badge/Edge-blue?style=flat-square) | Embedded Engine | Fast neural TTS designed for smart speakers, edge appliances, and microcontrollers | [GitHub](https://github.com/AliAkrami1375/dcho) |
| **[Gooya Bozorg](https://github.com/Reza2kn/gooya-bozorg-native)** | ![Desktop](https://img.shields.io/badge/Desktop-slate?style=flat-square) | Desktop App | Native cross-platform desktop application for offline reading of long Persian texts | [GitHub](https://github.com/Reza2kn/gooya-bozorg-native) |

---

## 8. 👁️ Computer Vision, OCR & Multimodal

| Model / Suite | Badges | Architecture | Task Scope | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[CLIPfa](https://github.com/sajjjadayobi/CLIPfa)** | ![Multimodal](https://img.shields.io/badge/Multimodal-pink?style=flat-square) | Dual-Encoder CLIP | Persian multimodal model connecting images and text for zero-shot search and categorization | [GitHub](https://github.com/sajjjadayobi/CLIPfa) |
| **[Qwen2-VL Persian OCR](https://huggingface.co/mohajesmaeili/Qwen3-VL-2B-Persian-Arabic-Ocr-v1.0)** | ![Vision-LLM](https://img.shields.io/badge/Vision--LLM-purple?style=flat-square) | Vision-Language | Digitizes handwritten manuscripts, mixed language pages, and complex formulas | [Hugging Face](https://huggingface.co/mohajesmaeili/Qwen3-VL-2B-Persian-Arabic-Ocr-v1.0) |
| **[Persian OCR Master](https://github.com/JENOVASir/persianAi-OCR-MASTER)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Web OCR | High-precision recognition of handwritten notes and math symbols with Word export | [GitHub](https://github.com/JENOVASir/persianAi-OCR-MASTER) |
| **[PDF-OCR-Math2LaTeX](https://github.com/Sadeghizad/pdf-ocr-fas-eng-math2latex)** | ![LaTeX](https://img.shields.io/badge/LaTeX-blue?style=flat-square) | OCR + LaTeX Parser | Performs bilingual Persian/English OCR and converts equations into valid LaTeX syntax | [GitHub](https://github.com/Sadeghizad/pdf-ocr-fas-eng-math2latex) |
| **[Hezar Vision](https://github.com/hezarai/hezar)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Vision Transformers | Models for Iranian license plate recognition, national ID cards, and document parsing | [GitHub](https://github.com/hezarai/hezar) |
| **[Iran OCR](https://www.iranocr.ir)** | ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) | Commercial API | Cloud OCR API for scanned Persian administrative archives and PDF images | [iranocr.ir](https://www.iranocr.ir) |

---

## 9. 📚 Persian Embeddings & Enterprise RAG

### 9.1. Embedding Models

| Model | Badges | Base Architecture | Specialization | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[Tooka-SBERT (Part AI)](https://huggingface.co/PartAI/Tooka-SBERT-V2-Large)** | ![Top-Embedding](https://img.shields.io/badge/Top--Embedding-emerald?style=flat-square) | Sentence-BERT | State-of-the-art Persian Sentence-BERT model for semantic retrieval and passage ranking | [Hugging Face](https://huggingface.co/PartAI/Tooka-SBERT-V2-Large) |
| **[Persian Embeddings](https://huggingface.co/heydariAI/persian-embeddings)** | ![Top-Embedding](https://img.shields.io/badge/Top--Embedding-emerald?style=flat-square) | Sentence Transformers | Top-rated Persian sentence embedding model trained on semantic similarity corpora | [Hugging Face](https://huggingface.co/heydariAI/persian-embeddings) |
| **[BGE-M3 Multilingual](https://github.com/FlagOpen/FlagEmbedding)** | ![Multilingual](https://img.shields.io/badge/Multilingual-blue?style=flat-square) | Multi-Stage Transformer | Multilingual model with robust support for complex Persian semantic retrieval across dense and sparse queries | [GitHub](https://github.com/FlagOpen/FlagEmbedding) |
| **[ParsBERT NLI](https://huggingface.co/parsi-ai-nlpclass/ParsBERT-nli-FarsTail-FarSick)** | ![NLI](https://img.shields.io/badge/NLI-violet?style=flat-square) | RoBERTa / BERT | Natural language inference model for document contradiction and entailment verification | [Hugging Face](https://huggingface.co/parsi-ai-nlpclass/ParsBERT-nli-FarsTail-FarSick) |

### 9.2. Enterprise RAG Pipelines

| Solution | Badges | Architecture | Production Capabilities | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[PersianRAG](https://github.com/TahaBakhtari/PersianRAG)** | ![RAG](https://img.shields.io/badge/RAG-amber?style=flat-square) | Vector RAG | Ready-to-deploy question answering pipeline over Persian PDF archives | [GitHub](https://github.com/TahaBakhtari/PersianRAG) |
| **[Bank Chatbot Legal RAG](https://github.com/Muhammad-davoudi/bank-chatbot)** | ![RAG](https://img.shields.io/badge/RAG-amber?style=flat-square) | Anti-Hallucination RAG | Production RAG system for Iranian banking circulars with anti-hallucination guardrails | [GitHub](https://github.com/Muhammad-davoudi/bank-chatbot) |

---

## 10. 🛠️ Persian NLP Toolkits & Normalizers

| Library | Badges | Language | Description | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[DadmaTools](https://github.com/Dadmatech/DadmaTools)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Python | Comprehensive Persian NLP toolkit from Dadmatech; lemmatizer, dependency parser, POS tagger, and summarizer | [GitHub](https://github.com/Dadmatech/DadmaTools) |
| **[Hezar](https://github.com/hezarai/hezar)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Python | High-level library unifying Hugging Face transformers, vision, and speech under a clean API | [GitHub](https://github.com/hezarai/hezar) |
| **[ParsiNLU](https://github.com/persiannlp/parsinlu)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Python | High-level evaluation benchmark suite covering reading comprehension, entailment, and question generation | [GitHub](https://github.com/persiannlp/parsinlu) |
| **[Persian-Tools](https://github.com/persian-tools/persian-tools)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | TS / Py / Go / Rust | Battle-tested library for National Code, Sheba, card validation, and Jalali date parsing across 8 languages | [GitHub](https://github.com/persian-tools/persian-tools) |
| **[Hazm](https://github.com/roshan-research/hazm)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Python | Pioneer Persian text tokenization, stemming, and POS tagging toolkit by Roshan Research | [GitHub](https://github.com/roshan-research/hazm) |
| **[Parsivar](https://github.com/ICTRC/Parsivar)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Python | Text pre-processing library adhering strictly to the Academy of Persian Language and Literature rules | [GitHub](https://github.com/ICTRC/Parsivar) |
| **[Persian-NER](https://github.com/Text-Mining/Persian-NER)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Dataset | Largest tagged Named Entity Recognition (NER) corpus and toolkit for Persian | [GitHub](https://github.com/Text-Mining/Persian-NER) |
| **[Persian AI Glossary](https://github.com/snrazavi/Persian-AI-and-Machine-Learning-Glossary)** | ![Docs](https://img.shields.io/badge/Docs-blue?style=flat-square) | Markdown | Standard Persian translations for AI, Deep Learning, and data science terminology | [GitHub](https://github.com/snrazavi/Persian-AI-and-Machine-Learning-Glossary) |

---

## 11. 🌐 Neural Machine Translation (NMT)

| Model / App | Badges | Architecture | Scope & Quality | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[mT5-ParsiNLU Opus Translation](https://huggingface.co/persiannlp/mt5-small-parsinlu-opus-translation_fa_en)** | ![NMT](https://img.shields.io/badge/NMT-purple?style=flat-square) | Google mT5 | High-quality bidirectional English/Persian neural translation model (>50k downloads) | [Hugging Face](https://huggingface.co/persiannlp/mt5-small-parsinlu-opus-translation_fa_en) |
| **[Persian LoRA Translator](https://github.com/Mahdi-Maaref/Persian-To-English-Translator)** | ![PEFT](https://img.shields.io/badge/PEFT-teal?style=flat-square) | LoRA Adapter | Resource-efficient LoRA adapter for fast real-world translation serving on modest hardware | [GitHub](https://github.com/Mahdi-Maaref/Persian-To-English-Translator) |
| **[EPUB AI Translator](https://github.com/Retro-Zero/epub-ai-translator)** | ![Web-App](https://img.shields.io/badge/Web--App-blue?style=flat-square) | Translation Engine | Translates entire e-books into fluent Persian while preserving chapter styling and RTL layout | [GitHub](https://github.com/Retro-Zero/epub-ai-translator) |

---

## 12. 🖥️ AI Interfaces, Agent DevTools & RTL Tools

| Tool | Badges | Environment | Purpose & Fix | Link |
| :--- | :---: | :---: | :--- | :---: |
| **[opencode-rtl](https://github.com/razavioo/opencode-rtl)** | ![DevTool](https://img.shields.io/badge/OpenCode--Plugin-blue?style=flat-square) | OpenCode CLI | Comprehensive right-to-left language plugin for opencode CLI; preserves code blocks and terminal outputs | [GitHub](https://github.com/razavioo/opencode-rtl) |
| **[RTL Support for VS Code Agents](https://github.com/GuyRonnen/rtl-for-vs-code-agents)** | ![VS-Code](https://img.shields.io/badge/VS--Code-blue?style=flat-square) | VS Code / Copilot | Native-like RTL rendering in VS Code AI agents while keeping English code blocks cleanly LTR formatted | [GitHub](https://github.com/GuyRonnen/rtl-for-vs-code-agents) |
| **[Kivun Terminal](https://github.com/noambrand/kivun-terminal-wsl)** | ![Terminal](https://img.shields.io/badge/Terminal-slate?style=flat-square) | CLI Terminal | Cross-platform terminal with a native BiDi engine ensuring Claude Code renders without reversed characters | [GitHub](https://github.com/noambrand/kivun-terminal-wsl) |
| **[BiDi Shaper](https://github.com/cc1a2b/bidi-shaper)** | ![Text-Shaping](https://img.shields.io/badge/Text--Shaping-emerald?style=flat-square) | Standalone Lib | Zero-dependency Unicode UAX #9 engine and glyph shaper for Canvas, WebGL, three.js, and terminals | [GitHub](https://github.com/cc1a2b/bidi-shaper) |
| **[Nimruz Desktop](https://github.com/xmannii/nimruz-desktop)** | ![Desktop](https://img.shields.io/badge/Desktop-slate?style=flat-square) | Desktop GUI | Elegant desktop client with Persian-first typography for chatting with local and remote LLMs | [GitHub](https://github.com/xmannii/nimruz-desktop) |
| **[Hermes Agent Farsi](https://github.com/m4tinbeigi-official/hermes-agent-farsi)** | ![UI-Mod](https://img.shields.io/badge/UI--Mod-orange?style=flat-square) | Web Dashboard | One-click localization, RTL layout, and Vazirmatn font styling for Nous Hermes Agent dashboards | [GitHub](https://github.com/m4tinbeigi-official/hermes-agent-farsi) |
| **[Persian AI RTL Assistant](https://github.com/tig-ndi/persian-ai-rtl-assistant)** | ![Browser](https://img.shields.io/badge/Browser-sky?style=flat-square) | Browser Extension | Automatically enforces RTL text alignment on ChatGPT, Claude, and DeepSeek web clients | [GitHub](https://github.com/tig-ndi/persian-ai-rtl-assistant) |
| **[Persian Text to PDF Converter](https://github.com/Ho3seinTork/Persian-Text-to-PDF-Converter)** | ![Web-App](https://img.shields.io/badge/Web--App-blue?style=flat-square) | Web Tool | Converts markdown LLM outputs into cleanly shaped Persian PDF documents without font corruption | [GitHub](https://github.com/Ho3seinTork/Persian-Text-to-PDF-Converter) |
| **[Reply RTL Viewer](https://github.com/shahriyar3/reply-rtl-viewer)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Markdown Viewer | Single-file markdown viewer with BiDi isolation preventing mixed Latin/Persian code garbling | [GitHub](https://github.com/shahriyar3/reply-rtl-viewer) |

---

## 13. 📊 AI Datasets & Corpora

| Dataset | Badges | Modality / Task | Volume | Description | Link |
| :--- | :---: | :---: | :---: | :--- | :---: |
| **[PersianQA](https://github.com/sajjjadayobi/PersianQA)** | ![QA](https://img.shields.io/badge/QA-violet?style=flat-square) | Reading Comprehension | 9,000+ pairs | Gold-standard Persian reading comprehension dataset based on Persian Wikipedia | [GitHub](https://github.com/sajjjadayobi/PersianQA) |
| **[ManaTTS Speech Dataset](https://github.com/MahtaFetrat/ManaTTS-Persian-Speech-Dataset)** | ![Audio](https://img.shields.io/badge/Audio-orange?style=flat-square) | Audio / Speech | 114+ hours | Largest open transcribed Persian speech corpus containing high-quality speech | [GitHub](https://github.com/MahtaFetrat/ManaTTS-Persian-Speech-Dataset) |
| **[Persian Raw Text (80GB)](https://github.com/persiannlp/persian-raw-text)** | ![Corpus](https://img.shields.io/badge/Corpus-blue?style=flat-square) | Plain Text | 80 GB | Deduplicated, cleaned raw text for pre-training large language models | [GitHub](https://github.com/persiannlp/persian-raw-text) |
| **[SentiPers Corpus](https://github.com/phosseini/SentiPers)** | ![Sentiment](https://img.shields.io/badge/Sentiment-red?style=flat-square) | Sentiment Classification | Benchmark | Standard sentiment analysis corpus for Persian reviewed and published on arXiv | [GitHub](https://github.com/phosseini/SentiPers) |
| **[FarsInstruct](https://huggingface.co/datasets/ParsiAI/FarsInstruct)** | ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) | Instruction Tuning | Multi-Turn | Large-scale instruction-tuning dataset for aligning Persian assistants and chat models | [Hugging Face](https://huggingface.co/datasets/ParsiAI/FarsInstruct) |
| **[Alpaca Persian](https://huggingface.co/datasets/sinarashidi/alpaca-persian)** | ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) | Instruction Tuning | 52,000 items | Persian translation and cultural adaptation of the Stanford Alpaca 52k dataset | [Hugging Face](https://huggingface.co/datasets/sinarashidi/alpaca-persian) |
| **[Persian Voice v1](https://huggingface.co/datasets/vhdm/persian-voice-v1)** | ![Audio](https://img.shields.io/badge/Audio-orange?style=flat-square) | Speech Dataset | Multi-Speaker | Multi-speaker speech dataset for voice cloning and acoustic modeling | [Hugging Face](https://huggingface.co/datasets/vhdm/persian-voice-v1) |
| **[Persian Wikipedia QA](https://huggingface.co/datasets/fibonacciai/Persian-Wikipedia-QA)** | ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) | Encyclopedic QA | Knowledge Pairs | Open QA dataset extracted from encyclopedic articles for training RAG retrievers | [Hugging Face](https://huggingface.co/datasets/fibonacciai/Persian-Wikipedia-QA) |
| **[GPTInformal Speech Dataset](https://github.com/MahtaFetrat/GPTInformal-Persian-Speech-Dataset)** | ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) | Conversational Audio | 6+ hours | Informal speech-to-text pairs for conversational fine-tuning | [GitHub](https://github.com/MahtaFetrat/GPTInformal-Persian-Speech-Dataset) |
| **[MirasText & Hamshahri Corpus](https://github.com/mhbashari/awesome-persian-nlp-ir)** | ![Corpus](https://img.shields.io/badge/Corpus-blue?style=flat-square) | News & Encyclopedic | Multi-Million | Multi-million-article journalistic corpora for historical and language modeling research | [GitHub](https://github.com/mhbashari/awesome-persian-nlp-ir) |

---

## 👥 Maintainers & Community

Maintained and curated by the **[Kalahamoon (کالاهامون)](https://github.com/Kalahamoon)** organization alongside the Iranian AI and open-source engineering community worldwide.

---

## 📜 License

Released under the permissive **[MIT License](LICENSE)**.
