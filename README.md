# Ücretsiz Yapay Zeka API'leri, Python Kütüphaneleri ve Otomasyon Araçları

![son güncelleme](https://img.shields.io/badge/son%20g%C3%BCncelleme-2026-10-20-brightgreen) ![test edilen api](https://img.shields.io/badge/çal%C4%B1%C5%9Fan%20API-8%2F8-blue)

Kredi kartı istemeyen yapay zeka servisleri, yeni çıkan Python kütüphaneleri ve açık kaynak otomasyon araçları. Türkçe.

**Bu listeyi farklı yapan şey:** her API kaydı otomatik test edilir ve yanında son test tarihi yazar. Haftada iki kez, Salı ve Cuma günleri güncellenir. Çalışmayan servis işaretlenir, listede yalan bilgi kalmaz.

## İçindekiler

- [Ücretsiz ve kartsız API'ler](#ücretsiz-ve-kartsız-apiler)
- [Yeni Python kütüphaneleri](#yeni-python-kütüphaneleri)
- [Açık kaynak otomasyon araçları](#açık-kaynak-otomasyon-araçları)
- [Nasıl katkı verirsin](#nasıl-katkı-verirsin)
- [Değişiklik günlüğü](#değişiklik-günlüğü)

## Ücretsiz ve kartsız API'ler

Kredi kartı istemeden kullanabildiğin servisler. Durum sütunu her güncellemede yeniden test edilir.

| Servis | Ne veriyor | Kart ister mi | Durum | Son test |
|---|---|---|---|---|
| [Groq](https://api.groq.com) | LLM ve Whisper konuşma tanıma | hayır | ✅ çalışıyor | 2026-10-20 |
| [Openverse](https://openverse.org) | telifsiz görsel arama | hayır | ✅ çalışıyor | 2026-10-20 |
| [Pollinations](https://pollinations.ai) | metinden görsel üretme | hayır | ✅ çalışıyor | 2026-10-20 |
| [PyPI JSON](https://pypi.org) | paket bilgisi | hayır | ✅ çalışıyor | 2026-10-20 |
| [Wikimedia REST](https://wikimedia.org) | ansiklopedi ve görsel | hayır | ✅ çalışıyor | 2026-10-20 |
| [Frankfurter](https://frankfurter.dev) | döviz kuru | hayır | ✅ çalışıyor | 2026-10-20 |
| [Open-Meteo](https://open-meteo.com) | hava durumu | hayır | ✅ çalışıyor | 2026-10-20 |
| [CoinGecko](https://coingecko.com) | kripto fiyat | hayır | ✅ çalışıyor | 2026-10-20 |

## Yeni Python kütüphaneleri

PyPI'da yeni yayınlanan, puanlamayı geçen paketler. Puan; sürüm sayısı, kaynak kod deposunun varlığı, lisans ve açıklama kalitesinden hesaplanır.

| Paket | Sürüm | Ne işe yarar | Puan | Eklendi |
|---|---|---|---|---|
| [tamias](https://pypi.org/project/tamias/) | 0.1.0a8 | Local HTTP proxy that logs token usage and cost per request for OpenAI-compatible agents. | 75 | 2026-10-20 |
| [biocartoon](https://pypi.org/project/biocartoon/) | 0.1.1 | Search and download the BioCartoon catalog of open-licensed scientific illustrations from  | 75 | 2026-10-20 |
| [seam](https://pypi.org/project/seam/) | 3.18.0 | SDK for the Seam API written in Python. | 85 | 2026-10-20 |
| [ho](https://pypi.org/project/ho/) | 0.0.18 | Http Objects - Tools to make python interfaces to http services | 90 | 2026-10-20 |
| [pubmed-search-mcp](https://pypi.org/project/pubmed-search-mcp/) | 0.8.0 | MCP SDK v2 server for PubMed and multi-source biomedical literature research | 90 | 2026-10-20 |
| [ryde-cli](https://pypi.org/project/ryde-cli/) | 0.1.1 | Unofficial Ryde CLI, local ride-map dashboard, and read-only MCP server | 75 | 2026-10-16 |
| [strike-ai](https://pypi.org/project/strike-ai/) | 0.1.1 | Client for the Strike API: typed yes/no, choice, and score decisions. | 75 | 2026-10-16 |
| [pykorail](https://pypi.org/project/pykorail/) | 0.4.0 | 코레일(KTX) 스마트 예매 비공식 Python 클라이언트 | 85 | 2026-10-16 |
| [sciwidgets](https://pypi.org/project/sciwidgets/) | 0.9.1 | PySide6 widgets for scientific desktop apps: LaTeX labels, sliders, parameter panels, Matp | 90 | 2026-10-16 |
| [minibot](https://pypi.org/project/minibot/) | 0.33.0 | Self-hosted Telegram-first AI assistant with async tooling, memory, and scheduling. | 95 | 2026-10-16 |
| [invisible-puppeteer](https://pypi.org/project/invisible-puppeteer/) | 0.4.0 | pyppeteer's API for a patched Firefox with a deterministic stealth profile. | 90 | 2026-10-13 |
| [ww-agentic-workflows](https://pypi.org/project/ww-agentic-workflows/) | 1.0.0b2 | A local-first, resumable workflow CLI for people and AI agents. | 95 | 2026-10-13 |
| [prizm-adls-scanner](https://pypi.org/project/prizm-adls-scanner/) | 0.3.8 | Prizm Databricks Exception, Lookup, Comparison, and Materialize job runtime | 95 | 2026-10-13 |
| [stabilize](https://pypi.org/project/stabilize/) | 0.33.1 | Stabilize Workflow Orchestration - Agentic Parallel Workflows | 95 | 2026-10-13 |
| [xstate-statemachine](https://pypi.org/project/xstate-statemachine/) | 0.11.0 | A robust Python library for parsing and running XState JSON state machines. | 95 | 2026-10-13 |
| [teddy-cli](https://pypi.org/project/teddy-cli/) | 0.1.16 | A local-first, file-based AI coding workflow that applies the UNIX philosophy to AI collab | 80 | 2026-10-09 |
| [bouwmeester-lockbox-api](https://pypi.org/project/bouwmeester-lockbox-api/) | 0.1.4 | Python client for the Bouwmeester Lab Lockbox REST API | 85 | 2026-10-09 |
| [APIPod](https://pypi.org/project/APIPod/) | 1.0.29 | Create web-APIs for long-running tasks | 90 | 2026-10-09 |
| [fastsdk](https://pypi.org/project/fastsdk/) | 0.4.21 | Turn any AI/web service (OpenAPI, Replicate, RunPod, APIPod) into a native-feeling Python  | 95 | 2026-10-09 |
| [apipod-registry](https://pypi.org/project/apipod-registry/) | 0.1.9 | Parse, hold and persist AIServices: the registry for APIPod clients. | 95 | 2026-10-09 |
| [cadpilot](https://pypi.org/project/cadpilot/) | 0.7.6 | CADPilot-MCP: Automatic CAD — MCP server that lets AI clients drive FreeCAD to create, edi | 90 | 2026-10-06 |
| [pten](https://pypi.org/project/pten/) | 0.4.16 | A tool to use WeWork(企业微信) and feishu(飞书) API quickly and easily | 90 | 2026-10-06 |
| [pyrig](https://pypi.org/project/pyrig/) | 18.98.0 | A Python project setup and management tool built on infrastructure as code and convention  | 90 | 2026-10-06 |
| [matrixai-core](https://pypi.org/project/matrixai-core/) | 1.14.0 | Auditable AI model language, runtime and deployment framework | 95 | 2026-10-06 |
| [odoo-addon-base-rest](https://pypi.org/project/odoo-addon-base-rest/) | 18.0.1.2.0 | Develop your own high level REST APIs for Odoo thanks to this addon. | 95 | 2026-10-06 |
| [aspose-total-net](https://pypi.org/project/aspose-total-net/) | 26.8.0 | Aspose.Total for Python via .NET is a document/visio/pdf/presentation/imaging/3D & CAD met | 75 | 2026-10-02 |
| [aiorentman](https://pypi.org/project/aiorentman/) | 0.2.1 | Unofficial asynchronous Python library to interact with the Rentman API | 75 | 2026-10-02 |
| [aiofarmad](https://pypi.org/project/aiofarmad/) | 0.2.0 | Unofficial asynchronous Python library to interact with the Mijn Farmad Apotheek API | 75 | 2026-10-02 |
| [embodify-mcp](https://pypi.org/project/embodify-mcp/) | 0.1.0a2 | Embodify MCP server: robot observation and control tools for the agent you already use | 80 | 2026-10-02 |
| [bambooai](https://pypi.org/project/bambooai/) | 2.0.1 | An LLM-driven data analyst that works in a persistent Python kernel, one cell at a time, a | 95 | 2026-10-02 |
| [ros2-inspector-mcp](https://pypi.org/project/ros2-inspector-mcp/) | 0.1.1 | Read-only MCP server that lets LLMs inspect and analyze ROS 2 systems (nodes, topics, para | 75 | 2026-09-29 |
| [shopping-cli](https://pypi.org/project/shopping-cli/) | 3.2.6 | Standalone local-commerce AI consultation marketplace runtime | 80 | 2026-09-29 |
| [searchmux](https://pypi.org/project/searchmux/) | 0.1.4 | The search layer for AI agents over SerpApi | 85 | 2026-09-29 |
| [guillotina](https://pypi.org/project/guillotina/) | 7.1.5 | asyncio REST API Resource database | 90 | 2026-09-29 |
| [argus-obs-semconv](https://pypi.org/project/argus-obs-semconv/) | 1.0.0a12 | Convenciones semanticas de Argus. Para LIBRERIAS: depende solo de la API de OpenTelemetry. | 95 | 2026-09-29 |
| [spaex](https://pypi.org/project/spaex/) | 5.2.2 | spaex 4.0: reproducible coding harnesses for any repo. Compose skills, MCPs, constitutions | 80 | 2026-09-25 |
| [srift](https://pypi.org/project/srift/) | 4.0.0.post1 | Zero-config, end-to-end encrypted peer-to-peer file transfer CLI and MCP server for AI age | 80 | 2026-09-25 |
| [maplibre-tiles](https://pypi.org/project/maplibre-tiles/) | 0.2.0 | Python bindings for MapLibre Tile (MLT) format | 90 | 2026-09-25 |
| [heylead](https://pypi.org/project/heylead/) | 0.10.399 | MCP-native autonomous LinkedIn SDR. Your AI sales rep, one command to fill your pipeline. | 90 | 2026-09-25 |
| [bonicos](https://pypi.org/project/bonicos/) | 0.11.0 | One Python SDK for every BonicBot — transport-agnostic, replaces bonicbot (BLE) and bonicb | 95 | 2026-09-25 |

## Açık kaynak otomasyon araçları

Son 30 günde açılmış, yıldız hızı yüksek depolar. Yıldız hızı günlük kazanılan yıldız demektir, tek seferlik zirveleri değil süregelen ilgiyi ölçer.

| Depo | Ne işe yarar | Yıldız | Yıldız/gün | Eklendi |
|---|---|---|---|---|
| [openspline/openspline](https://github.com/openspline/openspline) | Give a face to your voice AI in 5 lines of code. Generate realtime avatar video  | 225 | 11.2 | 2026-10-20 |
| [Folkbench/folkbench](https://github.com/Folkbench/folkbench) | AI API 中转站评测排行与切换工具：实测可用率、延迟与价格 · Open-source AI API relay benchmark, rankings & | 2077 | 115.4 | 2026-10-20 |
| [deeplethe/solid-glass](https://github.com/deeplethe/solid-glass) | A design system for AI applications. Material, physical, tactile, technical. | 2388 | 298.5 | 2026-10-20 |
| [Hybirdss/Hycli](https://github.com/Hybirdss/Hycli) | Websites, ready for AI. Turn website tasks into verified CLI and MCP actions, wi | 345 | 34.5 | 2026-10-20 |
| [songshikang0111/awesome-REA-cases](https://github.com/songshikang0111/awesome-REA-cases) | A curated collection of REA and AI-assisted reverse engineering cases, projects, | 292 | 36.5 | 2026-10-20 |
| [KKKKhazix/AIHOT](https://github.com/KKKKhazix/AIHOT) | 一个自己找热点、自己写日报的网站框架。把信源和精选标准换成你的，它就是你的行业热点站。 | 7858 | 462.2 | 2026-10-16 |
| [nano-muse/nanoMuse](https://github.com/nano-muse/nanoMuse) | nanoMuse: an open-source personal agent for every device you own. One agent with | 1306 | 56.8 | 2026-10-16 |
| [datalab-to/indra](https://github.com/datalab-to/indra) | Fast CPU OCR: line detection, CTC recognition, reading order, markdown | 382 | 191.0 | 2026-10-16 |
| [jiwoochris/artex-global](https://github.com/jiwoochris/artex-global) | ARTEX 한국어판 · AI 자율 침투 테스트 프레임워크(upstream: Autumn-27/ARTEX, AGPL-3.0) | 1567 | 130.6 | 2026-10-16 |
| [hitkeeen/blender-ai-addon](https://github.com/hitkeeen/blender-ai-addon) | Blender add-on: create and edit 3D models by chatting with AI - send text or an  | 215 | 30.7 | 2026-10-16 |
| [xcisxc29/dsh-wechat](https://github.com/xcisxc29/dsh-wechat) | WeChat channel for DeepSeek Harness | 147 | 29.4 | 2026-10-13 |
| [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | Let an AI model use a real iPhone with a $7 ESP32: AirPlay eyes, USB HID hands,  | 1114 | 1114.0 | 2026-10-13 |
| [jiwoochris/artex-ko](https://github.com/jiwoochris/artex-ko) | ARTEX 한국어판 · AI 자율 침투 테스트 프레임워크(upstream: Autumn-27/ARTEX, AGPL-3.0) | 1408 | 156.4 | 2026-10-13 |
| [onehumanbeing/esp32-iphone-agent](https://github.com/onehumanbeing/esp32-iphone-agent) | Let an AI model use a real iPhone with a $7 ESP32: AirPlay eyes, USB HID hands,  | 1114 | 1114.0 | 2026-10-13 |
| [zhuyansen/new-term-radar](https://github.com/zhuyansen/new-term-radar) | Daily radar for new AI terms: names of new models, products and repos, caught on | 758 | 758.0 | 2026-10-13 |
| [z91772524-ai/pojia-next](https://github.com/z91772524-ai/pojia-next) | 一个脚本搞定 DSH / WorkBuddy / ZCode / Codex / Cursor / Claude 六客户端的提示词与人格替换：零依赖、双击即用、 | 198 | 9.4 | 2026-10-09 |
| [Sidiora-Labs/centra-gideon-agent](https://github.com/Sidiora-Labs/centra-gideon-agent) | The companion AI agent that learns, adapts and gets the work done no matter the  | 217 | 9.9 | 2026-10-09 |
| [nachisama/ai-data-extractor](https://github.com/nachisama/ai-data-extractor) | Free open-source extractor for AI coding assistant chat histories. Supports Clau | 148 | 148.0 | 2026-10-09 |
| [LosaLosSantos/aurelio-finance](https://github.com/LosaLosSantos/aurelio-finance) | Open-source personal finance app with an AI financial advisor: track your net wo | 707 | 353.5 | 2026-10-09 |
| [yi1108/printfilm](https://github.com/yi1108/printfilm) | PRINTFILM: AI short-video marketing and AI short-drama creation platform | 5053 | 174.2 | 2026-10-09 |
| [Edwardxlai/easyread](https://github.com/Edwardxlai/easyread) | 把英文论文读成舒服的中文：本地 PDF 论文翻译、原文对照、边读边问 AI、文献管理。Read English papers in comfortable Ch | 814 | 162.8 | 2026-10-06 |
| [QingYunA/answer-me-with-html](https://github.com/QingYunA/answer-me-with-html) | Answer me with HTML — an agent skill that answers hard questions with a one-page | 1583 | 395.8 | 2026-10-06 |
| [Ebony-Vinyl/dsh-our-free-model](https://github.com/Ebony-Vinyl/dsh-our-free-model) | 在 dsh 里装上这个插件即可，无需登录、注册或填 API Key，就能使用包括 DeepSeek V4.1 Flash、Kimi K3 在内的前沿模型——完全 | 1885 | 171.4 | 2026-10-06 |
| [yakuikai/tokentab](https://github.com/yakuikai/tokentab) | Local-first CLI and web dashboard that reads Claude Code, Codex and Gemini CLI s | 176 | 12.6 | 2026-10-06 |
| [malevrigns/agent-jev](https://github.com/malevrigns/agent-jev) | AgentJev-0.6B - a fast 'System One' decision model for AI Agents: feed it any un | 341 | 24.4 | 2026-10-06 |
| [undefined-ui/second-brain-os](https://github.com/undefined-ui/second-brain-os) | An AI second brain that maintains itself. Full guide, starter vault, agent skill | 862 | 35.9 | 2026-10-02 |
| [youngyangyang04/llm-master](https://github.com/youngyangyang04/llm-master) | 大模型（LLM）全栈学习路线与中文教程🔥：覆盖 Prompt Engineering、RAG、AI Agent、MCP、微调、模型部署、Transformer、 | 1058 | 52.9 | 2026-10-02 |
| [ant-research/AntOmniEvo](https://github.com/ant-research/AntOmniEvo) | An auto-evolution framework that optimizes anything — your 7×24 team of algorith | 899 | 52.9 | 2026-10-02 |
| [nanaism/yomiyasu](https://github.com/nanaism/yomiyasu) | AI生成の日本語を自然な日本語へ推敲するAgent Skill / Agent Skill for Refining AI-Generated Japanese | 1102 | 1102.0 | 2026-10-02 |
| [suvamneog/jobradar](https://github.com/suvamneog/jobradar) | Watches company job boards, scores openings against your resume, and emails you  | 147 | 21.0 | 2026-10-02 |
| [ufo-ai/ufo-core](https://github.com/ufo-ai/ufo-core) | Business agent operating system | 83 | 41.5 | 2026-09-29 |
| [qiz029/dscode](https://github.com/qiz029/dscode) | A DeepSeek coding agent harness: persistent shell, Ultra subagents, auto approva | 861 | 47.8 | 2026-09-29 |
| [nokia-applied-research/AnyJev](https://github.com/nokia-applied-research/AnyJev) | Turn any LLM into a Jev-style decision model: typed decisions, real probabilitie | 919 | 114.9 | 2026-09-29 |
| [jamespolyakov9829/captcha-api](https://github.com/jamespolyakov9829/captcha-api) | Captcha-solving API client - Cloudflare Challenge and Turnstile in one interface | 264 | 88.0 | 2026-09-29 |
| [matank001/clodfarm](https://github.com/matank001/clodfarm) | clodfarm (say it out loud): a farm of Claude Code agents. Plant a mission, they  | 80 | 20.0 | 2026-09-29 |
| [TypeLLM/TypeLLM](https://github.com/TypeLLM/TypeLLM) | TypeLLM: LLMs with type-safe generation | 244 | 34.9 | 2026-09-25 |
| [yetone/magpie](https://github.com/yetone/magpie) | Every agent's model. One place. Codex on DeepSeek, Claude Code on Kimi, from the | 741 | 741.0 | 2026-09-25 |
| [TokenRhythm/NeoHorse](https://github.com/TokenRhythm/NeoHorse) | NeoHorse-1: Towards Recursive Self-Improvement via Agentic Post-Training with Ro | 981 | 46.7 | 2026-09-25 |
| [kishormorol/cli-faq-shortcuts](https://github.com/kishormorol/cli-faq-shortcuts) | An Agent Skill that turns the asks you keep typing into short commands, mined fr | 104 | 17.3 | 2026-09-25 |
| [yukitorido/short-video-generator-AI](https://github.com/yukitorido/short-video-generator-AI) | AI video processing pipeline for generating vertical shorts using LLMs, Whisper  | 348 | 348.0 | 2026-09-25 |

## Nasıl katkı verirsin

Bildiğin ücretsiz bir servis eksikse issue aç, şu üç bilgiyi yaz: servisin adresi, ne verdiği, kredi kartı isteyip istemediği. Test adresini de yazarsan bir sonraki güncellemede otomatik test edilir.

Listeden düşmesi gereken bir kayıt görürsen de issue aç. Zaten her güncellemede test ediliyor ama gözden kaçabilir.

## Değişiklik günlüğü

- **2026-10-20** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-10-16** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-10-13** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-10-09** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-10-06** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-10-02** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-09-29** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-09-25** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-09-22** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-09-18** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-09-15** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-09-11** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor

---

Bu liste bir otomasyon tarafından üretiliyor. Kaynaklar: PyPI akışları, GitHub arama API'si ve canlı servis testleri. Hiçbir kayıt elle uydurulmuyor.