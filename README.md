# Awesome Persian AI & MCP Hub

<div align="center">

![Awesome Persian AI Banner](assets/banner.svg)

<br/>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Organization](https://img.shields.io/badge/Org-Kalahamoon-6366f1.svg?style=flat-square)](https://github.com/Kalahamoon)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-10b981.svg?style=flat-square)](CONTRIBUTING.md)
[![Persian Typography](https://img.shields.io/badge/ZWNJ-Standard_Persian-0ea5e9.svg?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-f59e0b.svg?style=flat-square)](LICENSE)

<br/>

**هاب متمرکز، مهندسی‌شده و جامع ابزارها، پروتکل MCP، مدل‌های زبانی، سرویس‌های ابری و زیرساخت‌های هوش مصنوعی برای زبان فارسی و ایران.**

*The definitive community hub for Persian AI: Model Context Protocol (MCP) servers, LLMs, Agentic Tools, Datasets, and Local Cloud Gateways.*

[مشارکت و افزودن ابزار جدید](CONTRIBUTING.md) • [گزارش خطا / پیشنهاد](https://github.com/Kalahamoon/awesome-persian-ai/issues)

</div>

---

## 🧭 فهرست دسته‌بندی‌ها / Table of Contents

- [🔌 سرورها و ابزارهای پروتکل MCP (Model Context Protocol)](#1--سرورها-و-ابزارهای-پروتکل-mcp-model-context-protocol)
  - [اتصال به پلتفرم‌های ایرانی و سازمانی](#11-اتصال-به-پلتفرمهای-ایرانی-و-سازمانی)
  - [ابزارهای تقویم، زمان و داده‌های بومی](#12-ابزارهای-تقویم-زمان-و-دادههای-بومی)
  - [کلاینت‌ها و فریم‌ورک‌های توسعه MCP](#13-کلاینتها-و-فریمورکهای-توسعه-mcp)
- [🧠 مدل‌های زبانی و بنیادی فارسی (LLMs & Foundation Models)](#2--مدلهای-زبانی-و-بنیادی-فارسی-llms--foundation-models)
  - [مدل‌های متن‌باز و وزن‌های قابل دانلود](#21-مدلهای-متنباز-و-وزنهای-قابل-دانلود)
  - [فریم‌ورک‌ها و بنچ‌مارک‌های ارزیابی (Eval Harnesses)](#22-فریمورکها-و-بنچمارکهای-ارزیابی-eval-harnesses)
- [☁️ پلتفرم‌های ابری و درگاه‌های API (Cloud & Gateways)](#3--پلتفرمهای-ابری-و-درگاههای-api-cloud--gateways)
  - [درگاه‌های ارائه‌دهنده مدل‌های زبانی (LLM Gateways)](#31-درگاههای-ارائهدهنده-مدلهای-زبانی-llm-gateways)
  - [زیرساخت‌های پردازش ابری و سرورهای GPU](#32-زیرساختهای-پردازش-ابری-و-سرورهای-gpu)
- [🎙️ پردازش گفتار و صوت (Speech: STT & TTS)](#4--پردازش-گفتار-و-صوت-speech-stt--tts)
  - [تبدیل گفتار به متن (Speech to Text - STT)](#41-تبدیل-گفتار-به-متن-speech-to-text---stt)
  - [تبدیل متن به گفتار (Text to Speech - TTS)](#42-تبدیل-متن-به-گفتار-text-to-speech---tts)
- [👁️ بینایی ماشین و سندکاوی (Vision & OCR)](#5--بینایی-ماشین-و-سندکاوی-vision--ocr)
- [📚 ابزارهای بازیابی اطلاعات و RAG بومی (Persian RAG & Embeddings)](#6--ابزارهای-بازیابی-اطلاعات-و-rag-بومی-persian-rag--embeddings)
  - [مدل‌های برداری (Embeddings)](#61-مدلهای-برداری-embeddings)
  - [فریم‌ورک‌ها و پایپ‌لاین‌های آماده RAG](#62-فریمورکها-و-پایپلاینهای-آماده-rag)
- [🛠️ کتابخانه‌ها و ابزارهای مهندسی زبان (Persian NLP Toolkits)](#7--کتابخانهها-و-ابزارهای-مهندسی-زبان-persian-nlp-toolkits)
- [🖥️ افزونه‌ها، ابزارهای مرورگر و رابط‌های کاربری (Extensions & RTL)](#8--افزونهها-ابزارهای-مرورگر-و-رابطهای-کاربری-extensions--rtl)
- [📊 دیتاست‌ها و منابع یادگیری (Datasets & Corpora)](#9--دیتاستها-و-منابع-یادگیری-datasets--corpora)

---

## 1. 🔌 سرورها و ابزارهای پروتکل MCP (Model Context Protocol)

پروتکل **MCP (Model Context Protocol)** استانداردی است که به دستیارهای هوش مصنوعی و مدل‌های زبانی (مثل Claude Desktop، Cursor، Windsurf و OpenCode) اجازه می‌دهد مستقیماً با سامانه‌ها و پایگاه‌های داده ارتباط برقرار کنند. در این بخش، سرورهای بومی پیاده‌سازی‌شده یا سازگار فهرست شده‌اند:

### 1.1. اتصال به پلتفرم‌های ایرانی و سازمانی

| عنوان سرور / پروژه | توضیحات عملکردی | پشته / زبان | وضعیت |
| :--- | :--- | :--- | :---: |
| **Kasra MCP Server** | دسترسی دستیار هوش مصنوعی به سامانه جامع تردد و پرسنلی کسرا (مشاهده کارکرد، ترددها، ثبت و لغو مرخصی و مأموریت ساعتی/روزانه) | Python / FastMCP | 🟢 پایدار |
| **Bale Messenger MCP** | کنترل کامل پیام‌رسان بله توسط هوش مصنوعی (دریافت مکالمات، جستجو در پیام‌ها و ارسال خودکار پیام به مخاطبان تاییدشده با تایید دو‌مرحله‌ای) | Python / Stdio | 🟢 پایدار |
| **APIs-made-in-Iran Catalog** | کاتالوگ و ایندکس جامع صدها وب‌سرویس و API عمومی ایرانی جهت فراخوانی توسط دستیارهای ایجنتیک | JSON / Spec | 🟢 فعال |

### 1.2. ابزارهای تقویم، زمان و داده‌های بومی

| عنوان سرور / ابزار | توضیحات عملکردی | پشته / زبان |
| :--- | :--- | :--- |
| **Jalali Date Engine** | تبدیل دقیق تقویم شمسی/میلادی/قمری، استخراج روزهای کاری و تعطیلات رسمی ایران با الگوریتم دقیق ۳۳ ساله | TypeScript / Node.js |
| **TGJU Financial Feed (Agent Tool)** | ابزار استخراج زنده نرخ طلا، ارز، سکه و شاخص‌های مالی بازار ایران برای تحلیل ایجنت‌های هوش مصنوعی | Python / Scraper |
| **Torob & Digikala Product Search Tool** | ابزار جستجوی قیمت و مقایسه هوشمند محصولات در فروشگاه‌های اینترنتی ایران | Python |

### 1.3. کلاینت‌ها و فریم‌ورک‌های توسعه MCP

* **[FastMCP](https://github.com/jlowin/fastmcp)** — فریم‌ورک استاندارد و سریع برای ساخت سرورهای MCP در پایتون با دکوراتورهای خوانا و احراز هویت داخلی.
* **[Model Context Protocol SDKs](https://modelcontextprotocol.io)** — کیت‌های توسعه رسمی تایپ‌اسکریپت و پایتون برای اتصال به هوش مصنوعی.

---

## 2. 🧠 مدل‌های زبانی و بنیادی فارسی (LLMs & Foundation Models)

مدل‌های زبانی بزرگ که به‌طور ویژه برای زبان فارسی بازآموزی (Pretrain) یا پیش‌آموزی و تنظیم دقیق (Fine-tune) شده‌اند.

### 2.1. مدل‌های متن‌باز و وزن‌های قابل دانلود

| نام مدل | معماری پایه | اندازه پارامتر | توضیحات و لینک |
| :--- | :--- | :---: | :--- |
| **درنا (Dorna)** | LLaMA / Mistral | 8B / 7B | مدل بهینه‌شده برای درک مکالمات روزمره و اداری به زبان فارسی توسعه‌یافته توسط پارت. |
| **مرال (Maral-7B)** | Mistral-7B | 7B | از نخستین مدل‌های زبانی فارسی مبتنی بر میسترال با درک بالا از اصطلاحات ادبی و محاوره‌ای. |
| **سینا (Sina)** | LLaMA-3 | 8B | مدل زبانی فاین‌تیون‌شده روی پیکره‌های بزرگ زبان فارسی با توانایی بالا در استدلال و پرسش و پاسخ. |
| **Ava-LLM** | Qwen / Gemma | 2B / 7B | مدل‌های سبک و چابک با قابلیت اجرای کامل بر روی سخت‌افزارهای دسکتاپ و پردازنده‌های CPU با Ollama. |
| **هزار (Hezar Models)** | BERT / RoBERTa / T5 | گوناگون | مجموعه‌ای کامل از مدل‌های ترانسفورمر پیش‌آموزش‌دیده برای تسک‌های متنوع متن و صوت فارسی در پلتفرم هزار. |

### 2.2. فریم‌ورک‌ها و بنچ‌مارک‌های ارزیابی (Eval Harnesses)

* **[persian-llm-eval](https://github.com/heyparsadev/persian-llm-eval)** — بنچ‌مارک و چارچوب ارزیابی جامع مدل‌های زبانی در زبان فارسی شامل ۳۰۰ آزمون در ۱۰ شاخه تخصصی، ارزیابی قطعیت و لیدربورد مدل‌های برتر.
* **[Persian-LLM-Security-Evaluation](https://github.com/Haniyesabeghi/Persian-LLM-Security-Evaluation-BA)** — ارزیابی و پژوهش‌های امنیتی و تست مقاومت در برابر Prompt Injection در مدل‌های فارسی.

---

## 3. ☁️ پلتفرم‌های ابری و درگاه‌های API (Cloud & Gateways)

سرویس‌های ابری که دسترسی مستقیم، بدون تحریم و پایدار به مدل‌های هوش مصنوعی را برای کسب‌وکارها و توسعه‌دهندگان ایرانی فراهم می‌کنند:

### 3.1. درگاه‌های ارائه‌دهنده مدل‌های زبانی (LLM Gateways)

* **[AvalAI (اول‌آی)](https://avalai.ir)** — درگاه جامع ارائه‌دهنده‌ی API سازگار با فرمت OpenAI برای دسترسی به مدل‌های روز جهان (Claude 3.5، GPT-4o، DeepSeek V3/R1) با پرداخت ریالی و سرورهای پرسرعت.
* **[هوشیو (Hooshio)](https://hooshio.com)** — پایگاه تحلیلی و ارائه‌دهنده دسترسی‌های نوین به ابزارها و مدل‌های هوش مصنوعی.
* **[پارت دات آی‌آر (Part AI Hub)](https://partsoftware.com)** — مرکز خدمات هوش مصنوعی شامل درگاه مدل‌های پردازش زبان، هوش مالی و سرویس‌های احراز هویت هوشمند.
* **[مه‌پرتو (Mehparto)](https://mehparto.ir)** — سرویس‌های زیرساختی و رابط‌های برنامه‌نویسی برای هوش مصنوعی شرکتی در ایران.

### 3.2. زیرساخت‌های پردازش ابری و سرورهای GPU

* **[ابر آروان (ArvanCloud AI / GPU)](https://arvancloud.ir)** — ارائه‌دهنده سرورهای ابری مجهز به پردازنده‌های گرافیکی NVIDIA برای اجرای محلی مدل‌ها و فرآیندهای فاین‌تیون.
* **[ابر دراک (Derak Cloud)](https://derak.cloud)** — ارائه‌دهنده خدمات ابری، شبکه‌های لبه و زیرساخت‌های استقرار سرویس‌های هوش مصنوعی.

---

## 4. 🎙️ پردازش گفتار و صوت (Speech: STT & TTS)

مجموعه ابزارها و موتورهای تبدیل صوت به متن و متن به گفتار در زبان فارسی:

### 4.1. تبدیل گفتار به متن (Speech to Text - STT)

* **[OpenAI Whisper (Persian Fine-tunes)](https://github.com/devie-dev/persian-stt-models)** — نسخه‌های تنظیم‌شده مدل ویسپر اوپن‌ای‌آی با دقت خیره‌کننده در تشخیص لهجه‌ها و لحن‌های گفتاری زبان فارسی.
* **[Persian-STT (Oct4Pie)](https://github.com/Oct4Pie/persian-stt)** — مدل سبک استخراج متن از گفتار آموزش‌دیده روی فریم‌ورک Coqui STT.
* **[Farsi Speech Recognition API](https://github.com/karim23657/awesome-Persian-Speech)** — آرشیو جامع دیتاست‌ها و مدل‌های پردازش صوت زبان فارسی.

### 4.2. تبدیل متن به گفتار (Text to Speech - TTS)

* **[persian_tts (nimaone)](https://github.com/nimaone/persian_tts)** — تولید گفتار طبیعی فارسی با قابلیت کلون کردن صدا (Voice Cloning) به‌صورت کاملاً آفلاین روی پردازنده‌های معمولی (CPU) با ONNX Runtime.
* **[Persian-tts-coqui](https://github.com/karim23657/Persian-tts-coqui)** — پایپ‌لاین آموزش و اجرای مدل‌های خوانش متن فارسی با کیفیت استودیویی بر پایه Coqui TTS.
* **[dcho Engine](https://github.com/AliAkrami1375/dcho)** — موتور صوتی سبک و سریع متن‌باز مناسب برای استفاده در گجت‌های امبدد و دستیارهای صوتی محلی ایرانی.
* **[گویا بزرگ (Gooya Bozorg Native)](https://github.com/Reza2kn/gooya-bozorg-native)** — برنامه بومی دسکتاپ برای خوانش متن‌های طولانی فارسی بدون نیاز به اینترنت (Cross-platform).

---

## 5. 👁️ بینایی ماشین و سندکاوی (Vision & OCR)

* **[Persian OCR Master](https://github.com/JENOVASir/persianAi-OCR-MASTER)** — سیستم پیشرفته استخراج متون دست‌نویس و چاپی فارسی با پشتیبانی از فرمول‌های ریاضی و خروجی Word.
* **[Hezar Vision OCR](https://github.com/hezarai/hezar)** — مدل‌های تشخیص نویسه نوری فارسی آموزش‌دیده برای پلاک‌خوانی، کارت ملی، شناسنامه و متون اسکن‌شده.

---

## 6. 📚 ابزارهای بازیابی اطلاعات و RAG بومی (Persian RAG & Embeddings)

یکی از چالش‌های بنیادین در پیاده‌سازی سامانه‌های RAG، نبود پشتیبانی دقیق مدل‌های امبدینگ عمومی از زبان فارسی است. پروژه‌های این بخش این مشکل را رفع می‌کنند:

### 6.1. مدل‌های برداری (Embeddings)

* **[Persian-Sentence-Transformer](https://huggingface.co/models?search=persian-embedding)** — مدل‌های برداری تخصصی مبتنی بر BERT و RoBERTa برای درک شباهت معنایی جملات و پاراگراف‌های فارسی.
* **[BGE-M3 Multilingual (Persian Validated)](https://github.com/FlagOpen/FlagEmbedding)** — یکی از قدرتمندترین مدل‌های چندزبانه با پشتیبانی عالی و درک عمیق از جملات فارسی در کاربردهای بازیابی داده متنی (Dense & Sparse Retrieval).

### 6.2. فریم‌ورک‌ها و پایپ‌لاین‌های آماده RAG

* **[PersianRAG (TahaBakhtari)](https://github.com/TahaBakhtari/PersianRAG)** — پایپ‌لاین آماده پرسش و پاسخ هوشمند از روی اسناد و مستندات PDF فارسی با استفاده از معماری RAG.
* **[Bank-Chatbot (RAG)](https://github.com/Muhammad-davoudi/bank-chatbot)** — سیستم سازمانی پاسخگویی خودکار به قوانین بانکی و تسهیلات با تکنیک‌های پیشرفته Chunking در متون حقوقی و اداری ایران.

---

## 7. 🛠️ کتابخانه‌ها و ابزارهای مهندسی زبان (Persian NLP Toolkits)

ابزارهایی حیاتی برای آماده‌سازی، نرمال‌سازی متون و پاک‌سازی داده‌ها پیش از ارسال به مدل‌های زبانی:

| نام ابزار / کتابخانه | زبان / پلتفرم | کاربرد کلیدی |
| :--- | :---: | :--- |
| **[Hezar (هزار)](https://github.com/hezarai/hezar)** | Python (PyTorch) | کتابخانه همه‌منظوره هوش مصنوعی برای زبان فارسی با پشتیبانی از ترانسفورمرها، مدل‌های چندوجهی، طبقه‌بندی و تولید متن. |
| **[Persian-Tools](https://github.com/persian-tools/persian-tools)** | TypeScript / JS | ابزار پرسرعت و مدرن برای اعتبارسنجی کد ملی، تبدیل اعداد به حروف، اعتبارسنجی کارت بانکی و اصلاح کلمات. |
| **[Hazm (هضم)](https://github.com/roshan-research/hazm)** | Python | جعبه‌ابزار کلاسیک و شناخته‌شده پردازش زبان فارسی (ریشه‌یابی، تصحیح املا، تقطیع جملات و برچسب‌گذاری نحوی). |
| **[Parsivar (پارسی‌وار)](https://github.com/ICTRC/Parsivar)** | Python | مجموعه ابزار پیش‌پردازش متن زبان فارسی با تکیه بر دستور خط استاندارد و استخراج بن واژگان. |
| **[Persian-AI-Glossary](https://github.com/snrazavi/Persian-AI-and-Machine-Learning-Glossary)** | Markdown / Docs | واژه‌نامه تخصصی و استاندارد ترجمه اصطلاحات هوش مصنوعی و یادگیری ماشین به زبان فارسی. |

---

## 8. 🖥️ افزونه‌ها، ابزارهای مرورگر و رابط‌های کاربری (Extensions & RTL)

* **[Persian AI RTL Assistant](https://github.com/tig-ndi/persian-ai-rtl-assistant)** — افزونه مرورگر جهت اصلاح خودکار چیدمان راست‌به‌چپ (RTL)، تصحیح ترکیب کلمات انگلیسی و فارسی، و اعمال فونت زیبای وزیرمتن در پلتفرم‌های ChatGPT، Claude و Perplexity.
* **[Reply RTL Viewer](https://github.com/shahriyar3/reply-rtl-viewer)** — رندرکننده تک‌فایلی هوشمند Markdown با تفکیک هوشمند عبارات انگلیسی و فارسی و پشتیبانی از KaTeX و نمایش کدهای چندزبانه.

---

## 9. 📊 دیتاست‌ها و منابع یادگیری (Datasets & Corpora)

* **[Awesome-Persian-LLM](https://github.com/MohammadHeydari/Awesome-Persian-LLM)** — فهرست مقالات، اسناد پژوهشی و منابع آموزشی در حوزه مدل‌های زبانی بزرگ برای زبان فارسی.
* **[GPTInformal-Persian-Speech](https://github.com/MahtaFetrat/GPTInformal-Persian-Speech-Dataset)** — مجموعه‌داده صوتی بیش از ۶ ساعت گفتار محاوره‌ای فارسی همراه با برچسب متنی دقیق مناسب آموزش مدل‌های صوتی.
* **[Hamshahri & Miras Corpora](https://github.com/mhbashari/awesome-persian-nlp-ir)** — پیکره‌های بزرگ خبری و متنی زبان فارسی برای پیش‌آموزش و ارزیابی مدل‌های زبانی.

---

## 👥 سازندگان و حامیان (Maintainers & Backers)

این پروژه توسط سازمان **[Kalahamoon (کلاهمون)](https://github.com/Kalahamoon)** و با همراهی جامعه توسعه‌دهندگان، پژوهشگران و علاقه‌مندان به پیشرفت فناوری در زیست‌بوم فارسی نگهداری و گسترش داده می‌شود.

---

## 📜 مجوز (License)

این پروژه تحت مجوز متن‌باز **MIT** منتشر شده است. برای مطالعه جزئیات به فایل [LICENSE](LICENSE) مراجعه کنید.
