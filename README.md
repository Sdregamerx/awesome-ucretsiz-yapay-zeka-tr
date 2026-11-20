# Ücretsiz Yapay Zeka API'leri, Python Kütüphaneleri ve Otomasyon Araçları

![son güncelleme](https://img.shields.io/badge/son%20g%C3%BCncelleme-2026-11-20-brightgreen) ![test edilen api](https://img.shields.io/badge/çal%C4%B1%C5%9Fan%20API-8%2F8-blue)

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
| [Groq](https://api.groq.com) | LLM ve Whisper konuşma tanıma | hayır | ✅ çalışıyor | 2026-11-20 |
| [Openverse](https://openverse.org) | telifsiz görsel arama | hayır | ✅ çalışıyor | 2026-11-20 |
| [Pollinations](https://pollinations.ai) | metinden görsel üretme | hayır | ✅ çalışıyor | 2026-11-20 |
| [PyPI JSON](https://pypi.org) | paket bilgisi | hayır | ✅ çalışıyor | 2026-11-20 |
| [Wikimedia REST](https://wikimedia.org) | ansiklopedi ve görsel | hayır | ✅ çalışıyor | 2026-11-20 |
| [Frankfurter](https://frankfurter.dev) | döviz kuru | hayır | ✅ çalışıyor | 2026-11-20 |
| [Open-Meteo](https://open-meteo.com) | hava durumu | hayır | ✅ çalışıyor | 2026-11-20 |
| [CoinGecko](https://coingecko.com) | kripto fiyat | hayır | ✅ çalışıyor | 2026-11-20 |

## Yeni Python kütüphaneleri

PyPI'da yeni yayınlanan, puanlamayı geçen paketler. Puan; sürüm sayısı, kaynak kod deposunun varlığı, lisans ve açıklama kalitesinden hesaplanır.

| Paket | Sürüm | Ne işe yarar | Puan | Eklendi |
|---|---|---|---|---|
| [ragpick](https://pypi.org/project/ragpick/) | 0.5.0 | Choose, build, evaluate, and run the right RAG architecture — architecture as code. | 90 | 2026-11-20 |
| [pyjuiz](https://pypi.org/project/pyjuiz/) | 0.3.0 | Python binding interface for JUIZ robot middleware components | 95 | 2026-11-20 |
| [juiz-cli](https://pypi.org/project/juiz-cli/) | 0.3.0 | JUIZ robot middleware: the juiz command for Python users (no Rust toolchain needed) | 95 | 2026-11-20 |
| [drawlib](https://pypi.org/project/drawlib/) | 0.3.15 | Pure-Python library for Illustration, Diagrams, Documentation, and Slides as Code (HTML/PD | 95 | 2026-11-20 |
| [django-queryable-properties](https://pypi.org/project/django-queryable-properties/) | 1.14.0 | Write Django model properties that can be used in database queries. | 95 | 2026-11-20 |
| [raja-mcp](https://pypi.org/project/raja-mcp/) | 0.1.1 | Unofficial read-only MCP server for Raja (raja.ir), the Iranian train ticket seller: stati | 75 | 2026-11-17 |
| [iran-roads-mcp](https://pypi.org/project/iran-roads-mcp/) | 0.1.1 | Unofficial read-only MCP server for Iran road status (141.ir, Road Maintenance and Transpo | 75 | 2026-11-17 |
| [kaizo-hf](https://pypi.org/project/kaizo-hf/) | 0.2.4 | Hugging Face plugin for kaizo | 85 | 2026-11-17 |
| [homematicip](https://pypi.org/project/homematicip/) | 2.23.1 | An API for the homematicip cloud | 90 | 2026-11-17 |
| [qcdata](https://pypi.org/project/qcdata/) | 0.23.1 | Beautiful and user friendly data structures for quantum chemistry. | 95 | 2026-11-17 |
| [dataiku-scoring](https://pypi.org/project/dataiku-scoring/) | 15.2.1 | Dataiku ML Scoring Python library | 75 | 2026-11-13 |
| [openrouter](https://pypi.org/project/openrouter/) | 1.3.175 | Official Python Client SDK for OpenRouter. | 90 | 2026-11-13 |
| [scrapely-python](https://pypi.org/project/scrapely-python/) | 0.1.48 | Scrapely Python SDK - A toolkit for building Actors on the Scrapely platform | 90 | 2026-11-13 |
| [llm-council-core](https://pypi.org/project/llm-council-core/) | 0.53.1 | Multi-LLM council system with peer review and synthesis | 90 | 2026-11-13 |
| [setuptools-git-versioning](https://pypi.org/project/setuptools-git-versioning/) | 3.2.2 | Use git repo data for building a version number according to PEP-440 | 95 | 2026-11-13 |
| [interloper-api](https://pypi.org/project/interloper-api/) | 0.129.0 | Interloper FastAPI routes | 70 | 2026-11-10 |
| [windmill-api](https://pypi.org/project/windmill-api/) | 1.865.0 | A client library for accessing Windmill API | 75 | 2026-11-10 |
| [idtrackerai-CYSM](https://pypi.org/project/idtrackerai-CYSM/) | 6.0.15a0.post2 | A fork of idtracker.ai that accepts animal outlines from an external instance-segmentation | 75 | 2026-11-10 |
| [conclave-team](https://pypi.org/project/conclave-team/) | 0.1.1 | A managed agent team: one Dean orchestrates many Cardinals on any model, Devils argue back | 75 | 2026-11-10 |
| [wmill](https://pypi.org/project/wmill/) | 1.865.0 | A client library for accessing Windmill server wrapping the Windmill client API | 80 | 2026-11-10 |
| [ibm-watsonx-data-intelligence-mcp-server](https://pypi.org/project/ibm-watsonx-data-intelligence-mcp-server/) | 1.7.0 | MCP Server implementation for IBM Data Intelligence | 85 | 2026-11-06 |
| [dex-python-sdk](https://pypi.org/project/dex-python-sdk/) | 1.35.0 | Python SDK for the Dex workflow engine | 85 | 2026-11-06 |
| [pyedautils](https://pypi.org/project/pyedautils/) | 0.0.33 | Python Energy Data Analysis Utilities | 90 | 2026-11-06 |
| [zernio-sdk](https://pypi.org/project/zernio-sdk/) | 1.4.1581 | The official Python library for the Zernio API | 90 | 2026-11-06 |
| [late-sdk](https://pypi.org/project/late-sdk/) | 1.4.1581 | The official Python library for the Zernio API | 90 | 2026-11-06 |
| [copernicus-ems](https://pypi.org/project/copernicus-ems/) | 0.2.0 | Client for Copernicus EMS Rapid Mapping: activations, observation masks, observed flood ex | 75 | 2026-11-03 |
| [dirigent-contrib](https://pypi.org/project/dirigent-contrib/) | 0.32.0 | Block packs for dirigent that reach outside systems: Chap and the open climate service. | 90 | 2026-11-03 |
| [sma-autoui](https://pypi.org/project/sma-autoui/) | 1.0.4 | Smart Mobile Automation UI Framework | 90 | 2026-11-03 |
| [tdd-cli](https://pypi.org/project/tdd-cli/) | 0.18.0 | Ledger-backed TDD process controller for autonomous coding agents | 90 | 2026-11-03 |
| [tracktales](https://pypi.org/project/tracktales/) | 2026.11.1 | TrackTales: Parse, analyze, and visualize your Apple Health workout data with an interacti | 95 | 2026-11-03 |
| [django-looseleaf](https://pypi.org/project/django-looseleaf/) | 2.4.0 | LooseLeaf UI for Django: the CUBE CSS design system's stylesheet and scripts, template tag | 70 | 2026-10-30 |
| [maibot-dashboard](https://pypi.org/project/maibot-dashboard/) | 1.9.12 | MaiBot WebUI static assets | 70 | 2026-10-30 |
| [biztory-tableau-knowledge-mcp](https://pypi.org/project/biztory-tableau-knowledge-mcp/) | 0.2.0 | Search, explore and enrich the Tableau Knowledge graph from any MCP client, and port it to | 75 | 2026-10-30 |
| [facebook-gql-scraper](https://pypi.org/project/facebook-gql-scraper/) | 0.8.1 | Scrape Facebook GraphQL data without an API key — profiles, posts, comments, reactions, gr | 75 | 2026-10-30 |
| [evalkit-py](https://pypi.org/project/evalkit-py/) | 0.3.0 | Self-hosted system for improving AI agents: server, CLI, web UI, Python SDK and agent skil | 75 | 2026-10-30 |
| [cairn-operator-eval-lm](https://pypi.org/project/cairn-operator-eval-lm/) | 0.2.0 | eval/lm-eval: EleutherAI lm-evaluation-harness against a served candidate, and the eval.lm | 75 | 2026-10-27 |
| [mite](https://pypi.org/project/mite/) | 2.12.0 | A Python Performance Testing Framework | 85 | 2026-10-27 |
| [licentivo-sdk](https://pypi.org/project/licentivo-sdk/) | 0.11.5 | Licentivo software licensing client | 90 | 2026-10-27 |
| [apmw](https://pypi.org/project/apmw/) | 1.1.4 | Cross-platform wrapper for the apm CLI — places OpenCode plugins after install and update | 90 | 2026-10-27 |
| [nexor-agora](https://pypi.org/project/nexor-agora/) | 0.21.2 | Shared LAN chat where humans and their Claude Code agents collaborate | 95 | 2026-10-27 |

## Açık kaynak otomasyon araçları

Son 30 günde açılmış, yıldız hızı yüksek depolar. Yıldız hızı günlük kazanılan yıldız demektir, tek seferlik zirveleri değil süregelen ilgiyi ölçer.

| Depo | Ne işe yarar | Yıldız | Yıldız/gün | Eklendi |
|---|---|---|---|---|
| [osarhiemenaiyevbosa-cloud/ai-manus](https://github.com/osarhiemenaiyevbosa-cloud/ai-manus) | AI Manus is a general-purpose AI Agent system that supports running various tool | 152 | 11.7 | 2026-11-20 |
| [Gigachad-byte/ai-manus](https://github.com/Gigachad-byte/ai-manus) | AI Manus is a general-purpose AI Agent system that supports running various tool | 152 | 11.7 | 2026-11-20 |
| [willsmanuel123-creator/ai-manus](https://github.com/willsmanuel123-creator/ai-manus) | AI Manus is a general-purpose AI Agent system that supports running various tool | 152 | 11.7 | 2026-11-20 |
| [thecoderrrer/ai-manus](https://github.com/thecoderrrer/ai-manus) | AI Manus is a general-purpose AI Agent system that supports running various tool | 152 | 11.7 | 2026-11-20 |
| [google-deepmind/robotics-antigravity-plugin](https://github.com/google-deepmind/robotics-antigravity-plugin) | GDM Robotics Skills for agentic robotics workflows across simulation and real ro | 158 | 52.7 | 2026-11-20 |
| [monirchemrubd/ai-manus](https://github.com/monirchemrubd/ai-manus) | AI Manus is a general-purpose AI Agent system that supports running various tool | 152 | 15.2 | 2026-11-17 |
| [Abdoandqsnk/ai-manus](https://github.com/Abdoandqsnk/ai-manus) | AI Manus is a general-purpose AI Agent system that supports running various tool | 152 | 15.2 | 2026-11-17 |
| [Kolg123/ai-manus](https://github.com/Kolg123/ai-manus) | AI Manus is a general-purpose AI Agent system that supports running various tool | 152 | 15.2 | 2026-11-17 |
| [quyetcao/ai-manus](https://github.com/quyetcao/ai-manus) | AI Manus is a general-purpose AI Agent system that supports running various tool | 154 | 15.4 | 2026-11-17 |
| [Abdul-Rehman7826/ai-manus](https://github.com/Abdul-Rehman7826/ai-manus) | AI Manus is a general-purpose AI Agent system that supports running various tool | 156 | 15.6 | 2026-11-17 |
| [SAOS-3624/dsh-see-now](https://github.com/SAOS-3624/dsh-see-now) | 让 AI 实时看见你的屏幕：按变化量筛选帧、多帧拼进一张图，静止画面几乎不花 token | 616 | 56.0 | 2026-11-13 |
| [8hjkkwikl8/ai-portfolio](https://github.com/8hjkkwikl8/ai-portfolio) | 三个可运行的 AI 工程项目：可追溯 RAG、提示词评测与受守护的 NL2SQL 分析 | 100 | 50.0 | 2026-11-13 |
| [agentes-chat/agentes-chat](https://github.com/agentes-chat/agentes-chat) | Open-source, self-hosted Slack alternative where your team and AI agents work to | 1255 | 313.8 | 2026-11-13 |
| [RunanywhereAI/trnrt](https://github.com/RunanywhereAI/trnrt) | The open LLM inference engine for AWS Trainium: NKI megakernels, 1M-token contex | 1574 | 121.1 | 2026-11-13 |
| [professorsolderin/project-lighthouse](https://github.com/professorsolderin/project-lighthouse) | Project Lighthouse — shining AI on the pages history never read: transcriptions, | 81 | 27.0 | 2026-11-13 |
| [AbhramJohn/instagram-engagement-bot](https://github.com/AbhramJohn/instagram-engagement-bot) | Community-driven Instagram Liker Bot with advanced automation for desktop | 482 | 160.7 | 2026-11-10 |
| [JosssphZhou/poki](https://github.com/JosssphZhou/poki) | Let AI agents operate a real iPhone. Local MCP server and agent, no jailbreak, n | 847 | 211.8 | 2026-11-10 |
| [cutetailbud/ff-ruyijs](https://github.com/cutetailbud/ff-ruyijs) | This is a lightweight, headless browser purpose-built for AI agents (such as Cod | 1201 | 100.1 | 2026-11-10 |
| [KKKKhazix/agent-autoloop](https://github.com/KKKKhazix/agent-autoloop) | 让你的命令行 Agent 在后台自己接活、自己跟进到底；平时不烦你，遇到拿不准的事才发卡片找你拍板。 | 4375 | 625.0 | 2026-11-10 |
| [TIGER-AI-Lab/WebsiteBench](https://github.com/TIGER-AI-Lab/WebsiteBench) | Can AI agents rebuild websites through browser exploration? | 181 | 36.2 | 2026-11-10 |
| [sahenjp/RustXNG](https://github.com/sahenjp/RustXNG) | Self-hosted metasearch and grounding engine for AI agents, based on SearXNG. Rus | 861 | 45.3 | 2026-11-06 |
| [heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit](https://github.com/heqiangdiao-wq/AI-Cross-Border-Ecommerce-Agent-Toolkit) | AI 跨境电商运营智能体工具箱 · 把运营 SOP 拆成 7 个可复用的 AI Agent 工作流，含 Prompt、模板与真实案例 | 990 | 43.0 | 2026-11-06 |
| [N1nEmAn/sapper-v2](https://github.com/N1nEmAn/sapper-v2) | Autonomous pentest legion — AI commander + worker swarm + layered fact-intent gr | 1411 | 235.2 | 2026-11-06 |
| [dragonwolfshovel/youtube-uploader](https://github.com/dragonwolfshovel/youtube-uploader) | Automated YouTube video uploader with batch processing, thumbnail support, and s | 426 | 426.0 | 2026-11-06 |
| [HerdBuilderEstimate/roblox-studio-mcp](https://github.com/HerdBuilderEstimate/roblox-studio-mcp) | Model Context Protocol server for Roblox Studio. Connect AI assistants (Claude,  | 427 | 427.0 | 2026-11-06 |
| [wangzan101/Mika](https://github.com/wangzan101/Mika) | An on-device AI agent for Android that operates apps and the web to get things d | 5802 | 1450.5 | 2026-11-03 |
| [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) | Experience-Driven Black-Box Cost Control for Coding Agents | 4582 | 218.2 | 2026-11-03 |
| [outcrawlai/scout](https://github.com/outcrawlai/scout) | Scout: the open-source browser agent, by Outcrawl. Mirrored automatically from O | 949 | 45.2 | 2026-11-03 |
| [modelflare-ai/AnyModelBot](https://github.com/modelflare-ai/AnyModelBot) | 🤖 Open-source, local-first alternative to Grok Bot, OpenAI dots and Claude Duet. | 2019 | 288.4 | 2026-11-03 |
| [gh9ko8y/graphmemory](https://github.com/gh9ko8y/graphmemory) | Bitemporal AI memory system: six-variable decay, time-graded recall, TTL expiry, | 158 | 52.7 | 2026-11-03 |
| [teraus111/web3-agent-kit-solana-trading](https://github.com/teraus111/web3-agent-kit-solana-trading) | Build autonomous AI agents that interact with blockchains — in minutes, not mont | 141 | 8.8 | 2026-10-30 |
| [Syenzzz/mcd-coupon-strategist](https://github.com/Syenzzz/mcd-coupon-strategist) | 麦麦省钱助手 —— 基于麦当劳 MCP 的点餐成本优化 Skill。算出当前门店最省钱的点餐方案，并主动提示凑单陷阱。 | 994 | 52.3 | 2026-10-30 |
| [hanzohanzhe/Grandet](https://github.com/hanzohanzhe/Grandet) | Find the cheapest API for any model and connect it from your AI agent: Grandet S | 1011 | 40.4 | 2026-10-30 |
| [AienTech/dossier](https://github.com/AienTech/dossier) | A self-hosted job search app that writes tailored resumes and cover letters from | 3267 | 125.7 | 2026-10-30 |
| [RabbittuX/purrge](https://github.com/RabbittuX/purrge) | 🐾 Purrge — macOS AI 磁盘清理工具，支持 Claude Code 和 Codex：空间不足时提醒，AI 逐项判断能清什么，你勾选确认后才清理 | 109 | 12.1 | 2026-10-30 |
| [AbuZar-Ansarii/Ultron](https://github.com/AbuZar-Ansarii/Ultron) | Autonomous desktop intelligence with MCU Ultron persona, mood-aware workspace or | 130 | 16.2 | 2026-10-27 |
| [developeryj1992/ai-trend-studio](https://github.com/developeryj1992/ai-trend-studio) | Local-first AI trend radar and live-session distillation | 240 | 15.0 | 2026-10-27 |
| [Rocky-true/vmware-to-kubernetes](https://github.com/Rocky-true/vmware-to-kubernetes) | Kubernetes 自动化运维与迁移工具：阿里云 3 主 HA、Compose→K8s、Terraform、Kubekey、部署验证与故障排查。Kuberne | 115 | 14.4 | 2026-10-27 |
| [huaxialucaicaizi/ai-startup-skills](https://github.com/huaxialucaicaizi/ai-startup-skills) | 创业公司做 AI 产品的 7 步 Agent Skill 合集：验证 → BP → 政策 → 路演 → 获客 → 定价 → 注册。 | 366 | 91.5 | 2026-10-27 |
| [hevnsnt/CVEngine](https://github.com/hevnsnt/CVEngine) | AI-first external attack surface assessment with continuous discovery, evidence- | 399 | 199.5 | 2026-10-27 |

## Nasıl katkı verirsin

Bildiğin ücretsiz bir servis eksikse issue aç, şu üç bilgiyi yaz: servisin adresi, ne verdiği, kredi kartı isteyip istemediği. Test adresini de yazarsan bir sonraki güncellemede otomatik test edilir.

Listeden düşmesi gereken bir kayıt görürsen de issue aç. Zaten her güncellemede test ediliyor ama gözden kaçabilir.

## Değişiklik günlüğü

- **2026-11-20** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-11-17** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-11-13** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-11-10** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-11-06** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-11-03** — 5 kütüphane, 5 araç eklendi; 7/8 API çalışıyor
- **2026-10-30** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-10-27** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-10-23** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-10-20** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-10-16** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-10-13** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor

---

Bu liste bir otomasyon tarafından üretiliyor. Kaynaklar: PyPI akışları, GitHub arama API'si ve canlı servis testleri. Hiçbir kayıt elle uydurulmuyor.