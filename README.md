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

## 🏷️ راهنمای برچسب‌ها و وضعیت‌ها (Badges & Legend)

برای اینکه در یک نگاه نوع دسترسی، مدل هزینه و نوع ابزار مشخص باشد، از سیستم برچسب‌گذاری زیر استفاده شده است:

| برچسب | عنوان | توضیحات |
| :---: | :--- | :--- |
| `[MCP]` | **پروتکل اتصال مدل** | سازگار با پروتکل Model Context Protocol و قابل فراخوانی مستقیم در ایجنت‌ها |
| `[Open-Source]` | **متن‌باز** | سورس‌کد و وزن‌های مدل به‌صورت رایگان و عمومی در گیت‌هاب یا هاگینگ‌فیس موجود است |
| `[API-Gateway]` | **درگاه API** | سرویس ارائه‌دهنده توکن و کلید API سازگار با استاندارد OpenAI / Claude |
| `[Free]` | **کاملاً رایگان** | استفاده بدون هزینه مالی و محدودیت پرداختی |
| `[Freemium]` | **اعتبار اولیه / حجمی** | دارای بسته تست رایگان با امکان خرید بسته‌های مصرفی |
| `[Commercial]` | **تجاری / سازمانی** | نیازمند اشتراک، خرید کلید تجاری یا قرارداد شرکتی |
| `[Iran-Access]` | **اینترانت ملی** | پایداری تضمین‌شده در شرایط محدودیت اینترنت بین‌الملل |
| `[No-VPN]` | **بدون نیاز به تحریم‌شکن** | دسترسی مستقیم و بدون مسدودسازی IP از داخل ایران |

---

## 🧭 فهرست دسته‌بندی‌ها / Table of Contents

