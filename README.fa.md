# نسخه فارسی Awesome Persian AI Hub

<div dir="rtl" align="right">

<div align="center">

![Awesome Persian AI Banner](assets/banner.svg)

<br/>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Organization](https://img.shields.io/badge/Org-Kalahamoon-6366f1.svg?style=flat-square)](https://github.com/Kalahamoon)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-10b981.svg?style=flat-square)](CONTRIBUTING.md)
[![Persian Typography](https://img.shields.io/badge/ZWNJ-Standard_Persian-0ea5e9.svg?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-f59e0b.svg?style=flat-square)](LICENSE)

<br/>

**مرکز جامع، مهندسی‌شده و یکپارچه ابزارها، پروتکل MCP، مدل‌های زبانی، سرویس‌های ابری و زیرساخت‌های هوش مصنوعی برای زبان فارسی و ایران.**

[نسخه انگلیسی (English Version)](README.md) • [راهنمای مشارکت](CONTRIBUTING.md) • [گزارش خطا یا ثبت ابزار](https://github.com/Kalahamoon/awesome-persian-ai/issues)

</div>

---

### 🇮🇷 درود و سپاس از پیشگامان هوش مصنوعی فارسی

> **پیام تقدیر و افتخار:**  
> صمیمانه‌ترین درودها و تبریکات نثار تمامی دانشمندان، مهندسان نرم‌افزار، پژوهشگران هوش مصنوعی، فعالان جامعه متن‌باز و کارآفرینان ایرانی در سراسر کره زمین — از مراکز تحقیقاتی پیشرو در اروپا و آمریکای شمالی تا استارتاپ‌ها، شرکت‌های دانش‌بنیان و توسعه‌دهندگان مستقل در جای‌جای ایران عزیز — که با وجود پیچیده‌ترین شرایط تحریمی، موانع زیرساختی و نابرابری‌های دسترسی، هرگز متوقف نشدند و با پشتکار، ایثار علمی و خلاقیت ناب خود، جایگاه زبان، فرهنگ و هوش مصنوعی فارسی را در صدر تحولات جهانی پاس داشتند. این هاب تقدیم به تک‌تک شما همراهان سرافراز است. 🦁✨

---

## 🧭 فهرست دسته‌بندی‌ها

| شماره | عنوان بخش | خلاصه محتوا |
| :---: | :--- | :--- |
| **۰۱** | [🔌 سرورها و ابزارهای پروتکل MCP](#۱-سرورها-و-ابزارهای-پروتکل-mcp) | سرورهای MCP برای پلتفرم‌های ایرانی، پیام‌رسان‌ها و اتوماسیون‌های سازمانی |
| **۰۲** | [☁️ پلتفرم‌های ابری و درگاه‌های API](#۲-پلتفرمهای-ابری-و-درگاههای-api) | درگاه‌های بدون تحریم، فروش توکنی و سرورهای GPU |
| **۰۳** | [🧠 مدل‌های زبانی و بنیادی فارسی](#۳-مدلهای-زبانی-و-بنیادی-فارسی) | مدل‌های متن‌باز پایه، وزن‌های زبانی و لیدربوردهای رسمی |
| **۰۴** | [🤖 سیستم‌ها و فریم‌ورک‌های چندایجنتیک](#۴-سیستمها-و-فریمورکهای-چندایجنتیک) | عامل‌های خودمختار، تبدیل متن به SQL و منشی‌های صوتی تلفنی |
| **۰۵** | [🛡️ امنیت مدل‌های زبانی، گاردریل و ایمنی پرامپت](#۵-امنیت-مدلهای-زبانی-گاردریل-و-ایمنی-پرامپت) | دیواره‌های آتش زبانی، آزمون نفوذ پرامپت و جلوگیری از جیل‌بریک |
| **۰۶** | [⚖️🩺 هوش مصنوعی در حوزه‌های تخصصی](#۶-هوش-مصنوعی-در-حوزههای-تخصصی-حقوقی-و-سلامت) | سیستم‌عامل دفاتر وکالت، مدل‌های بالینی پزشکی و شبیه‌سازها |
| **۰۷** | [🎙️ پردازش گفتار، صوت و دوبله](#۷-پردازش-گفتار-صوت-و-دوبله) | بازشناسی گفتار فارسی (STT)، سنتز گفتار و شبیه‌سازی صدا (TTS) |
| **۰۸** | [👁️ بینایی ماشین و مدل‌های چندوجهی](#۸-بینایی-ماشین-و-مدلهای-چندوجهی) | مدل‌های چندوجهی فارسی (CLIP)، موتورهای OCR و تبدیل به LaTeX |
| **۰۹** | [📚 ابزارهای بازیابی اطلاعات و RAG بومی](#۹-ابزارهای-بازیابی-اطلاعات-و-rag-بومی) | مدل‌های برداری امبدینگ و پایپ‌لاین‌های سازمانی پرسش‌وپاسخ اسناد |
| **۱۰** | [🛠️ کتابخانه‌ها و ابزارهای مهندسی زبان](#۱۰-کتابخانهها-و-ابزارهای-مهندسی-زبان) | نرمال‌سازها، واژه‌نماها، جعبه‌ابزارهای توکنایزیشن و رسم‌الخط |
| **۱۱** | [🌐 ترجمه ماشینی و ترنسفر زبان](#۱۱-ترجمه-ماشینی-و-ترنسفر-زبان) | مدل‌های ترجمه عصبی دوطرفه و مترجم‌های فرمت کتاب الکترونیکی |
| **۱۲** | [🖥️ افزونه‌ها، ابزارهای مرورگر و محیط‌های توسعه](#۱۲-افزونهها-ابزارهای-مرورگر-و-محیطهای-توسعه) | افزونه‌های تصحیح راست‌چین VS Code، ترمینال‌های BiDi و چیدمان متن |
| **۱۳** | [📊 دیتاست‌ها و منابع ارزیابی داده](#۱۳-دیتاستها-و-منابع-ارزیابی-داده) | پیکره‌های ۸۰ گیگابایتی آموزش اولیه، دیتاست‌های دستوری و صوتی |

---

## 🏷️ راهنمای برچسب‌ها و وضعیت‌ها

| نشان بصری | عنوان و دسته‌بندی فنی |
| :--- | :--- |
| ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) | **پروتکل اتصال مدل:** ارائه ابزارها و منابع استاندارد برای ایجنت‌های هوش مصنوعی |
| ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | **متن‌باز:** سورس‌کد یا وزن‌های مدل به‌صورت عمومی در گیت‌هاب یا هاگینگ‌فیس در دسترس است |
| ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) | **درگاه API:** سرویس تجمیعی ارائه توکن با پرداخت ریالی/تومانی |
| ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) | **عامل هوشمند:** سیستم دارای حلقه تصمیم‌گیری و اجرای وظایف چندمرحله‌ای |
| ![Leaderboard](https://img.shields.io/badge/Leaderboard-pink?style=flat-square) | **لیدربورد و ارزیابی:** جداول رتبه‌بندی رقابتی و بنچ‌مارک‌های معتبر |
| ![Security](https://img.shields.io/badge/Security-red?style=flat-square) | **امنیت و گاردریل:** ابزارهای آزمون نفوذ، ایمنی پرامپت و دیواره‌های آتش زبانی |
| ![LegalTech](https://img.shields.io/badge/LegalTech-violet?style=flat-square) ![Healthcare](https://img.shields.io/badge/Healthcare-teal?style=flat-square) | **حوزه تخصصی:** مدل‌ها و سامانه‌های اختصاصی حقوقی، قضایی یا سلامت و پزشکی |
| ![No-VPN](https://img.shields.io/badge/No--VPN-sky?style=flat-square) | **بدون تحریم‌شکن:** دسترسی مستقیم بدون نیاز به VPN از داخل ایران |
| ![Iran-Access](https://img.shields.io/badge/Iran--Access-green?style=flat-square) | **اینترانت ملی:** پایداری تضمین‌شده در شرایط محدودیت اینترنت بین‌الملل |
| ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) | **مدل هزینه:** بسته‌های اعتباری/مصرفی یا قراردادهای سازمانی |

---

## ۱. سرورها و ابزارهای پروتکل MCP

### ۱.۱. پلتفرم‌های تجارت الکترونیک و آگهی ایران
* **[Basalam MCP Server](https://developers.basalam.com/docs/mcp)** ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Production](https://img.shields.io/badge/Production-blue?style=flat-square) — سرور رسمی MCP بازار اجتماعی باسلام در آدرس `mcp.basalam.com/mcp` جهت جستجوی محصولات و مدیریت سفارش‌ها.
* **[Digikala MCP Server](https://github.com/mmdju/digikala-mcp)** ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) — سرور MCP مستقل دیجی‌کالا با ۱۶ ابزار اختصاصی جستجو، مقایسه قیمت و استخراج مشخصات فنی.
* **[Divar MCP Server](https://github.com/mmdju/divar-mcp)** ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) — سرور MCP جستجو و تحلیل آگهی‌های پلتفرم دیوار (املاک، خودرو، کالا).
* **[Torob MCP Server](https://github.com/mmdju/torob-mcp)** ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) — سرور MCP موتور مقایسه قیمت ترب شامل ۱۴ ابزار برای پایش تخفیف‌ها و نوسان قیمت.

### ۱.۲. سامانه‌های اتوماسیون، پیام‌رسان‌ها و زیرساخت
* **Kasra MCP Server** ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Internal](https://img.shields.io/badge/Internal-slate?style=flat-square) — اتصال هوش مصنوعی به اتوماسیون تردد و پرسنلی کسرا برای ثبت مرخصی، مأموریت و مشاهده کارکرد.
* **Bale Messenger MCP** ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) — اتصال ایجنت‌های هوش مصنوعی به پیام‌رسان بله برای خواندن تاریخچه و ارسال پیام تاییدمحور.
* **[Liara Cloud MCP Server](https://github.com/SalehB1/Lira-mcp)** ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) — سرور MCP بر روی مستندات و زیرساخت ابری لیارا جهت دیباگ لاگ‌های بیلد و کانفیگ استقرار.
* **[Aira MCP Server](https://github.com/AiraChat/aira-mcp)** ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) — سرور MCP و رجیستری کانکتورهای شناختی هوش مصنوعی فارسی.
* **[Hermes Agent Iran Gateway](https://github.com/hnkwing/hermes-agent-iran-gateway)** ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) — گیت‌وی متن‌باز اتصال ایجنت هرمس به پیام‌رسان‌های بومی بله و روبیکا.
* **[Smart Home KNX MCP](https://github.com/SMousavi7/smart-home-knx-thingsboard)** ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![IoT](https://img.shields.io/badge/IoT-blue?style=flat-square) — کنترل سیستم خانه هوشمند با فرمان‌های زبان طبیعی فارسی از طریق ترکیب KNX و اولاما.
* **[APIs-made-in-Iran Catalog](https://github.com/Hameds/APIs-made-in-Iran)** ![Tools](https://img.shields.io/badge/Tools-slate?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) — کاتالوگ جامع صدها وب‌سرویس عمومی و سازمانی در ایران.

### ۱.۳. ابزارهای زمانی، تقویم و بازارهای مالی ایران
* **[Jalali Date Engine](https://persian-calendar.ir/)** ![Free](https://img.shields.io/badge/Free-emerald?style=flat-square) — موتور دقیق تبدیل تقویم‌های شمسی، میلادی و قمری و استخراج تعطیلات رسمی ایران.
* **[TGJU Live Market Feed](https://marketplace.tgju.org)** ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) — وب‌سرویس استخراج لحظه‌ای نرخ ارز، طلا، سکه و بورس برای ایجنت‌های مالی.
* **[Nobitex Trading Agent Tool](https://apidocs.nobitex.ir/)** ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) — واسط برنامه‌نویسی بازار رمزارز نوبیتکس برای تحلیل عمق بازار و قیمت تتر.

---

## ۲. پلتفرم‌های ابری و درگاه‌های API

### ۲.۱. درگاه‌های تجمیعی و ارائه‌دهنده توکن بدون تحریم
* **[AIZamin (ای‌آی زمین)](https://aizamin.ir)** ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![No-VPN](https://img.shields.io/badge/No--VPN-sky?style=flat-square) ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) — فروش توکنی و حجمی بدون اشتراک ماهانه؛ سازگاری با OpenCode و VS Code با پرداخت تومان.
* **[متیس (Metis AI)](https://www.metisai.ir)** ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![Iran-Access](https://img.shields.io/badge/Iran--Access-green?style=flat-square) ![Enterprise](https://img.shields.io/badge/Enterprise-slate?style=flat-square) — پایدار در زمان قطعی اینترنت بین‌الملل، سیستم No-Code و کش توکن و حافظه RAG بومی.
* **[AvalAI (اول‌آی)](https://avalai.ir)** ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![No-VPN](https://img.shields.io/badge/No--VPN-sky?style=flat-square) ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) — درگاه پرسرعت سازگار با SDK پایتون/JS اوپن‌ای‌آی با پرداخت ریالی.
* **[پارت دات آی‌آر (Part AI)](https://partsoftware.com)** ![Enterprise](https://img.shields.io/badge/Enterprise-slate?style=flat-square) ![Iran-Access](https://img.shields.io/badge/Iran--Access-green?style=flat-square) — بزرگ‌ترین اکوسیستم هوش مصنوعی بومی ایران (درنا، سهاب، پردازش تصویر و صوت بانکی).
* **[هوشیو (Hooshio)](https://hooshio.com)** ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) — پایگاه دانش و ارائه‌دهنده راهکارهای شرکتی و اشتراک مدل‌های هوش مصنوعی.
* **[مه‌پرتو (Mehparto)](https://mehparto.ir)** ![Enterprise](https://img.shields.io/badge/Enterprise-slate?style=flat-square) ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) — خدمات زیرساختی LLM و مدل‌های سفارشی برای سازمان‌ها.

### ۲.۲. زیرساخت‌های ابری پردازش هوش مصنوعی و GPU
* **[ابر آروان (ArvanCloud AI / GPU IaaS)](https://arvancloud.ir)** ![Iran-Access](https://img.shields.io/badge/Iran--Access-green?style=flat-square) — سرورهای ابری مجهز به پردازنده‌های گرافیکی NVIDIA در شبکه ملی.
* **[ابر دراک (Derak Cloud)](https://derak.cloud)** ![Cloud](https://img.shields.io/badge/Cloud-blue?style=flat-square) — خدمات ابری لبه و ذخیره‌سازی داده‌های برداری (Vector DBs).

---

## ۳. مدل‌های زبانی و بنیادی فارسی

### ۳.۱. مدل‌های متن‌باز و وزن‌های زبانی
* **درنا ۲ (Dorna 2)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) — نسل دوم مدل زبانی درنا بر پایه LLaMA-3.1 با حجم 8B و پشتیبانی از GGUF.
* **مرال (Maral-7B)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) — مدل پایه محبوب فارسی بر پایه Mistral-7B با درک بالا از متون فارسی.
* **PersianMind (دانشگاه تهران)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) — مدل زبانی دانشگاه تهران برای استدلال علمی و ادبی فارسی.
* **سینا (Sina-LLM)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) — مدل فاین‌تیون‌شده روی پیکره‌های بزرگ فارسی مبتنی بر LLaMA-3.
* **AVA-Llama-3 & Mistral** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) — سری مدل‌های زبانی آوا با کیفیت روان در مکالمه.
* **ParsBERT** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Transformers](https://img.shields.io/badge/Transformers-yellow?style=flat-square) — مدل بنیادین ترانسفورمر زبان فارسی با بیش از ۱۶۰ هزار دانلود در هاگینگ‌فیس.
* **ParsGPT** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) — مدل تولید متن و مکالمه بر پایه معماری GPT-2 در هوشواره.
* **Gemma-3-Persian** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) — فاین‌تیون دقیق بر روی نسل جدید مدل‌های سبک جما گوگل.
* **آوا (Ava-LLM)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Local-CPU](https://img.shields.io/badge/Local--CPU-cyan?style=flat-square) — مدل سبک برای اجرای محلی روی پردازنده معمولی لپ‌تاپ با Ollama.
* **مدل‌های هزار (Hezar)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Transformers](https://img.shields.io/badge/Transformers-yellow?style=flat-square) — مدل‌های چندمنظوره برای تحلیل احساسات، NER و خلاصه‌سازی.

### ۳.۲. لیدربوردها و بنچ‌مارک‌های ارزیابی
* **[Open Persian LLM Leaderboard (PartAI)](https://huggingface.co/spaces/PartAI/open-persian-llm-leaderboard)** ![Leaderboard](https://img.shields.io/badge/Leaderboard-pink?style=flat-square) — لیدربورد رسمی و جامع ارزیابی رقابتی مدل‌های زبانی فارسی در هاگینگ‌فیس.
* **[persian-llm-eval](https://github.com/heyparsadev/persian-llm-eval)** ![Benchmark](https://img.shields.io/badge/Benchmark-emerald?style=flat-square) — بنچ‌مارک استاندارد مدل‌های فارسی با ۳۰۰ تست در ۱۰ شاخه تخصصی.
* **[PersianMMLU Benchmark](https://huggingface.co/spaces/raia-center/PersianMMLU)** ![Benchmark](https://img.shields.io/badge/Benchmark-emerald?style=flat-square) — بنچ‌مارک درک دانش دانشگاهی در ۵۷ رشته تخصصی به زبان فارسی.
* **[ParsiEval](https://github.com/mshojaei77/ParsiEval)** ![Benchmark](https://img.shields.io/badge/Benchmark-emerald?style=flat-square) — ارزیابی استدلال، ریاضیات و درک متن در مدل‌های بزرگ زبانی فارسی.
* **[ParsBench](https://github.com/ParsBench/ParsBench)** ![Toolkit](https://img.shields.io/badge/Toolkit-slate?style=flat-square) — مجموعه ابزار و دیتاست برای ارزیابی تسک‌های زبان فارسی.
* **[TAAROFBENCH](https://github.com/niktaas/TAAROFBENCH)** ![Research](https://img.shields.io/badge/EMNLP_2025-blue?style=flat-square) — اولین بنچ‌مارک سنجش درک مدل‌ها از تعارف، کنایه و فرهنگ گفتاری ایرانی.

---

## ۴. سیستم‌ها و فریم‌ورک‌های چندایجنتیک
* **[LangGraph Multi-Agent Persian](https://github.com/SaharZarbafi/langgraph-multi-agent-persian)** ![Agent](https://img.shields.io/badge/Multi--Agent-amber?style=flat-square) — سیستم چندعامله پروداکشن با معماری Actor-Critic و مسیریابی هوشمند میان مدل‌ها.
* **[Local SQL Agent (Persian)](https://github.com/alisadeghiaghili/local-sql-agent)** ![Agent](https://img.shields.io/badge/Text--to--SQL-amber?style=flat-square) — تبدیل امن زبان طبیعی فارسی به دستورات SQL با اعتبارسنجی نحوی AST.
* **[Doctor Agent](https://github.com/SirBNL/doctor-agent)** ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) — ایجنت نوبت‌دهی پزشکی با ابزارخوانی (Tool Calling) لوکال با اولاما.
* **[Phone Agent (منشی تلفنی هوشمند)](https://github.com/sepehr071/phone-agent)** ![Agent](https://img.shields.io/badge/Voice--Agent-amber?style=flat-square) — پاسخ‌گویی صوتی خودکار تلفنی بر بستر استریسک (Asterisk) به فارسی روان.
* **[Micky Voice Assistant](https://github.com/xmannii/micky)** ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) — دستیار صوتی ایجنتیک اولویت‌دار برای زبان فارسی.
* **[Moujez Summarizer Agent](https://github.com/kharazi/moujez)** ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) — ایجنت تلخیص و عصاره‌کشی ساختاریافته از متون طولانی.

---

## ۵. امنیت مدل‌های زبانی، گاردریل و ایمنی پرامپت
* **[MCI LLM Security Hackathon Archive](https://github.com/erfnzdeh/MCI-LLM-Security-Hackathon)** ![Security](https://img.shields.io/badge/Security-red?style=flat-square) — سناریوهای آزمون نفوذ و جیل‌بریک مدل‌های زبانی فارسی از طریق حملات چندزبانه و چارچوب‌بندی.
* **[Persian LLM Security Evaluation](https://github.com/Haniyesabeghi/Persian-LLM-Security-Evaluation-BA)** ![Security](https://img.shields.io/badge/Security-red?style=flat-square) — ارزیابی آسیب‌پذیری و دفاع روی مدل‌های درنا و مرال با اولاما.
* **[Morphological Type Guards (MTG)](https://github.com/Moshe-ship/mtg)** ![Security](https://img.shields.io/badge/Security-red?style=flat-square) — دفاع در برابر حملات فریب کاراکتری و دستکاری جهت‌گیری متن (BiDi Hijacking).
* **[PAIB Benchmark](https://github.com/Romohub/paib)** ![Security](https://img.shields.io/badge/Security-red?style=flat-square) — بنچ‌مارک ارزیابی یکپارچگی ایجنت‌های فارسی در برابر دستکاری دستورات.

---

## ۶. هوش مصنوعی در حوزه‌های تخصصی: حقوقی و سلامت

### ۶.۱. حقوق، قضا و قراردادها
* **[Persian Legal Practice OS](https://github.com/ansariaiadmin/legal-platform)** ![LegalTech](https://img.shields.io/badge/LegalTech-violet?style=flat-square) — سیستم‌عامل سلف‌هاستد دفاتر وکالت با ۶ ایجنت هوشمند و RAG سه‌گانه.
* **[Persian Legal RAG Agent](https://github.com/Hamidreza-Talei/persian-legal-rag-agent)** ![LegalTech](https://img.shields.io/badge/LegalTech-violet?style=flat-square) — پاسخگویی به سوالات حقوقی مدنی و کیفری ایران با بازرتبه‌بندی معنایی.
* **[Smart Legal Letterhead](https://github.com/ahmadsalamifar/smart-legal-letterhead)** ![LegalTech](https://img.shields.io/badge/LegalTech-violet?style=flat-square) — تولیدکننده هوشمند لوایح و سربرگ‌های حقوقی فارسی.

### ۶.۲. پزشکی، داروسازی و سلامت
* **[PerMed (Persian Meditron)](https://github.com/neda-kheirkhah/PerMed)** ![Healthcare](https://img.shields.io/badge/Healthcare-teal?style=flat-square) — مدل زبانی تخصصی پزشکی و دارویی فارسی مبتنی بر Meditron.
* **[Persian Medical RAG Chatbot](https://github.com/yousef-mousavizade/Persian-Medical-RAG-Chatbot)** ![Healthcare](https://img.shields.io/badge/Healthcare-teal?style=flat-square) — چت‌بات دارویی و بالینی متصل به دیتابیس‌های پزشکی ایران.
* **[OSCE AI Tutor](https://github.com/NafisSam/osce-tutor)** ![Healthcare](https://img.shields.io/badge/Healthcare-teal?style=flat-square) — شبیه‌ساز آزمون‌های بالینی OSCE برای دانشجویان پزشکی ایران.

---

## ۷. پردازش گفتار، صوت و دوبله

### ۷.۱. تبدیل گفتار به متن (Speech-to-Text)
* **[wav2vec2-large-xlsr-53-persian](https://huggingface.co/jonatasgrosman/wav2vec2-large-xlsr-53-persian)** ![STT](https://img.shields.io/badge/STT-blue?style=flat-square) — پردانلودترین مدل تشخیص گفتار فارسی با نزدیک به ۱ میلیون دانلود.
* **[Wav2Vec2 Persian v3 (m3hrdadfi)](https://huggingface.co/m3hrdadfi/wav2vec2-large-xlsr-persian-v3)** ![STT](https://img.shields.io/badge/STT-blue?style=flat-square) — مدل بهینه‌شده بازشناسی گفتار فارسی با نرخ خطای واژگانی بسیار پایین.
* **[Whisper-Persian-v4 (nezamisafa)](https://huggingface.co/nezamisafa/whisper-persian-v4)** ![Whisper](https://img.shields.io/badge/Whisper-purple?style=flat-square) — مدل بهینه‌شده ویسپر لارج ۳ برای زبان فارسی.
* **[Persian ASR Leaderboard](https://huggingface.co/spaces/navidved/open_persian_asr_leaderboard)** ![Leaderboard](https://img.shields.io/badge/Leaderboard-pink?style=flat-square) — لیدربورد مقایسه‌ای عملکرد مدل‌های بازشناسی گفتار فارسی.
* **[PersianScribe for Apple Silicon](https://github.com/duuuude/PersianScribe-for-Apple-Silicon)** ![Offline](https://img.shields.io/badge/Offline-emerald?style=flat-square) — تبدیل آفلاین گفتار به متن با تفکیک گوینده روی پردازنده‌های سری M اپل.
* **[Nemotron ASR Streaming Farsi](https://huggingface.co/mehdi-hf/nemotron-asr-streaming-farsi)** ![Streaming](https://img.shields.io/badge/Streaming-cyan?style=flat-square) — تشخیص گفتار استریمینگ بلادرنگ مبتنی بر معماری نیموترون انویدیا.
* **[فارس‌آوا (FarsAva / Amerandish)](https://amerandish.com)** ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) — سرویس تجاری باسابقه تبدیل گفتار به متن در محیط‌های شلوغ.
* **[IoType (آی‌او تایپ)](https://www.iotype.com/api)** ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) — وب‌سرویس تایپ صوتی و تبدیل صوت به متن.

### ۷.۲. تبدیل متن به گفتار و شبیه‌سازی صدا (Text-to-Speech)
* **[Chatterbox-TTS-Persian-Farsi](https://huggingface.co/Thomcles/Chatterbox-TTS-Persian-Farsi)** ![TTS](https://img.shields.io/badge/TTS-purple?style=flat-square) — محبوب‌ترین و طبیعی‌ترین مدل تبدیل متن به صوت فارسی.
* **[Pocket TTS Farsi (ONNX)](https://huggingface.co/Nimaone/pocket-tts-farsi-v2-onnx)** ![Lightweight](https://img.shields.io/badge/Lightweight-teal?style=flat-square) — سنتز گفتار سبک با فرمت ONNX برای دیوایس‌های کم‌مصرف.
* **[persian_tts (nimaone)](https://github.com/nimaone/persian_tts)** ![Offline](https://img.shields.io/badge/Offline-emerald?style=flat-square) — سنتز صدای فارسی با قابلیت شبیه‌سازی صدا (Voice Cloning) کاملاً آفلاین روی CPU.
* **[Mana Persian Piper](https://huggingface.co/MahtaFetrat/Mana-Persian-Piper)** ![Piper](https://img.shields.io/badge/Piper-orange?style=flat-square) — مدل بهینه‌سازی‌شده برای موتور صوت پایپر با تلفظ دقیق.
* **[dcho Voice Engine](https://github.com/AliAkrami1375/dcho)** ![Edge](https://img.shields.io/badge/Edge-blue?style=flat-square) — موتور صوتی سبک متن‌باز برای گجت‌ها و سیستم‌های امبدد.
* **[Gooya Bozorg (گویا بزرگ)](https://github.com/Reza2kn/gooya-bozorg-native)** ![Desktop](https://img.shields.io/badge/Desktop-slate?style=flat-square) — برنامه دسکتاپ کراس‌پلتفرم برای خوانش متن‌های طولانی به فارسی روان.

---

## ۸. بینایی ماشین و مدل‌های چندوجهی
* **[CLIPfa (سجاد ایوبی)](https://github.com/sajjjadayobi/CLIPfa)** ![Multimodal](https://img.shields.io/badge/Multimodal-pink?style=flat-square) — مدل اتصال متن و تصویر در زبان فارسی برای جستجوی متنی تصویر.
* **[Qwen2-VL-Persian-Arabic-OCR](https://huggingface.co/mohajesmaeili/Qwen3-VL-2B-Persian-Arabic-Ocr-v1.0)** ![Vision-LLM](https://img.shields.io/badge/Vision--LLM-purple?style=flat-square) — مدل بینایی زبان جهت خواندن اسناد خطی، چاپی و فرمول‌های ریاضی.
* **[Persian OCR Master](https://github.com/JENOVASir/persianAi-OCR-MASTER)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) — وب‌اپلیکیشن استخراج متن از تصاویر کتاب‌ها و دست‌خط‌های فارسی.
* **[PDF-OCR-Math2LaTeX](https://github.com/Sadeghizad/pdf-ocr-fas-eng-math2latex)** ![LaTeX](https://img.shields.io/badge/LaTeX-blue?style=flat-square) — استخراج متون دوزبانه از اسناد و تبدیل معادلات ریاضی به کدهای LaTeX.
* **[Hezar Vision (هزار)](https://github.com/hezarai/hezar)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) — مدل‌های پلاک‌خوانی و اسکن مدارک هویتی فارسی.
* **[ایران OCR](https://www.iranocr.ir)** ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) — وب‌سرویس تخصصی تبدیل اسناد تصویری به متن قابل جستجو.

---

## ۹. ابزارهای بازیابی اطلاعات و RAG بومی
* **[Persian Embeddings (heydariAI)](https://huggingface.co/heydariAI/persian-embeddings)** ![Top-Embedding](https://img.shields.io/badge/Top--Embedding-emerald?style=flat-square) — مدل برداری رتبه یک هاگینگ‌فیس برای بازیابی معنایی متون فارسی.
* **[BGE-M3 Multilingual](https://github.com/FlagOpen/FlagEmbedding)** ![Multilingual](https://img.shields.io/badge/Multilingual-blue?style=flat-square) — مدل چندزبانه با درک عمیق از جملات فارسی در دو روش متراکم (Dense) و پراکنده (Sparse).
* **[ParsBERT NLI](https://huggingface.co/parsi-ai-nlpclass/ParsBERT-nli-FarsTail-FarSick)** ![NLI](https://img.shields.io/badge/NLI-violet?style=flat-square) — مدل استنتاج معنایی و ارزیابی تطابق اسناد فارسی.
* **[PersianRAG (TahaBakhtari)](https://github.com/TahaBakhtari/PersianRAG)** ![RAG](https://img.shields.io/badge/RAG-amber?style=flat-square) — پایپ‌لاین آماده پرسش و پاسخ اسناد با معماری RAG.
* **[Bank Chatbot Legal RAG](https://github.com/Muhammad-davoudi/bank-chatbot)** ![RAG](https://img.shields.io/badge/RAG-amber?style=flat-square) — سیستم پاسخگویی به قوانین بانکی با کنترل توهم مدل.

---

## ۱۰. کتابخانه‌ها و ابزارهای مهندسی زبان
* **[DadmaTools](https://github.com/Dadmatech/DadmaTools)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) `Python` — تولکیت مدرن پردازش زبان فارسی (لماتایزر، تجزیه‌گر نحوی و برچسب‌زن POS).
* **[Hezar (هزار)](https://github.com/hezarai/hezar)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) `Python` — فریم‌ورک استاندارد هوش مصنوعی فارسی با پشتیبانی از تسک‌های چندوجهی.
* **[ParsiNLU](https://github.com/persiannlp/parsinlu)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) `Python` — مجموعه تسک‌های سطح بالای درک زبان فارسی.
* **[Persian-Tools](https://github.com/persian-tools/persian-tools)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) `TS / Python / Go / Rust` — کامل‌ترین جعبه‌ابزار اعتبارسنجی کدملی، کارت بانکی، تبدیل عدد به حروف و تقویم شمسی.
* **[Hazm (هضم)](https://github.com/roshan-research/hazm)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) `Python` — باسابقه‌ترین ابزار توکنایزیشن و پیش‌پردازش متن فارسی.
* **[Parsivar](https://github.com/ICTRC/Parsivar)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) `Python` — ابزار پیش‌پردازش متن بر اساس دستور خط فرهنگستان.
* **[Persian-NER (Text-Mining)](https://github.com/Text-Mining/Persian-NER)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) `Dataset` — بزرگ‌ترین پیکره شناسایی موجودیت‌های نامدار در زبان فارسی.
* **[Persian AI Glossary](https://github.com/snrazavi/Persian-AI-and-Machine-Learning-Glossary)** ![Docs](https://img.shields.io/badge/Docs-blue?style=flat-square) `MD` — واژه‌نامه تخصصی معادل‌های فارسی برای اصطلاحات هوش مصنوعی.

---

## ۱۱. ترجمه ماشینی و ترنسفر زبان
* **[mT5-ParsiNLU Opus Translation (FA-EN)](https://huggingface.co/persiannlp/mt5-small-parsinlu-opus-translation_fa_en)** ![NMT](https://img.shields.io/badge/NMT-purple?style=flat-square) — مدل ترجمه عصبی دوطرفه با بیش از ۵۰ هزار بار دانلود در هاگینگ‌فیس.
* **[Persian-To-English LoRA Translator](https://github.com/Mahdi-Maaref/Persian-To-English-Translator)** ![PEFT](https://img.shields.io/badge/PEFT-teal?style=flat-square) — مدل سبک ترجمه با تنظیم پارامتری (LoRA) برای سرورهای کم‌مصرف.
* **[EPUB AI Translator](https://github.com/Retro-Zero/epub-ai-translator)** ![Web-App](https://img.shields.io/badge/Web--App-blue?style=flat-square) — وب‌اپلیکیشن ترجمه کتاب‌های الکترونیکی با حفظ ساختار راست‌چین.

---

## ۱۲. افزونه‌ها، ابزارهای مرورگر و محیط‌های توسعه
* **[RTL Support for VS Code Agents](https://github.com/GuyRonnen/rtl-for-vs-code-agents)** ![VS-Code](https://img.shields.io/badge/VS--Code-blue?style=flat-square) — پشتیبانی رسمی از چیدمان راست‌به‌چپ (RTL) در ایجنت‌های کدنویسی VS Code و GitHub Copilot با حفظ بلوک‌های کد LTR.
* **[Kivun Terminal (Claude Code RTL)](https://github.com/noambrand/kivun-terminal-wsl)** ![Terminal](https://img.shields.io/badge/Terminal-slate?style=flat-square) — ترمینال اصلاح خروجی دوجهته (BiDi) برای اجرای بی‌نقص Claude Code در متون فارسی.
* **[BiDi Shaper](https://github.com/cc1a2b/bidi-shaper)** ![Text-Shaping](https://img.shields.io/badge/Text--Shaping-emerald?style=flat-square) — کتابخانه مستقل اتصال حروف فارسی و پیاده‌سازی UAX #9 برای Canvas و ترمینال‌ها.
* **[Nimruz Desktop](https://github.com/xmannii/nimruz-desktop)** ![Desktop](https://img.shields.io/badge/Desktop-slate?style=flat-square) — کلاینت گرافیکی دسکتاپ برای چت با مدل‌های محلی و خارجی به زبان فارسی.
* **[Hermes Agent Farsi](https://github.com/m4tinbeigi-official/hermes-agent-farsi)** ![UI-Mod](https://img.shields.io/badge/UI--Mod-orange?style=flat-square) — فارسی‌سازی کامل داشبورد، راست‌چین‌سازی و فونت وزیرمتن برای فریم‌ورک Hermes Agent.
* **[Persian AI RTL Assistant](https://github.com/tig-ndi/persian-ai-rtl-assistant)** ![Browser](https://img.shields.io/badge/Browser-sky?style=flat-square) — اصلاح خودکار جهت نمایش (RTL) در صفحات ChatGPT، Claude، DeepSeek و Mistral.
* **[Persian Text to PDF Converter](https://github.com/Ho3seinTork/Persian-Text-to-PDF-Converter)** ![Web-App](https://img.shields.io/badge/Web--App-blue?style=flat-square) — تبدیل خروجی‌های مارک‌داون LLMها به پی‌دی‌اف تمیز فارسی.
* **[Reply RTL Viewer](https://github.com/shahriyar3/reply-rtl-viewer)** ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) — نمایشگر مدرن متون مارک‌داون با تفکیک کدهای لاتین و متون فارسی.

---

## ۱۳. دیتاست‌ها و منابع ارزیابی داده
* **[PersianQA](https://github.com/sajjjadayobi/PersianQA)** ![QA](https://img.shields.io/badge/QA-violet?style=flat-square) — اولین دیتاست استاندارد پرسش و پاسخ زبان فارسی مبتنی بر ویکی‌پدیا.
* **[ManaTTS Speech Dataset](https://github.com/MahtaFetrat/ManaTTS-Persian-Speech-Dataset)** ![Audio](https://img.shields.io/badge/Audio-orange?style=flat-square) — بزرگ‌ترین دیتاست گفتار فارسی با بیش از ۱۱۴ ساعت صوت و متن متناظر.
* **[Persian Raw Text (80GB)](https://github.com/persiannlp/persian-raw-text)** ![Corpus](https://img.shields.io/badge/Corpus-blue?style=flat-square) — حدود ۸۰ گیگابایت متن خام پالایش‌شده برای پیش‌آموزش مدل‌های زبانی.
* **[SentiPers Corpus](https://github.com/phosseini/SentiPers)** ![Sentiment](https://img.shields.io/badge/Sentiment-red?style=flat-square) — پیکره مرجع تحلیل احساسات در زبان فارسی منتشرشده در arXiv.
* **[FarsInstruct](https://huggingface.co/datasets/ParsiAI/FarsInstruct)** ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) — مجموعه‌داده بزرگ تنظیم دستورالعمل برای دستیارهای هوشمند فارسی.
* **[Alpaca Persian](https://huggingface.co/datasets/sinarashidi/alpaca-persian)** ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) — دیتاست ۵۲ هزارتایی آموزش دستور ترجمه و بهینه‌سازی‌شده برای فارسی.
* **[Persian Voice v1 & Speech](https://huggingface.co/datasets/vhdm/persian-voice-v1)** ![Audio](https://img.shields.io/badge/Audio-orange?style=flat-square) — دیتاست نمونه‌های صوتی ضبط‌شده برای ترینینگ مدل‌های گفتار.
* **[Persian Wikipedia QA](https://huggingface.co/datasets/fibonacciai/Persian-Wikipedia-QA)** ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) — مجموعه‌داده جفت‌های پرسش و پاسخ ویکی‌پدیا فارسی.
* **[GPTInformal Speech Dataset](https://github.com/MahtaFetrat/GPTInformal-Persian-Speech-Dataset)** ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) — بیش از ۶ ساعت دیتای صوتی مکالمات غیررسمی مناسب ترینینگ مدل‌های صوتی.
* **[MirasText & Hamshahri Corpus](https://github.com/mhbashari/awesome-persian-nlp-ir)** ![Corpus](https://img.shields.io/badge/Corpus-blue?style=flat-square) — پیکره‌های چند ده‌میلیونی متون استاندارد و خبری زبان فارسی.

---

## 👥 سازندگان و حامیان (Maintainers & Backers)

این پروژه توسط سازمان **[Kalahamoon (کالاهامون)](https://github.com/Kalahamoon)** و با همراهی جامعه توسعه‌دهندگان و متخصصان هوش مصنوعی ایران نگهداری و گسترش می‌یابد.

---

## 📜 مجوز (License)

این پروژه تحت مجوز متن‌باز **MIT** منتشر شده است. برای اطلاعات بیشتر فایل [LICENSE](LICENSE) را مشاهده نمایید.

</div>
