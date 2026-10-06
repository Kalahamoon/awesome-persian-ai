# Awesome Persian AI & MCP Hub

<div dir="rtl" align="right">

<div align="center">

![Awesome Persian AI Banner](assets/banner.svg)

<br/>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Organization](https://img.shields.io/badge/Organization-Kalahamoon-6366f1.svg?style=flat-square)](https://github.com/Kalahamoon)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-10b981.svg?style=flat-square)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-f59e0b.svg?style=flat-square)](LICENSE)
[![English Version](https://img.shields.io/badge/Language-English_README-0ea5e9.svg?style=flat-square)](README.md)

<br/>

**مرجع جامع، مهندسی‌شده و متمرکز ابزارها، سرورهای پروتکل MCP، مدل‌های زبانی، سرویس‌های ابری و زیرساخت‌های تخصصی هوش مصنوعی برای زبان فارسی و اکوسیستم ایران.**

[English Version (نسخه انگلیسی)](README.md) • [راهنمای مشارکت](CONTRIBUTING.md) • [ثبت ابزار یا گزارش خطا](https://github.com/Kalahamoon/awesome-persian-ai/issues)

</div>

---

### 🦁 درود و سپاس از پیشگامان هوش مصنوعی فارسی

> **پیام تقدیر و افتخار:**  
> صمیمانه‌ترین درودها و تبریکات نثار تمامی دانشمندان، مهندسان نرم‌افزار، پژوهشگران هوش مصنوعی، فعالان جامعه متن‌باز و کارآفرینان ایرانی در سراسر کره زمین — از مراکز تحقیقاتی پیشرو در اروپا و آمریکای شمالی تا استارتاپ‌ها، شرکت‌های دانش‌بنیان و توسعه‌دهندگان مستقل در جای‌جای ایران عزیز — که با وجود پیچیده‌ترین شرایط تحریمی، موانع زیرساختی و نابرابری‌های دسترسی، هرگز متوقف نشدند و با پشتکار، ایثار علمی و خلاقیت ناب خود، جایگاه زبان، فرهنگ و هوش مصنوعی فارسی را در صدر تحولات جهانی پاس داشتند. این هاب تقدیم به تک‌تک شما همراهان سرافراز است. 🦁✨

---

## 🧭 فهرست دسته‌بندی‌ها

| شماره | عنوان بخش | خلاصه محتوا |
| :---: | :--- | :--- |
| **۰۱** | [🔌 سرورها و ابزارهای پروتکل MCP](#۱-سرورها-و-ابزارهای-پروتکل-mcp) | سرورهای بومی برای باسلام، دیجی‌کالا، دیوار، ترب، لیارا، کراولرمون، کسرا و بله |
| **۰۲** | [☁️ پلتفرم‌های ابری و درگاه‌های API](#۲-پلتفرمهای-ابری-و-درگاههای-api) | درگاه‌های بدون تحریم، فروش توکنی و سرورهای پردازش گرافیکی GPU |
| **۰۳** | [🧠 مدل‌های زبانی و بنیادی فارسی](#۳-مدلهای-زبانی-و-بنیادی-فارسی) | مدل‌های متن‌باز پایه، توکابرٹ، وزن‌های زبانی و لیدربوردهای رسمی |
| **۰۴** | [🤖 سیستم‌ها و فریم‌ورک‌های چندایجنتیک](#۴-سیستمها-و-فریمورکهای-چندایجنتیک) | عامل‌های مالی، تبدیل متن به SQL و منشی‌های صوتی تلفنی |
| **۰۵** | [🛡️ امنیت مدل‌های زبانی، گاردریل و ایمنی پرامپت](#۵-امنیت-مدلهای-زبانی-گاردریل-و-ایمنی-پرامپت) | دیواره‌های آتش زبانی، آزمون نفوذ پرامپت و جلوگیری از جیل‌بریک |
| **۰۶** | [⚖️🩺 هوش مصنوعی در حوزه‌های تخصصی](#۶-هوش-مصنوعی-در-حوزههای-تخصصی-حقوقی-و-سلامت) | سیستم‌عامل دفاتر وکالت، مدل‌های بالینی پزشکی و شبیه‌سازها |
| **۰۷** | [🎙️ پردازش گفتار، صوت و دوبله](#۷-پردازش-گفتار-صوت-و-دوبله) | بازشناسی گفتار فارسی (STT)، ابزار پیاده‌سازی ویدیو، سنتز گفتار و شبیه‌سازی صدا |
| **۰۸** | [👁️ بینایی ماشین و مدل‌های چندوجهی](#۸-بینایی-ماشین-و-مدلهای-چندوجهی) | مدل‌های چندوجهی فارسی (CLIP)، موتورهای OCR و تبدیل به LaTeX |
| **۰۹** | [📚 ابزارهای بازیابی اطلاعات و RAG بومی](#۹-ابزارهای-بازیابی-اطلاعات-و-rag-بومی) | مدل‌های برداری امبدینگ (Tooka-SBERT) و پایپ‌لاین‌های سازمانی اسناد |
| **۱۰** | [🛠️ کتابخانه‌ها و ابزارهای مهندسی زبان](#۱۰-کتابخانهها-و-ابزارهای-مهندسی-زبان) | نرمال‌سازها، واژه‌نماها، جعبه‌ابزارهای توکنایزیشن و رسم‌الخط |
| **۱۱** | [🌐 ترجمه ماشینی و ترنسفر زبان](#۱۱-ترجمه-ماشینی-و-ترنسفر-زبان) | مدل‌های ترجمه عصبی دوطرفه و مترجم‌های فرمت کتاب الکترونیکی |
| **۱۲** | [🖥️ رابط‌های کاربری، ابزارهای ایجنت و ابزارهای RTL](#۱۲-رابطهای-کاربری-ابزارهای-ایجنت-و-ابزارهای-rtl) | پلاگین opencode-rtl، افزونه‌های VS Code، ترمینال‌های BiDi و چیدمان متن |
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

| سرور / ابزار | برچسب‌ها | توضیحات عملکردی | پشته فنی | مستندات و مخزن |
| :--- | :---: | :--- | :---: | :---: |
| **[Basalam MCP Server](https://developers.basalam.com/docs/mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Production](https://img.shields.io/badge/Production-blue?style=flat-square) | سرور رسمی MCP بازار اجتماعی باسلام در آدرس `mcp.basalam.com/mcp` جهت جستجوی محصولات و مدیریت سفارش‌ها | HTTP Transport / OAuth | [مستندات باسلام](https://developers.basalam.com/docs/mcp) |
| **[Digikala MCP Server](https://github.com/mmdju/digikala-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | سرور MCP مستقل دیجی‌کالا با ۱۶ ابزار اختصاصی جستجو، مقایسه قیمت و استخراج مشخصات فنی | Cloudflare Workers / TS | [mmdju/digikala-mcp](https://github.com/mmdju/digikala-mcp) |
| **[Divar MCP Server](https://github.com/mmdju/divar-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | سرور MCP جستجو و تحلیل آگهی‌های پلتفرم دیوار (املاک، خودرو، کالا) | Cloudflare Workers / TS | [mmdju/divar-mcp](https://github.com/mmdju/divar-mcp) |
| **[Torob MCP Server](https://github.com/mmdju/torob-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | سرور MCP موتور مقایسه قیمت ترب شامل ۱۴ ابزار برای پایش تخفیف‌ها و نوسان قیمت | Cloudflare Workers / TS | [mmdju/torob-mcp](https://github.com/mmdju/torob-mcp) |

### ۱.۲. زیرساخت ابری و خزشگرهای وب

| سرور / ابزار | برچسب‌ها | توضیحات عملکردی | پشته فنی | مستندات و مخزن |
| :--- | :---: | :--- | :---: | :---: |
| **[Liara Cloud MCP Server](https://github.com/razavioo/liara-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | سرور MCP جامع مدیریت زیرساخت ابری لیارا؛ استقرار برنامه‌ها، مدیریت دیتابیس‌ها و دیسک‌ها با زبان طبیعی | TypeScript / Node.js | [GitHub](https://github.com/razavioo/liara-mcp) |
| **[Crawlemoon MCP Server](https://github.com/razavioo/crawlemoon)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | پلتفرم پیشرفته خزش و استخراج محتوای وب طراحی‌شده برای عصر ایجنت‌های هوش مصنوعی با خروجی تمیز مارک‌داون | Python / FastMCP | [GitHub](https://github.com/razavioo/crawlemoon) |
| **[Liara Docs MCP](https://github.com/SalehB1/Lira-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | سرور MCP جستجوی آفلاین مستندات لیارا و عیب‌یابی خطاهای استقرار | Python / Local Corpus | [SalehB1/Lira-mcp](https://github.com/SalehB1/Lira-mcp) |

### ۱.۳. سامانه‌های اتوماسیون، پیام‌رسان‌ها و اینترنت اشیاء

| سرور / ابزار | برچسب‌ها | توضیحات عملکردی | پشته فنی | دسترسی |
| :--- | :---: | :--- | :---: | :---: |
| **[Kasra MCP Server](https://github.com/razavioo/kasra-mcp-server)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | اتصال هوش مصنوعی به اتوماسیون تردد و پرسنلی کسرا برای ثبت مرخصی، مأموریت و مشاهده کارکرد | Python / FastMCP | [GitHub](https://github.com/razavioo/kasra-mcp-server) |
| **[Userbot Bale MCP](https://github.com/razavioo/userbot-bale)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | هسته کامل کلاینت پیام‌رسان بله و سرور MCP برای خواندن پیام‌ها، جستجو در کانال‌ها و ارسال پیام تاییدمحور | Python / Stdio | [GitHub](https://github.com/razavioo/userbot-bale) |
| **[Aira MCP Server](https://github.com/AiraChat/aira-mcp)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | سرور MCP و رجیستری کانکتورهای شناختی هوش مصنوعی فارسی | TypeScript | [AiraChat/aira-mcp](https://github.com/AiraChat/aira-mcp) |
| **[Hermes Agent Iran Gateway](https://github.com/hnkwing/hermes-agent-iran-gateway)** | ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | گیت‌وی متن‌باز اتصال ایجنت هرمس به پیام‌رسان‌های بومی بله و روبیکا | Python / LangGraph | [GitHub](https://github.com/hnkwing/hermes-agent-iran-gateway) |
| **[Smart Home KNX MCP](https://github.com/SMousavi7/smart-home-knx-thingsboard)** | ![MCP](https://img.shields.io/badge/MCP-purple?style=flat-square) ![IoT](https://img.shields.io/badge/IoT-blue?style=flat-square) | کنترل سیستم خانه هوشمند با فرمان‌های زبان طبیعی فارسی از طریق ترکیب KNX و اولاما | Python / Ollama | [SMousavi7/smart-home](https://github.com/SMousavi7/smart-home-knx-thingsboard) |

---

## ۲. پلتفرم‌های ابری و درگاه‌های API

| پلتفرم / سرویس | برچسب‌ها | مدل‌ها و دسترسی | قابلیت‌های زیرساختی | وب‌سایت |
| :--- | :---: | :--- | :--- | :---: |
| **[AIZamin (ای‌آی زمین)](https://aizamin.ir)** | ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![No-VPN](https://img.shields.io/badge/No--VPN-sky?style=flat-square) ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) | GPT-4o, Claude 3.5, Gemini, DeepSeek | فروش توکنی و حجمی بدون اشتراک ماهانه؛ سازگاری با OpenCode و VS Code با پرداخت تومان | [aizamin.ir](https://aizamin.ir) |
| **[متیس (Metis AI)](https://www.metisai.ir)** | ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![Iran-Access](https://img.shields.io/badge/Iran--Access-green?style=flat-square) ![Enterprise](https://img.shields.io/badge/Enterprise-slate?style=flat-square) | مدل‌های Frontier جهانی + مدل‌های بومی | پایدار در زمان قطعی اینترنت بین‌الملل، سیستم No-Code و کش توکن و حافظه RAG بومی | [metisai.ir](https://www.metisai.ir) |
| **[AvalAI (اول‌آی)](https://avalai.ir)** | ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![No-VPN](https://img.shields.io/badge/No--VPN-sky?style=flat-square) ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) | OpenAI, Anthropic, Mistral, LLaMA-3 | درگاه پرسرعت سازگار با SDK پایتون/JS اوپن‌ای‌آی با پرداخت شتابی ریالی | [avalai.ir](https://avalai.ir) |
| **[پارت دات آی‌آر (Part AI)](https://partsoftware.com)** | ![Enterprise](https://img.shields.io/badge/Enterprise-slate?style=flat-square) ![Iran-Access](https://img.shields.io/badge/Iran--Access-green?style=flat-square) | درنا ۲، سهاب، توکابرٹ، بینایی بانکی | بزرگ‌ترین اکوسیستم هوش مصنوعی بومی ایران (احراز هویت هوشمند و بینایی ماشین بانکی) | [partsoftware.com](https://partsoftware.com) |
| **[هوشیو (Hooshio)](https://hooshio.com)** | ![API-Gateway](https://img.shields.io/badge/API--Gateway-blue?style=flat-square) ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) | مدل‌های تصویرسازی و مدل‌های متنی | پایگاه دانش و ارائه‌دهنده راهکارهای شرکتی و اشتراک مدل‌های هوش مصنوعی | [hooshio.com](https://hooshio.com) |
| **[مه‌پرتو (Mehparto)](https://mehparto.ir)** | ![Enterprise](https://img.shields.io/badge/Enterprise-slate?style=flat-square) ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) | راهکارهای اختصاصی و استقرار لوکال | خدمات زیرساختی LLM و مدل‌های سفارشی برای سازمان‌های دولتی و خصوصی | [mehparto.ir](https://mehparto.ir) |
| **[ابر آروان (GPU IaaS)](https://arvancloud.ir)** | ![Iran-Access](https://img.shields.io/badge/Iran--Access-green?style=flat-square) ![Infrastructure](https://img.shields.io/badge/GPU--Cloud-blue?style=flat-square) | پردازنده‌های گرافیکی NVIDIA A100 / RTX | سرورهای ابری مجهز به پردازنده‌های گرافیکی با پهنای باند بالا در شبکه ملی | [arvancloud.ir](https://arvancloud.ir) |

---

## ۳. مدل‌های زبانی و بنیادی فارسی

### ۳.۱. مدل‌های متن‌باز و وزن‌های زبانی

| نام مدل | برچسب‌ها | پایه معماری | حجم | ویژگی‌ها و مشخصات | مخزن و هاگینگ‌فیس |
| :--- | :---: | :---: | :---: | :--- | :---: |
| **درنا ۲ (Dorna 2)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | LLaMA-3.1 | 8B | نسل دوم مدل پرچمدار درنا با درک عمیق از جملات و استدلال محاوره‌ای در فرمت GGUF | [Hugging Face](https://huggingface.co/aeranginkaman/Dorna2-Llama3.1-8B-Instruct-Q4_K_M-GGUF) |
| **مرال (Maral-7B)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | Mistral-7B | 7B | از معتبرترین مدل‌های پایه فارسی با درک عمیق از استعاره‌ها و ریزه‌کاری‌های زبان فارسی | [Hugging Face](https://huggingface.co/models?search=Maral-7B) |
| **TookaBERT** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Transformers](https://img.shields.io/badge/Transformers-yellow?style=flat-square) | BERT Base / Large | چندگانه | مدل بازنمایی زبانی قدرتمند فارسی آموزش‌دیده روی میلیاردها توکن متن توسط پارت | [Hugging Face](https://huggingface.co/PartAI/TookaBERT-Base) |
| **PersianMind** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | LLaMA-2 | 7B | مدل زبانی پژوهشی دانشگاه تهران برای درک مفاهیم علمی، ادبی و پرسش و پاسخ فارسی | [Hugging Face](https://huggingface.co/universitytehran/PersianMind-v1.0) |
| **سینا (Sina-LLM)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | LLaMA-3 | 8B | آموزش‌دیده روی حجم وسیعی از متون فارسی برای ارتقای توانایی استدلال، کدنویسی و ترجمه | [GitHub](https://github.com/snrazavi) |
| **AVA Series** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | LLaMA-3 / Mistral | 8B / 7B | سری مدل‌های آوا با فاین‌تیون باکیفیت و عملکرد روان در محاوره فارسی | [GitHub](https://github.com/mehdihosseinimoghadam/AVA-Llama-3) |
| **ParsBERT** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Transformers](https://img.shields.io/badge/Transformers-yellow?style=flat-square) | BERT Base | ۱۱۰ میلیون | مدل مرجع و بنیادین ترانسفورمر زبان فارسی با بیش از ۱۶۰ هزار بار دانلود در هاگینگ‌فیس | [Hugging Face](https://huggingface.co/HooshvareLab/bert-base-parsbert-uncased) |
| **ParsGPT** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | GPT-2 | چندگانه | مدل تولید متن زبان فارسی توسعه داده شده در هوشواره | [GitHub](https://github.com/hooshvare/parsgpt) |
| **Gemma-3-Persian** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Weights](https://img.shields.io/badge/Weights-purple?style=flat-square) | Google Gemma | 4B | فاین‌تیون دقیق بر روی نسل جدید مدل‌های سبک جما برای چت و ترجمه | [Hugging Face](https://huggingface.co/mshojaei77/gemma-3-4b-persian-v0) |
| **آوا (Ava-LLM)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Local-CPU](https://img.shields.io/badge/Local--CPU-cyan?style=flat-square) | Qwen-2.5 / Gemma | 2B / 7B | بسیار سبک، طراحی‌شده جهت استقرار لوکال روی لپ‌تاپ و سرورهای بدون کارت گرافیک با Ollama | [Hugging Face](https://huggingface.co/models?search=ava-llm) |
| **مدل‌های هزار (Hezar)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) ![Transformers](https://img.shields.io/badge/Transformers-yellow?style=flat-square) | BERT / RoBERTa / T5 | چندگانه | مدل‌های ویژه تسک‌های تخصصی: طبقه‌بندی احساسات، تشخیص نام اشخاص (NER) و خلاصه‌سازی | [GitHub](https://github.com/hezarai/hezar) |

### ۳.۲. لیدربوردها و بنچ‌مارک‌های ارزیابی

| بنچ‌مارک / لیدربورد | برچسب‌ها | حوزه ارزیابی | توضیحات | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[Open Persian LLM Leaderboard](https://huggingface.co/spaces/PartAI/open-persian-llm-leaderboard)** | ![Leaderboard](https://img.shields.io/badge/Leaderboard-pink?style=flat-square) | ارزیابی عمومی LLM | لیدربورد رسمی هاگینگ‌فیس برای رتبه‌بندی رقابتی مدل‌های زبانی فارسی | [Hugging Face Space](https://huggingface.co/spaces/PartAI/open-persian-llm-leaderboard) |
| **[persian-llm-eval](https://github.com/heyparsadev/persian-llm-eval)** | ![Benchmark](https://img.shields.io/badge/Benchmark-emerald?style=flat-square) | آزمون‌های قطعی | ۳۰۰ آیتم آزمون در ۱۰ شاخه تخصصی با فواصل اطمینان بوت‌استرپ | [GitHub](https://github.com/heyparsadev/persian-llm-eval) |
| **[PersianMMLU Benchmark](https://huggingface.co/spaces/raia-center/PersianMMLU)** | ![Benchmark](https://img.shields.io/badge/Benchmark-emerald?style=flat-square) | درک چندرشته‌ای دانشگاهی | بنچ‌مارک درک دانش دانشگاهی در ۵۷ رشته تخصصی به زبان فارسی | [Hugging Face Space](https://huggingface.co/spaces/raia-center/PersianMMLU) |
| **[ParsiEval](https://github.com/mshojaei77/ParsiEval)** | ![Benchmark](https://img.shields.io/badge/Benchmark-emerald?style=flat-square) | استدلال و ریاضیات | ارزیابی توانایی درک متون، استدلال و ریاضیات در مدل‌های بزرگ زبانی فارسی | [GitHub](https://github.com/mshojaei77/ParsiEval) |
| **[ParsBench](https://github.com/ParsBench/ParsBench)** | ![Toolkit](https://img.shields.io/badge/Toolkit-slate?style=flat-square) | آزمون‌های کاربردی | مجموعه ابزار و دیتاست برای محک زدن تسک‌های پیشرفته زبان فارسی | [GitHub](https://github.com/ParsBench/ParsBench) |
| **[TAAROFBENCH](https://github.com/niktaas/TAAROFBENCH)** | ![Research](https://img.shields.io/badge/EMNLP_2025-blue?style=flat-square) | کاربردشناسی و فرهنگ | ارزیابی مدل‌های زبانی در درک فرهنگ رفتاری، کنایه‌ها و تعارف در ارتباطات ایرانی | [GitHub](https://github.com/niktaas/TAAROFBENCH) |

---

## ۴. سیستم‌ها و فریم‌ورک‌های چندایجنتیک

| پروژه | برچسب‌ها | نوع ایجنت | ویژگی‌ها و کاربرد عملیاتی | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[LangGraph Multi-Agent Persian](https://github.com/SaharZarbafi/langgraph-multi-agent-persian)** | ![Agent](https://img.shields.io/badge/Multi--Agent-amber?style=flat-square) | چندعامله همکار | سیستم پروداکشن با معماری Actor-Critic و مسیریابی هوشمند میان مدل‌های مختلف | [GitHub](https://github.com/SaharZarbafi/langgraph-multi-agent-persian) |
| **[Rebex (ایجنت هوشمند ایران‌ریبیت)](https://github.com/razavioo/iranrebate-ai-agent)** | ![Agent](https://img.shields.io/badge/Finance--Agent-amber?style=flat-square) | ایجنت مالی | محیط کاربری ایجنتیک تحلیل بازار، شفافیت بروکرهای مالی و ریسرچ معامله‌گران | [GitHub](https://github.com/razavioo/iranrebate-ai-agent) |
| **[Local SQL Agent (Persian)](https://github.com/alisadeghiaghili/local-sql-agent)** | ![Agent](https://img.shields.io/badge/Text--to--SQL-amber?style=flat-square) | تبدیل متن به SQL | تبدیل امن زبان طبیعی فارسی به دستورات SQL با اعتبارسنجی نحوی AST و دسترسی ستونی | [GitHub](https://github.com/alisadeghiaghili/local-sql-agent) |
| **[Doctor Agent](https://github.com/SirBNL/doctor-agent)** | ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) | نوبت‌دهی پزشکی | ایجنت نوبت‌دهی با ابزارخوانی (Tool Calling) کاملاً لوکال با اولاما | [GitHub](https://github.com/SirBNL/doctor-agent) |
| **[Phone Agent](https://github.com/sepehr071/phone-agent)** | ![Agent](https://img.shields.io/badge/Voice--Agent-amber?style=flat-square) | منشی تلفنی هوشمند | پاسخ‌گویی صوتی خودکار بر بستر استریسک (STT -> LLM -> TTS در لحظه) به فارسی روان | [GitHub](https://github.com/sepehr071/phone-agent) |
| **[Micky Voice Assistant](https://github.com/xmannii/micky)** | ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) | دستیار صوتی دسکتاپ | دستیار صوتی ایجنتیک اولویت‌دار برای زبان فارسی با معماری ماژولار و رابط مدرن | [GitHub](https://github.com/xmannii/micky) |
| **[Moujez Summarizer Agent](https://github.com/kharazi/moujez)** | ![Agent](https://img.shields.io/badge/Agent-amber?style=flat-square) | تلخیص اسناد | ایجنت خلاصه‌سازی و عصاره‌کشی ساختاریافته از متون و گزارش‌های بلند فارسی | [GitHub](https://github.com/kharazi/moujez) |

---

## ۵. امنیت مدل‌های زبانی، گاردریل و ایمنی پرامپت

| ابزار / پروژه | برچسب‌ها | تمرکز تخصصی | توضیحات و راهکار دفاعی | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[MCI LLM Security Hackathon Archive](https://github.com/erfnzdeh/MCI-LLM-Security-Hackathon)** | ![Security](https://img.shields.io/badge/Security-red?style=flat-square) | آزمون نفوذ و جیل‌بریک | سناریوهای نفوذ به مدل‌های زبانی فارسی از طریق تکنیک‌های چندزبانه و چارچوب‌بندی | [GitHub](https://github.com/erfnzdeh/MCI-LLM-Security-Hackathon) |
| **[Persian LLM Security Evaluation](https://github.com/Haniyesabeghi/Persian-LLM-Security-Evaluation-BA)** | ![Security](https://img.shields.io/badge/Security-red?style=flat-square) | تزریق پرامپت | تحلیل آسیب‌پذیری و دفاع در برابر Prompt Injection در مدل‌های درنا و مرال | [GitHub](https://github.com/Haniyesabeghi/Persian-LLM-Security-Evaluation-BA) |
| **[Morphological Type Guards (MTG)](https://github.com/Moshe-ship/mtg)** | ![Security](https://img.shields.io/badge/Security-red?style=flat-square) | امنیت ابزارخوانی | لایه اعتبارسنجی تایپ‌شده برای جلوگیری از حملات دستکاری جهت‌گیری متن (BiDi Hijacking) | [GitHub](https://github.com/Moshe-ship/mtg) |
| **[PAIB Benchmark](https://github.com/Romohub/paib)** | ![Security](https://img.shields.io/badge/Security-red?style=flat-square) | یکپارچگی ایجنت | بنچ‌مارک سنجش مقاومت ایجنت‌های فارسی در برابر تغییر ناخواسته مجوزهای ابزار | [GitHub](https://github.com/Romohub/paib) |

---

## ۶. هوش مصنوعی در حوزه‌های تخصصی: حقوقی و سلامت

| پروژه | برچسب‌ها | حوزه تخصصی | قابلیت‌های کاربردی | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[Persian Legal Practice OS](https://github.com/ansariaiadmin/legal-platform)** | ![LegalTech](https://img.shields.io/badge/LegalTech-violet?style=flat-square) | حقوقی | سیستم‌عامل سلف‌هاستد دفاتر وکالت مجهز به ۶ ایجنت هوشمند و RAG سه‌گانه | [GitHub](https://github.com/ansariaiadmin/legal-platform) |
| **[Persian Legal RAG Agent](https://github.com/Hamidreza-Talei/persian-legal-rag-agent)** | ![LegalTech](https://img.shields.io/badge/LegalTech-violet?style=flat-square) | پرسش‌وپاسخ قوانین | پاسخگویی به سوالات حقوقی مدنی و کیفری ایران با LanceDB و بازرتبه‌بندی معنایی | [GitHub](https://github.com/Hamidreza-Talei/persian-legal-rag-agent) |
| **[Smart Legal Letterhead](https://github.com/ahmadsalamifar/smart-legal-letterhead)** | ![LegalTech](https://img.shields.io/badge/LegalTech-violet?style=flat-square) | اتوماسیون اسناد | تولیدکننده هوشمند لوایح و سربرگ‌های حقوقی فارسی با اعتبارسنجی اصطلاحات | [GitHub](https://github.com/ahmadsalamifar/smart-legal-letterhead) |
| **[PerMed (Persian Meditron)](https://github.com/neda-kheirkhah/PerMed)** | ![Healthcare](https://img.shields.io/badge/Healthcare-teal?style=flat-square) | مدل بالینی | مدل زبانی تخصصی پزشکی و دارویی فارسی مبتنی بر معماری Meditron | [GitHub](https://github.com/neda-kheirkhah/PerMed) |
| **[Persian Medical RAG Chatbot](https://github.com/yousef-mousavizade/Persian-Medical-RAG-Chatbot)** | ![Healthcare](https://img.shields.io/badge/Healthcare-teal?style=flat-square) | دارویی و بالینی | چت‌بات دارویی و بالینی متصل به دیتابیس‌های رسمی پزشکی ایران | [GitHub](https://github.com/yousef-mousavizade/Persian-Medical-RAG-Chatbot) |
| **[OSCE AI Tutor](https://github.com/NafisSam/osce-tutor)** | ![Healthcare](https://img.shields.io/badge/Healthcare-teal?style=flat-square) | آموزش بالینی | شبیه‌ساز آزمون‌های بالینی OSCE برای دانشجویان پزشکی ایران با ارزیابی چک‌لیست‌ها | [GitHub](https://github.com/NafisSam/osce-tutor) |

---

## ۷. پردازش گفتار، صوت و دوبله

### ۷.۱. تبدیل گفتار به متن (Speech-to-Text)

| مدل / سرویس | برچسب‌ها | معماری / نوع | نکات برجسته | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[wav2vec2-large-xlsr-53-persian](https://huggingface.co/jonatasgrosman/wav2vec2-large-xlsr-53-persian)** | ![STT](https://img.shields.io/badge/STT-blue?style=flat-square) | Wav2Vec2 | پردانلودترین مدل تشخیص گفتار فارسی در هاگینگ‌فیس با نزدیک به ۱ میلیون دانلود | [Hugging Face](https://huggingface.co/jonatasgrosman/wav2vec2-large-xlsr-53-persian) |
| **[Wav2Vec2 Persian v3](https://huggingface.co/m3hrdadfi/wav2vec2-large-xlsr-persian-v3)** | ![STT](https://img.shields.io/badge/STT-blue?style=flat-square) | Wav2Vec2 | مدل آکوستیک دقیق بازشناسی گفتار فارسی با حداقل نرخ خطای واژگانی | [Hugging Face](https://huggingface.co/m3hrdadfi/wav2vec2-large-xlsr-persian-v3) |
| **[Whisper-Persian-v4](https://huggingface.co/nezamisafa/whisper-persian-v4)** | ![Whisper](https://img.shields.io/badge/Whisper-purple?style=flat-square) | Whisper Large-v3 | بهینه‌سازی‌شده برای اصطلاحات محاوره‌ای، واژگان تخصصی و نویز محیطی | [Hugging Face](https://huggingface.co/nezamisafa/whisper-persian-v4) |
| **[Video Transcript Tool](https://github.com/razavioo/video-transcript-tool)** | ![Offline](https://img.shields.io/badge/Audio--Tool-emerald?style=flat-square) | ابزار خط فرمان | پیاده‌سازی آفلاین صوت و ویدیوهای فارسی/انگلیسی و دوبله هوشمند هوش مصنوعی | [GitHub](https://github.com/razavioo/video-transcript-tool) |
| **[Persian ASR Leaderboard](https://huggingface.co/spaces/navidved/open_persian_asr_leaderboard)** | ![Leaderboard](https://img.shields.io/badge/Leaderboard-pink?style=flat-square) | بنچ‌مارک | لیدربورد مقایسه‌ای عملکرد و خطای واژگانی (WER) مدل‌های بازشناسی گفتار فارسی | [Hugging Face Space](https://huggingface.co/spaces/navidved/open_persian_asr_leaderboard) |
| **[PersianScribe](https://github.com/duuuude/PersianScribe-for-Apple-Silicon)** | ![Offline](https://img.shields.io/badge/Offline-emerald?style=flat-square) | شتاب‌دهی اپل | تبدیل آفلاین گفتار به متن با تفکیک گوینده بهینه‌شده برای چیپ‌های M1 تا M4 | [GitHub](https://github.com/duuuude/PersianScribe-for-Apple-Silicon) |
| **[Nemotron ASR Streaming Farsi](https://huggingface.co/mehdi-hf/nemotron-asr-streaming-farsi)** | ![Streaming](https://img.shields.io/badge/Streaming-cyan?style=flat-square) | انویدیا نیموترون | تشخیص گفتار استریمینگ بلادرنگ با حداقل تاخیر مبتنی بر معماری انویدیا | [Hugging Face](https://huggingface.co/mehdi-hf/nemotron-asr-streaming-farsi) |
| **[فارس‌آوا](https://amerandish.com)** | ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) | سرویس تجاری | سرویس باسابقه و صنعتی تبدیل گفتار به متن فارسی شرکت عصر گویش‌پرداز | [amerandish.com](https://amerandish.com) |
| **[IoType (آی‌او تایپ)](https://www.iotype.com/api)** | ![Freemium](https://img.shields.io/badge/Freemium-indigo?style=flat-square) | API ابری | وب‌سرویس تایپ صوتی و تبدیل صوت به متن قابل ویرایش | [iotype.com](https://www.iotype.com/api) |

### ۷.۲. تبدیل متن به گفتار و شبیه‌سازی صدا (Text-to-Speech)

| مدل / سیستم | برچسب‌ها | نوع سنتز | ویژگی‌ها و مشخصات صوتی | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[Chatterbox-TTS-Persian-Farsi](https://huggingface.co/Thomcles/Chatterbox-TTS-Persian-Farsi)** | ![TTS](https://img.shields.io/badge/TTS-purple?style=flat-square) | سنتز عصبی | محبوب‌ترین و طبیعی‌ترین مدل تبدیل متن به صوت با لحن احساسی روان | [Hugging Face](https://huggingface.co/Thomcles/Chatterbox-TTS-Persian-Farsi) |
| **[Pocket TTS Farsi](https://huggingface.co/Nimaone/pocket-tts-farsi-v2-onnx)** | ![Lightweight](https://img.shields.io/badge/Lightweight-teal?style=flat-square) | فرمت ONNX | سنتز گفتار بسیار سبک برای موبایل‌ها، سیستم‌های امبدد و پردازنده‌های ضعیف | [Hugging Face](https://huggingface.co/Nimaone/pocket-tts-farsi-v2-onnx) |
| **[persian_tts](https://github.com/nimaone/persian_tts)** | ![Offline](https://img.shields.io/badge/Offline-emerald?style=flat-square) | شبیه‌سازی صدا | سنتز صدا همراه با قابلیت کلونینگ صدا (Voice Cloning) کاملاً آفلاین روی پردازنده معمولی | [GitHub](https://github.com/nimaone/persian_tts) |
| **[Mana Persian Piper](https://huggingface.co/MahtaFetrat/Mana-Persian-Piper)** | ![Piper](https://img.shields.io/badge/Piper-orange?style=flat-square) | پایپر تی‌تی‌اس | آموزش‌دیده روی گفتار چندگوینده فارسی با تلفظ واج‌شناسی دقیق | [Hugging Face](https://huggingface.co/MahtaFetrat/Mana-Persian-Piper) |
| **[dcho Voice Engine](https://github.com/AliAkrami1375/dcho)** | ![Edge](https://img.shields.io/badge/Edge-blue?style=flat-square) | موتور لبه | موتور صوتی سبک متن‌باز برای گجت‌های هوشمند و میکروکنترلرها | [GitHub](https://github.com/AliAkrami1375/dcho) |
| **[Gooya Bozorg (گویا بزرگ)](https://github.com/Reza2kn/gooya-bozorg-native)** | ![Desktop](https://img.shields.io/badge/Desktop-slate?style=flat-square) | نرم‌افزار دسکتاپ | برنامه دسکتاپ کراس‌پلتفرم برای خوانش کتاب‌های صوتی و متن‌های طولانی به فارسی روان | [GitHub](https://github.com/Reza2kn/gooya-bozorg-native) |

---

## ۸. بینایی ماشین و مدل‌های چندوجهی

| مدل / سوئیت | برچسب‌ها | پایه معماری | کاربرد و تسک‌ها | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[CLIPfa](https://github.com/sajjjadayobi/CLIPfa)** | ![Multimodal](https://img.shields.io/badge/Multimodal-pink?style=flat-square) | دوکدگذار CLIP | اتصال متن فارسی و تصویر برای جستجوی معنایی و دسته‌بندی صفر-شات تصویر | [GitHub](https://github.com/sajjjadayobi/CLIPfa) |
| **[Qwen2-VL Persian OCR](https://huggingface.co/mohajesmaeili/Qwen3-VL-2B-Persian-Arabic-Ocr-v1.0)** | ![Vision-LLM](https://img.shields.io/badge/Vision--LLM-purple?style=flat-square) | بینایی زبان | دیجیتالی‌سازی اسناد خطی، متون تاریخی و فرمول‌های پیچیده ریاضی | [Hugging Face](https://huggingface.co/mohajesmaeili/Qwen3-VL-2B-Persian-Arabic-Ocr-v1.0) |
| **[Persian OCR Master](https://github.com/JENOVASir/persianAi-OCR-MASTER)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | وب OCR | استخراج متن از تصاویر کتاب‌ها و دست‌خط‌ها با امکان خروجی به فایل Word | [GitHub](https://github.com/JENOVASir/persianAi-OCR-MASTER) |
| **[PDF-OCR-Math2LaTeX](https://github.com/Sadeghizad/pdf-ocr-fas-eng-math2latex)** | ![LaTeX](https://img.shields.io/badge/LaTeX-blue?style=flat-square) | پارسر معادلات | OCR متون دوزبانه فارسی/انگلیسی و تبدیل معادلات ریاضی به کدهای استاندارد LaTeX | [GitHub](https://github.com/Sadeghizad/pdf-ocr-fas-eng-math2latex) |
| **[Hezar Vision (هزار)](https://github.com/hezarai/hezar)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | ترانسفورمر بینایی | مدل‌های بینایی ماشین برای پلاک‌خوانی، کارت ملی، شناسنامه و اسکن اسناد | [GitHub](https://github.com/hezarai/hezar) |
| **[ایران OCR](https://www.iranocr.ir)** | ![Commercial](https://img.shields.io/badge/Commercial-slate?style=flat-square) | API تجاری | وب‌سرویس تخصصی تبدیل اسناد تصویری به متن با قابلیت جستجو | [iranocr.ir](https://www.iranocr.ir) |

---

## ۹. ابزارهای بازیابی اطلاعات و RAG بومی

### ۹.۱. مدل‌های برداری (Embedding Models)

| مدل برداری | برچسب‌ها | پایه ترانسفورمر | ویژگی‌های بازیابی معنایی | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[Tooka-SBERT (پارت)](https://huggingface.co/PartAI/Tooka-SBERT-V2-Large)** | ![Top-Embedding](https://img.shields.io/badge/Top--Embedding-emerald?style=flat-square) | Sentence-BERT | پیشرفته‌ترین مدل برداری فارسی آموزش‌دیده برای رتبه‌بندی معنایی و بازیابی متراکم اسناد | [Hugging Face](https://huggingface.co/PartAI/Tooka-SBERT-V2-Large) |
| **[Persian Embeddings](https://huggingface.co/heydariAI/persian-embeddings)** | ![Top-Embedding](https://img.shields.io/badge/Top--Embedding-emerald?style=flat-square) | Sentence Transformers | مدل برداری رتبه یک هاگینگ‌فیس آموزش‌دیده روی پیکره‌های بزرگ شباهت متن | [Hugging Face](https://huggingface.co/heydariAI/persian-embeddings) |
| **[BGE-M3 Multilingual](https://github.com/FlagOpen/FlagEmbedding)** | ![Multilingual](https://img.shields.io/badge/Multilingual-blue?style=flat-square) | چندزبانه پیشرفته | درک عمیق از جملات فارسی در دو روش متراکم (Dense) و کلمه‌کلیدی (Sparse) | [GitHub](https://github.com/FlagOpen/FlagEmbedding) |
| **[ParsBERT NLI](https://huggingface.co/parsi-ai-nlpclass/ParsBERT-nli-FarsTail-FarSick)** | ![NLI](https://img.shields.io/badge/NLI-violet?style=flat-square) | برت فارسی | مدل استنتاج معنایی و ارزیابی تطابق و تناقض اسناد متنی | [Hugging Face](https://huggingface.co/parsi-ai-nlpclass/ParsBERT-nli-FarsTail-FarSick) |

### ۹.۲. پایپ‌لاین‌های آماده RAG سازمانی

| سامانه RAG | برچسب‌ها | معماری پایپ‌لاین | توانمندی‌های پیاده‌سازی | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[PersianRAG](https://github.com/TahaBakhtari/PersianRAG)** | ![RAG](https://img.shields.io/badge/RAG-amber?style=flat-square) | وکتور RAG | پایپ‌لاین آماده پرسش و پاسخ بر روی آرشیو اسناد PDF فارسی | [GitHub](https://github.com/TahaBakhtari/PersianRAG) |
| **[Bank Chatbot Legal RAG](https://github.com/Muhammad-davoudi/bank-chatbot)** | ![RAG](https://img.shields.io/badge/RAG-amber?style=flat-square) | ضدتوهم سازمانی | سیستم پاسخگویی به مقررات بانکی و بخشنامه‌ها با کنترل توهم مدل | [GitHub](https://github.com/Muhammad-davoudi/bank-chatbot) |

---

## ۱۰. کتابخانه‌ها و ابزارهای مهندسی زبان

| کتابخانه | برچسب‌ها | زبان | توضیحات و کارکرد تخصصی | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[DadmaTools](https://github.com/Dadmatech/DadmaTools)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Python | تولکیت مدرن پردازش زبان فارسی؛ لماتایزر، تجزیه‌گر نحوی، برچسب‌زن ادوار سخن (POS) و خلاصه‌ساز | [GitHub](https://github.com/Dadmatech/DadmaTools) |
| **[Hezar (هزار)](https://github.com/hezarai/hezar)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Python | فریم‌ورک استاندارد هوش مصنوعی فارسی با یکپارچه‌سازی ترانسفورمرها، صوت و تصویر | [GitHub](https://github.com/hezarai/hezar) |
| **[ParsiNLU](https://github.com/persiannlp/parsinlu)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Python | مجموعه جامع تسک‌های سطح بالای درک زبان فارسی شامل درک مطلب و استنتاج معنایی | [GitHub](https://github.com/persiannlp/parsinlu) |
| **[Persian-Tools](https://github.com/persian-tools/persian-tools)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | TS / Py / Go / Rust | کامل‌ترین جعبه‌ابزار اعتبارسنجی کدملی، کارت بانکی، تبدیل عدد به حروف و تاریخ شمسی | [GitHub](https://github.com/persian-tools/persian-tools) |
| **[Hazm (هضم)](https://github.com/roshan-research/hazm)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Python | باسابقه‌ترین ابزار توکنایزیشن، ریشه‌یابی و پاک‌سازی متن برای ساخت پایپ‌لاین‌ها | [GitHub](https://github.com/roshan-research/hazm) |
| **[Parsivar](https://github.com/ICTRC/Parsivar)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | Python | مجموعه تخصصی پیش‌پردازش متن با رعایت دقیق دستور خط فرهنگستان | [GitHub](https://github.com/ICTRC/Parsivar) |
| **[Persian-NER](https://github.com/Text-Mining/Persian-NER)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | دیتابیس / ابزار | بزرگ‌ترین پیکره نشان‌گذاری‌شده شناسایی موجودیت‌های نامدار در زبان فارسی | [GitHub](https://github.com/Text-Mining/Persian-NER) |
| **[Persian AI Glossary](https://github.com/snrazavi/Persian-AI-and-Machine-Learning-Glossary)** | ![Docs](https://img.shields.io/badge/Docs-blue?style=flat-square) | مارک‌داون | واژه‌نامه تخصصی و استاندارد ترجمه اصطلاحات هوش مصنوعی و یادگیری عمیق | [GitHub](https://github.com/snrazavi/Persian-AI-and-Machine-Learning-Glossary) |

---

## ۱۱. ترجمه ماشینی و ترنسفر زبان

| مدل / ابزار | برچسب‌ها | پایه مدل | سطح کیفی و قابلیت‌ها | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[mT5-ParsiNLU Opus Translation](https://huggingface.co/persiannlp/mt5-small-parsinlu-opus-translation_fa_en)** | ![NMT](https://img.shields.io/badge/NMT-purple?style=flat-square) | گوگل mT5 | مدل ترجمه عصبی پیشرفته دوطرفه فارسی/انگلیسی با بیش از ۵۰ هزار بار دانلود | [Hugging Face](https://huggingface.co/persiannlp/mt5-small-parsinlu-opus-translation_fa_en) |
| **[Persian LoRA Translator](https://github.com/Mahdi-Maaref/Persian-To-English-Translator)** | ![PEFT](https://img.shields.io/badge/PEFT-teal?style=flat-square) | آداپتور LoRA | مدل سبک ترجمه با تنظیم پارامتری (LoRA) با حفظ لحن معنایی برای سرورهای کم‌مصرف | [GitHub](https://github.com/Mahdi-Maaref/Persian-To-English-Translator) |
| **[EPUB AI Translator](https://github.com/Retro-Zero/epub-ai-translator)** | ![Web-App](https://img.shields.io/badge/Web--App-blue?style=flat-square) | وب‌اپلیکیشن | ترجمه هوشمند کتاب‌های الکترونیکی به فارسی سلیس با حفظ چیدمان راست‌چین و جداول | [GitHub](https://github.com/Retro-Zero/epub-ai-translator) |

---

## ۱۲. رابط‌های کاربری، ابزارهای ایجنت و ابزارهای RTL

| ابزار | برچسب‌ها | محیط اجرا | هدف و رفع باگ | لینک |
| :--- | :---: | :---: | :--- | :---: |
| **[opencode-rtl](https://github.com/razavioo/opencode-rtl)** | ![DevTool](https://img.shields.io/badge/OpenCode--Plugin-blue?style=flat-square) | خط فرمان opencode | پلاگین جامع راست‌چین‌سازی رابط ترمینال opencode با محافظت کامل از بلوک‌های کد و دستورات | [GitHub](https://github.com/razavioo/opencode-rtl) |
| **[RTL for VS Code Agents](https://github.com/GuyRonnen/rtl-for-vs-code-agents)** | ![VS-Code](https://img.shields.io/badge/VS--Code-blue?style=flat-square) | افزونه VS Code | چیدمان طبیعی راست‌به‌چپ (RTL) در ایجنت‌های VS Code و Copilot با حفظ فرمت LTR کدها | [GitHub](https://github.com/GuyRonnen/rtl-for-vs-code-agents) |
| **[Kivun Terminal](https://github.com/noambrand/kivun-terminal-wsl)** | ![Terminal](https://img.shields.io/badge/Terminal-slate?style=flat-square) | ترمینال CLI | ترمینال اصلاح متن دوجهته (BiDi) برای اجرای بی‌نقص Claude Code بدون برعکس شدن حروف | [GitHub](https://github.com/noambrand/kivun-terminal-wsl) |
| **[BiDi Shaper](https://github.com/cc1a2b/bidi-shaper)** | ![Text-Shaping](https://img.shields.io/badge/Text--Shaping-emerald?style=flat-square) | کتابخانه مستقل | موتور سبک اتصال حروف فارسی و پیاده‌سازی استاندارد UAX #9 برای Canvas و موتورهای بازی | [GitHub](https://github.com/cc1a2b/bidi-shaper) |
| **[Nimruz Desktop](https://github.com/xmannii/nimruz-desktop)** | ![Desktop](https://img.shields.io/badge/Desktop-slate?style=flat-square) | کلاینت دسکتاپ | رابط کاربری گرافیکی مدرن دسکتاپ با تایپوگرافی فارسی برای چت با مدل‌های لوکال و ابری | [GitHub](https://github.com/xmannii/nimruz-desktop) |
| **[Hermes Agent Farsi](https://github.com/m4tinbeigi-official/hermes-agent-farsi)** | ![UI-Mod](https://img.shields.io/badge/UI--Mod-orange?style=flat-square) | داشبورد وب | بومی‌سازی کامل، راست‌چین‌سازی و فونت وزیرمتن برای فریم‌ورک محبوب Hermes Agent | [GitHub](https://github.com/m4tinbeigi-official/hermes-agent-farsi) |
| **[Persian AI RTL Assistant](https://github.com/tig-ndi/persian-ai-rtl-assistant)** | ![Browser](https://img.shields.io/badge/Browser-sky?style=flat-square) | افزونه مرورگر | اصلاح خودکار جهت نمایش (RTL) در صفحات وب چت‌بات‌های ChatGPT، Claude و DeepSeek | [GitHub](https://github.com/tig-ndi/persian-ai-rtl-assistant) |
| **[Persian Text to PDF](https://github.com/Ho3seinTork/Persian-Text-to-PDF-Converter)** | ![Web-App](https://img.shields.io/badge/Web--App-blue?style=flat-square) | ابزار وب | تبدیل خروجی‌های مارک‌داون LLMها به پی‌دی‌اف تمیز فارسی بدون خرابی فونت | [GitHub](https://github.com/Ho3seinTork/Persian-Text-to-PDF-Converter) |
| **[Reply RTL Viewer](https://github.com/shahriyar3/reply-rtl-viewer)** | ![Open-Source](https://img.shields.io/badge/Open--Source-emerald?style=flat-square) | نمایشگر مارک‌داون | نمایشگر تک‌فایلی متون مارک‌داون با ایزوله‌سازی BiDi برای جلوگیری از تداخل کدهای انگلیسی | [GitHub](https://github.com/shahriyar3/reply-rtl-viewer) |

---

## ۱۳. دیتاست‌ها و منابع ارزیابی داده

| مجموعه‌داده | برچسب‌ها | نوع تسک / مدالیته | حجم داده | شرح و کاربرد آموزشی | لینک |
| :--- | :---: | :---: | :---: | :--- | :---: |
| **[PersianQA](https://github.com/sajjjadayobi/PersianQA)** | ![QA](https://img.shields.io/badge/QA-violet?style=flat-square) | درک مطلب | ۹,۰۰۰+ جفت | اولین دیتاسِت استاندارد پرسش و پاسخ زبان فارسی مبتنی بر مقالات ویکی‌پدیا | [GitHub](https://github.com/sajjjadayobi/PersianQA) |
| **[ManaTTS Speech Dataset](https://github.com/MahtaFetrat/ManaTTS-Persian-Speech-Dataset)** | ![Audio](https://img.shields.io/badge/Audio-orange?style=flat-square) | داده صوتی گفتار | ۱۱۴+ ساعت | بزرگ‌ترین دیتاسِت متن‌باز گفتار فارسی همراه با فایل‌های صوتی و متن متناظر باکیفیت | [GitHub](https://github.com/MahtaFetrat/ManaTTS-Persian-Speech-Dataset) |
| **[Persian Raw Text (80GB)](https://github.com/persiannlp/persian-raw-text)** | ![Corpus](https://img.shields.io/badge/Corpus-blue?style=flat-square) | متن خام پالایش‌شده | حدود ۸۰ گیگابایت | پیکره عظیم متنی تمیزشده برای آموزش اولیه (Pre-training) مدل‌های بزرگ زبانی | [GitHub](https://github.com/persiannlp/persian-raw-text) |
| **[SentiPers Corpus](https://github.com/phosseini/SentiPers)** | ![Sentiment](https://img.shields.io/badge/Sentiment-red?style=flat-square) | تحلیل احساسات | بنچ‌مارک مرجع | پیکره استاندارد تحلیل احساسات زبان فارسی منتشر و داوری‌شده در arXiv | [GitHub](https://github.com/phosseini/SentiPers) |
| **[FarsInstruct](https://huggingface.co/datasets/ParsiAI/FarsInstruct)** | ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) | تیونینگ دستورات | چندمرحله‌ای | دیتاسِت مقیاس‌بزرگ تنظیم دستورالعمل برای ترازسازی رفتار مدل‌های زبانی فارسی | [Hugging Face](https://huggingface.co/datasets/ParsiAI/FarsInstruct) |
| **[Alpaca Persian](https://huggingface.co/datasets/sinarashidi/alpaca-persian)** | ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) | دستورات گفتگویی | ۵۲,۰۰۰ نمونه | ترجمه و تطبیق فرهنگی دیتاسِت استاندارد Alpaca برای چت‌بات‌های فارسی | [Hugging Face](https://huggingface.co/datasets/sinarashidi/alpaca-persian) |
| **[Persian Voice v1](https://huggingface.co/datasets/vhdm/persian-voice-v1)** | ![Audio](https://img.shields.io/badge/Audio-orange?style=flat-square) | ضبط صدای گویندگان | چندگوینده | دیتاسِت صوتی برای آموزش مدل‌های بازشناسی، تفکیک گوینده و کلونینگ صدا | [Hugging Face](https://huggingface.co/datasets/vhdm/persian-voice-v1) |
| **[Persian Wikipedia QA](https://huggingface.co/datasets/fibonacciai/Persian-Wikipedia-QA)** | ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) | پرسش دانشنامه‌ای | زوج‌های دانش | مجموعه‌داده پرسش و پاسخ استخراج‌شده از ویکی‌پدیا برای آموزش بازیاب‌های RAG | [Hugging Face](https://huggingface.co/datasets/fibonacciai/Persian-Wikipedia-QA) |
| **[GPTInformal Speech Dataset](https://github.com/MahtaFetrat/GPTInformal-Persian-Speech-Dataset)** | ![Dataset](https://img.shields.io/badge/Dataset-teal?style=flat-square) | گفتار غیررسمی | ۶+ ساعت | جفت‌های صوتی و متنی محاوره‌ای برای تنظیم دقیق مدل‌های صوتی به زبان گفتار عامیانه | [GitHub](https://github.com/MahtaFetrat/GPTInformal-Persian-Speech-Dataset) |
| **[MirasText & Hamshahri Corpus](https://github.com/mhbashari/awesome-persian-nlp-ir)** | ![Corpus](https://img.shields.io/badge/Corpus-blue?style=flat-square) | متون مطبوعاتی | چند میلیون مقاله | پیکره‌های مطبوعاتی و خبری برای مدل‌سازی آماری زبان و پیش‌آموزش مدل‌ها | [GitHub](https://github.com/mhbashari/awesome-persian-nlp-ir) |

---

## 👥 سازندگان و حامیان (Maintainers & Backers)

این پروژه توسط سازمان **[Kalahamoon (کالاهامون)](https://github.com/Kalahamoon)** و با همراهی جامعه توسعه‌دهندگان و متخصصان هوش مصنوعی ایران نگهداری و گسترش می‌یابد.

---

## 📜 مجوز (License)

این پروژه تحت مجوز متن‌باز **MIT** منتشر شده است. برای اطلاعات بیشتر فایل [LICENSE](LICENSE) را مشاهده نمایید.

</div>