- [1. 🔌 سرورها و ابزارهای پروتکل MCP (Model Context Protocol)](#1--سرورها-و-ابزارهای-پروتکل-mcp-model-context-protocol)
  - [1.1. سامانه‌ها و پلتفرم‌های بومی ایران](#11-سامانه‌ها-و-پلتفرمهای-بومی-ایران)
  - [1.2. فروشگاه‌ها و اکوسیستم‌های تجارت الکترونیک](#12-فروشگاهها-و-اکوسیستمهای-تجارت-الکترونیک)
  - [1.3. ابزارهای زمانی، تقویم و بازارهای مالی ایران](#13-ابزارهای-زمانی-تقویم-و-بازارهای-مالی-ایران)
- [2. ☁️ پلتفرم‌های ابری و درگاه‌های API (Cloud & Gateways)](#2--پلتفرمهای-ابری-و-درگاههای-api-cloud--gateways)
  - [2.1. درگاه‌های تجمیعی و ارائه‌دهنده توکن بدون تحریم](#21-درگاههای-تجمیعی-و-ارائهدهنده-توکن-بدون-تحریم)
  - [2.2. زیرساخت‌های ابری پردازش هوش مصنوعی و GPU](#22-زیرساختهای-ابری-پردازش-هوش-مصنوعی-و-gpu)
- [3. 🧠 مدل‌های زبانی و بنیادی فارسی (LLMs & Foundation Models)](#3--مدلهای-زبانی-و-بنیادی-فارسی-llms--foundation-models)
  - [3.1. مدل‌های متن‌باز و وزن‌های زبانی](#31-مدلهای-متنباز-و-وزنهای-زبانی)
  - [3.2. بنچ‌مارک‌ها و چارچوب‌های ارزیابی (Eval Harnesses)](#32-بنچمارکها-و-چارچوبهای-ارزیابی-eval-harnesses)
- [4. 🎙️ پردازش گفتار، صوت و دوبله (Speech: STT & TTS)](#4--پردازش-گفتار-صوت-و-دوبله-speech-stt--tts)
  - [4.1. تبدیل گفتار به متن (Speech-to-Text)](#41-تبدیل-گفتار-به-متن-speech-to-text)
  - [4.2. تبدیل متن به گفتار و شبیه‌سازی صدا (Text-to-Speech)](#42-تبدیل-متن-به-گفتار-و-شبیهسازی-صدا-text-to-speech)
- [5. 👁️ بینایی ماشین و سندکاوی (Vision, OCR & Document AI)](#5--بینایی-ماشین-و-سندکاوی-vision-ocr--document-ai)
- [6. 📚 ابزارهای بازیابی اطلاعات و RAG بومی (Persian RAG & Embeddings)](#6--ابزارهای-بازیابی-اطلاعات-و-rag-بومی-persian-rag--embeddings)
  - [6.1. مدل‌های برداری (Embedding Models)](#61-مدلهای-برداری-embedding-models)
  - [6.2. موتورها و پایپ‌لاین‌های آماده RAG سازمانی](#62-موتورها-و-پایپلاینهای-آماده-rag-سازمانی)
- [7. 🛠️ کتابخانه‌ها و ابزارهای مهندسی زبان (Persian NLP Toolkits)](#7--کتابخانهها-و-ابزارهای-مهندسی-زبان-persian-nlp-toolkits)
- [8. 🖥️ افزونه‌ها، ابزارهای مرورگر و رابط‌های کاربری (Extensions & RTL)](#8--افزونهها-ابزارهای-مرورگر-و-رابطهای-کاربری-extensions--rtl)
- [9. 📊 دیتاست‌ها و منابع ارزیابی داده (Datasets & Corpora)](#9--دیتاستها-و-منابع-ارزیابی-داده-datasets--corpora)

---

## 1. 🔌 سرورها و ابزارهای پروتکل MCP (Model Context Protocol)

پروتکل **MCP (Model Context Protocol)** استاندارد انقلابی شرکت آنتروپیک است که به دستیارهای هوش مصنوعی و مدل‌های زبانی (مثل Claude Desktop، Cursor، VS Code، OpenCode، Windsurf و Hermes) اجازه می‌دهد مستقیماً با پایگاه‌های داده و ابزارهای واقعی ارتباط برقرار کرده و دست به اقدام بزنند.

### 1.1. سامانه‌ها و پلتفرم‌های بومی ایران

| عنوان ابزار / سرور | برچسب‌ها | توضیحات عملکردی | پشته فنی | دسترسی |
| :--- | :---: | :--- | :---: | :---: |
| **Kasra MCP Server** | `[MCP]` `[Internal]` | ارتباط دستیار هوش مصنوعی با سامانه اتوماسیون تردد و پرسنلی کسرا؛ استخراج مانده مرخصی، وضعیت حضور و غیاب، و ثبت خودکار درخواست مجوز و ماموریت | Python / FastMCP | بومی |
| **Bale Messenger MCP** | `[MCP]` `[Open-Source]` | اتصال ایجنت‌های هوش مصنوعی به پیام‌رسان بله؛ خواندن تاریخچه پیام‌ها، سرچ در کانال‌ها و ارسال پیام تاییدمحور | Python / Stdio | بومی |
| **Hermes Agent Iran Gateway** | `[Agent]` `[Open-Source]` | گیت‌وی متن‌باز برای اتصال ایجنت‌های پیشرفته هرمس (Nous Hermes) به پلتفرم‌های بومی مانند بله و روبیکا | Python / LangGraph | [مخزن](https://github.com/hnkwing/hermes-agent-iran-gateway) |
| **APIs-made-in-Iran Catalog** | `[Tools]` `[Open-Source]` | ایندکس دسته‌بندی‌شده صدها وب‌سرویس عمومی و سازمانی در ایران برای تغذیه و فراخوانی ایجنت‌ها | JSON / Spec | [مخزن](https://github.com/Hameds/APIs-made-in-Iran) |

### 1.2. فروشگاه‌ها و اکوسیستم‌های تجارت الکترونیک

| عنوان ابزار / سرور | برچسب‌ها | توضیحات عملکردی | پشته فنی | مستندات |
| :--- | :---: | :--- | :---: | :---: |
| **Basalam MCP Server** | `[MCP]` `[Production]` | سرور رسمی MCP بازار اجتماعی باسلام؛ امکان مدیریت محصولات، غرفه‌ها، پیگیری سفارش‌ها و جستجو از طریق دستیار هوش مصنوعی در آدرس `mcp.basalam.com/mcp` | HTTP Transport / OAuth | [مستندات باسلام](https://developers.basalam.com/docs/mcp) |
| **Digikala Search & Specs** | `[Tools]` `[Scraper]` | ابزار واکشی هوشمند مشخصات فنی، نظرات خریداران و رصد نوسان قیمت محصولات در دیجی‌کالا برای ایجنت‌های خرید | Python / REST | [مستندات](https://gist.github.com/sh-sh-dev/542724a6ac72dc04623ecffaa4989620) |
| **Torob Price Engine Tool** | `[Tools]` `[Scraper]` | موتور مقایسه قیمت کالا میان صدها فروشگاه اینترنتی ایرانی جهت تصمیم‌گیری در پایپ‌لاین‌های خرید خودکار | Python | عمومی |

### 1.3. ابزارهای زمانی، تقویم و بازارهای مالی ایران

| عنوان ابزار / سرور | برچسب‌ها | توضیحات عملکردی | پشته فنی | مستندات |
| :--- | :---: | :--- | :---: | :---: |
| **Jalali Date & Holidays Tool** | `[Tools]` `[Free]` | موتور دقیق تبدیل تاریخ‌های شمسی/میلادی/قمری و تشخیص تعطیلات رسمی و مناسبت‌های تقویم ایران | TypeScript / Node | [سرویس](https://persian-calendar.ir/) |
| **TGJU Live Market Feed** | `[Tools]` `[Freemium]` | ابزار استخراج لحظه‌ای نرخ برابری ارزها، قیمت طلا، سکه و شاخص‌های بورس برای ایجنت‌های تحلیلگر مالی | Python / REST | [مستندات](https://marketplace.tgju.org) |
| **Nobitex Trading Agent Tool** | `[Tools]` `[Freemium]` | واسط برنامه‌نویسی بازار رمزارز نوبیتکس جهت دریافت عمق بازار و قیمت لحظه‌ای تتر/ریال | REST API | [مستندات](https://apidocs.nobitex.ir/) |

---

## 2. ☁️ پلتفرم‌های ابری و درگاه‌های API (Cloud & Gateways)

سرویس‌های ابری که دسترسی پایدار، سریع و بدون نیاز به دور زدن تحریم‌ها را به آخرین مدل‌های روز دنیا (مانند Claude 3.5، GPT-4o، DeepSeek R1) و مدل‌های بومی برای توسعه‌دهندگان ایرانی مهیا می‌کنند:

### 2.1. درگاه‌های تجمیعی و ارائه‌دهنده توکن بدون تحریم

| پلتفرم | برچسب‌ها | مدل‌های ارائه‌شده | ویژگی‌های کلیدی | وب‌سایت |
| :--- | :---: | :--- | :--- | :---: |
| **AIZamin (ای‌آی زمین)** | `[API-Gateway]` `[Freemium]` `[No-VPN]` | GPT-4o, Claude 3.5, Gemini, DeepSeek | فروش توکنی و حجمی بدون اشتراک ماهانه اجباری؛ سازگاری با OpenCode، VS Code و پایپ‌لاین‌های ایجنتیک با پرداخت تومان | [aizamin.ir](https://aizamin.ir) |
| **متیس (Metis AI)** | `[API-Gateway]` `[Enterprise]` `[Iran-Access]` | تمامی مدل‌های Frontier جهانی + مدل‌های محلی | پایدار در زمان قطعی اینترنت بین‌الملل، قابلیت ساخت بات و ورک‌فلوهای NoCode، سیستم کش توکن و حافظه RAG بومی | [metisai.ir](https://www.metisai.ir) |
| **AvalAI (اول‌آی)** | `[API-Gateway]` `[Freemium]` `[No-VPN]` | OpenAI, Anthropic, Mistral, LLaMA | درگاه پرسرعت سازگار با استاندارد SDK پایتون/JS اوپن‌ای‌آی با پرداخت ریالی و تاخیر شبکه بسیار پایین | [avalai.ir](https://avalai.ir) |
| **پارت دات آی‌آر (Part AI)** | `[Enterprise]` `[Iran-Access]` | مدل‌های بومی درنا، سهاب، پردازش تصویر و صوت | بزرگ‌ترین اکوسیستم هوش مصنوعی بومی ایران همراه با سرویس‌های احراز هویت هوشمند و بینایی ماشین بانکی | [partsoftware.com](https://partsoftware.com) |
| **هوشیو (Hooshio)** | `[API-Gateway]` `[Commercial]` | خانواده مدل‌های زبانی متن و تصویر | پایگاه دانش و ارائه‌دهنده راهکارهای شرکتی و اشتراک مدل‌های تولید تصویر و متن | [hooshio.com](https://hooshio.com) |
| **مه‌پرتو (Mehparto)** | `[Enterprise]` `[Commercial]` | خدمات زیرساختی LLM و مدل‌های سفارشی | ارائه‌دهنده راهکارهای هوش مصنوعی یکپارچه برای سازمان‌های دولتی و شرکتی | [mehparto.ir](https://mehparto.ir) |

### 2.2. زیرساخت‌های ابری پردازش هوش مصنوعی و GPU

* **[ابر آروان (ArvanCloud AI / GPU IaaS)](https://arvancloud.ir)** `[Iran-Access]` — سرورهای ابری مجهز به کارت‌های گرافیک انویدیا با اتصال مستقیم به اینترانت و شبکه تبادل داده داخل کشور.
* **[ابر دراک (Derak Cloud)](https://derak.cloud)** `[Cloud]` — سرویس‌های زیرساختی لبه و فضای ذخیره‌سازی پرسرعت مناسب برای پایگاه داده‌های برداری (Vector DBs).

---

## 3. 🧠 مدل‌های زبانی و بنیادی فارسی (LLMs & Foundation Models)

مدل‌های زبانی بازآموزی‌شده و تنظیم‌شده به‌طور تخصصی برای زبان و فرهنگ فارسی:

### 3.1. مدل‌های متن‌باز و وزن‌های زبانی

| نام مدل | برچسب‌ها | پایه معماری | حجم | ویژگی‌ها و کاربرد |
| :--- | :---: | :---: | :---: | :--- |
| **درنا (Dorna)** | `[Open-Source]` `[Weights]` | LLaMA / Mistral | 8B | بهینه‌سازی‌شده برای پاسخ‌گویی سلیس، مکالمات محاوره‌ای و متن‌های نامه‌نگاری اداری در ایران |
| **مرال (Maral-7B)** | `[Open-Source]` `[Weights]` | Mistral-7B | 7B | از معتبرترین مدل‌های پایه فارسی با درک عمیق از استعاره‌ها و ریزه‌کاری‌های زبان فارسی |
| **سینا (Sina-LLM)** | `[Open-Source]` `[Weights]` | LLaMA-3 | 8B | آموزش‌دیده روی حجم وسیعی از متون فارسی برای ارتقای توانایی استدلال، کدنویسی و ترجمه روان |
| **آوا (Ava-LLM)** | `[Open-Source]` `[Local-CPU]` | Qwen-2.5 / Gemma | 2B / 7B | بسیار سبک، طراحی‌شده جهت استقرار لوکال روی لپ‌تاپ و سرورهای بدون کارت گرافیک با Ollama |
| **مجموعه مدل‌های هزار (Hezar)** | `[Open-Source]` `[Transformers]` | BERT / RoBERTa / T5 | چندگانه | مدل‌های ویژه تسک‌های تخصصی: طبقه‌بندی احساسات، تشخیص نام اشخاص (NER) و خلاصه‌سازی متون |

### 3.2. بنچ‌مارک‌ها و چارچوب‌های ارزیابی (Eval Harnesses)

* **[persian-llm-eval](https://github.com/heyparsadev/persian-llm-eval)** `[Open-Source]` `[Benchmark]` — بنچ‌مارک استاندارد مدل‌های زبانی در زبان فارسی شامل ۳۰۰ تست در ۱۰ حوزه مختلف و جدول لیدربورد رتبه‌بندی مدل‌ها.
* **[Persian-LLM-Security-Evaluation](https://github.com/Haniyesabeghi/Persian-LLM-Security-Evaluation-BA)** `[Research]` — فریم‌ورک تحلیل آسیب‌پذیری و ارزیابی نفوذ از طریق Prompt Injection روی مدل‌های بومی درنا و مرال.

---

## 4. 🎙️ پردازش گفتار، صوت و دوبله (Speech: STT & TTS)

### 4.1. تبدیل گفتار به متن (Speech-to-Text)

* **[OpenAI Whisper (Persian Fine-tuned)](https://github.com/devie-dev/persian-stt-models)** `[Open-Source]` — پیاده‌سازی‌های فاین‌تیون‌شده مدل Whisper برای شناسایی کلمات عامیانه، لهجه‌ها و اصطلاحات تخصصی فارسی.
* **[فارس‌آوا (FarsAva / Amerandish)](https://amerandish.com)** `[Commercial]` `[API]` — از باسابقه‌ترین سرویس‌های تجاری تایپ صوتی و تبدیل گفتار به متن با دقت بسیار بالا در محیط‌های پرسروصدا.
* **[IoType (آی‌او تایپ)](https://www.iotype.com/api)** `[Freemium]` `[API]` — وب‌سرویس و API تایپ صوتی و تبدیل فایل‌های صوتی ضبط‌شده به متن ویرایش‌شده.

### 4.2. تبدیل متن به گفتار و شبیه‌سازی صدا (Text-to-Speech)

* **[persian_tts (nimaone)](https://github.com/nimaone/persian_tts)** `[Open-Source]` `[Offline]` — موتور سنتز صدای فارسی با قابلیت شبیه‌سازی و کلونینگ صدا (Voice Cloning) بدون نیاز به اینترنت بر روی پردازنده معمولی (CPU).
* **[dcho Voice Engine](https://github.com/AliAkrami1375/dcho)** `[Open-Source]` `[Edge]` — پایپ‌لاین تولید گفتار طبیعی و فوق‌سریع برای گجت‌های الکترونیکی و سیستم‌های امبدد.
* **[Gooya Bozorg (گویا بزرگ)](https://github.com/Reza2kn/gooya-bozorg-native)** `[Open-Source]` `[Desktop]` — نرم‌افزار دسکتاپ بومی کراس‌پلتفرم برای خواندن کتاب‌های صوتی و متن‌های طولانی به فارسی روان.

---

## 5. 👁️ بینایی ماشین و سندکاوی (Vision, OCR & Document AI)

* **[Persian OCR Master](https://github.com/JENOVASir/persianAi-OCR-MASTER)** `[Open-Source]` — وب‌اپلیکیشن استخراج متن از تصاویر اسناد، کتاب‌ها و دست‌خط‌های فارسی با امکان استخراج فرمول‌های ریاضی.
* **[Hezar Vision (هزار)](https://github.com/hezarai/hezar)** `[Open-Source]` — مدل‌های پیش‌آموزش‌دیده برای خواندن پلاک خودرو، اسکن متون فارسی و اسناد هویتی (کارت ملی و شناسنامه).
* **[ایران OCR](https://www.iranocr.ir)** `[Commercial]` `[API]` — وب‌سرویس قدیمی و تخصصی تبدیل پی‌دی‌اف‌های تصویری و عکس‌های اداری به فایل متنی قابل جستجو.

---

## 6. 📚 ابزارهای بازیابی اطلاعات و RAG بومی (Persian RAG & Embeddings)

### 6.1. مدل‌های برداری (Embedding Models)

* **[BGE-M3 Multilingual](https://github.com/FlagOpen/FlagEmbedding)** `[Open-Source]` — یکی از دقیق‌ترین مدل‌های چندزبانه با فهم عمیق معنایی جملات پیچیده فارسی در هر دو روش متراکم (Dense) و کلمه‌کلیدی (Sparse).
* **[Persian Sentence Transformers](https://huggingface.co/models?search=persian-embedding)** `[Open-Source]` — مدل‌های بهینه‌سازی‌شده برای خوشه‌بندی متون و جستجوی معنایی متون وب فارسی.

### 6.2. موتورها و پایپ‌لاین‌های آماده RAG سازمانی

* **[PersianRAG (TahaBakhtari)](https://github.com/TahaBakhtari/PersianRAG)** `[Open-Source]` — پایپ‌لاین آماده پرسش و پاسخ بر روی مستندات اداری و کتاب‌های فارسی با رابط کاربری کاربرپسند.
* **[Bank Chatbot Legal RAG](https://github.com/Muhammad-davoudi/bank-chatbot)** `[Open-Source]` — پیاده‌سازی کاربردی سیستم پاسخگویی به مقررات بانکی و بخشنامه‌های دولتی با کنترل توهم مدل (Anti-hallucination).
* **[Persian Legal RAG Agent](https://github.com/Hamidreza-Talei/persian-legal-rag-agent)** `[Open-Source]` — سیستم ایجنتیک پاسخگویی به سوالات حقوقی با ترکیب LangGraph، دیتابیس LanceDB و ارزیابی RAGAS.

---

## 7. 🛠️ کتابخانه‌ها و ابزارهای مهندسی زبان (Persian NLP Toolkits)

| ابزار | برچسب‌ها | زبان | ویژگی و ماموریت |
| :--- | :---: | :---: | :--- |
| **[Hezar (هزار)](https://github.com/hezarai/hezar)** | `[Open-Source]` | Python | فریم‌ورک استاندارد و فراگیر هوش مصنوعی فارسی با ساپورت ترانسفورمرها و تسک‌های چندوجهی |
| **[Persian-Tools](https://github.com/persian-tools/persian-tools)** | `[Open-Source]` | TS / JS | جعبه‌ابزار فوق‌العاده کاربردی برای اعتبارسنجی کدملی، کارت بانکی، تبدیل عدد به حروف و فرمت تاریخ |
| **[Hazm (هضم)](https://github.com/roshan-research/hazm)** | `[Open-Source]` | Python | باسابقه‌ترین ابزار توکنایزیشن، ریشه‌یابی و پاک‌سازی متن برای ساخت پایپ‌لاین‌های یادگیری ماشین |
| **[Parsivar](https://github.com/ICTRC/Parsivar)** | `[Open-Source]` | Python | مجموعه تخصصی پیش‌پردازش متن با تاکید بر دستور خط فرهنگستان زبان و ادب فارسی |
| **[Persian AI Glossary](https://github.com/snrazavi/Persian-AI-and-Machine-Learning-Glossary)** | `[Docs]` | MD | واژه‌نامه تخصصی معادل‌های فارسی برای اصطلاحات هوش مصنوعی و یادگیری ژرف |

---

## 8. 🖥️ افزونه‌ها، ابزارهای مرورگر و رابط‌های کاربری (Extensions & RTL)

* **[Persian AI RTL Assistant](https://github.com/tig-ndi/persian-ai-rtl-assistant)** `[Browser-Extension]` — اصلاح جهت نمایش (RTL) و فونت فارسی در صفحات ChatGPT، Claude، DeepSeek و Mistral.
* **[Reply RTL Viewer](https://github.com/shahriyar3/reply-rtl-viewer)** `[Open-Source]` — نمایشگر مدرن و تک‌فایلی متون مارک‌داون هوش مصنوعی با حل مشکل تداخل کدهای انگلیسی و متون فارسی.

---

## 9. 📊 دیتاست‌ها و منابع ارزیابی داده (Datasets & Corpora)

* **[Awesome-Persian-LLM](https://github.com/MohammadHeydari/Awesome-Persian-LLM)** `[Curated-List]` — فهرست مقالات دانشگاهی، سورس‌کدها و منابع مرتبط با مدل‌های زبانی فارسی.
* **[GPTInformal Speech Dataset](https://github.com/MahtaFetrat/GPTInformal-Persian-Speech-Dataset)** `[Dataset]` — بیش از ۶ ساعت دیتای صوتی مکالمات غیررسمی با متن منطبق مناسب ترینینگ مدل‌های صوتی.
* **[MirasText & Hamshahri Corpus](https://github.com/mhbashari/awesome-persian-nlp-ir)** `[Corpus]` — پیکره‌های چند ده‌میلیونی از متون استاندارد، خبری و دانشنامه‌ای فارسی.

---

## 👥 سازندگان و حامیان (Maintainers & Backers)

این پروژه توسط سازمان **[Kalahamoon (کلاهمون)](https://github.com/Kalahamoon)** و با همراهی جامعه توسعه‌دهندگان و متخصصان هوش مصنوعی ایران نگهداری و گسترش می‌یابد.

---

## 📜 مجوز (License)

این پروژه تحت مجوز متن‌باز **MIT** منتشر شده است. برای اطلاعات بیشتر فایل [LICENSE](LICENSE) را مشاهده نمایید.
