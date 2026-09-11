# Ücretsiz Yapay Zeka API'leri, Python Kütüphaneleri ve Otomasyon Araçları

![son güncelleme](https://img.shields.io/badge/son%20g%C3%BCncelleme-2026-09-11-brightgreen) ![test edilen api](https://img.shields.io/badge/çal%C4%B1%C5%9Fan%20API-8%2F8-blue)

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
| [Groq](https://api.groq.com) | LLM ve Whisper konuşma tanıma | hayır | ✅ çalışıyor | 2026-09-11 |
| [Openverse](https://openverse.org) | telifsiz görsel arama | hayır | ✅ çalışıyor | 2026-09-11 |
| [Pollinations](https://pollinations.ai) | metinden görsel üretme | hayır | ✅ çalışıyor | 2026-09-11 |
| [PyPI JSON](https://pypi.org) | paket bilgisi | hayır | ✅ çalışıyor | 2026-09-11 |
| [Wikimedia REST](https://wikimedia.org) | ansiklopedi ve görsel | hayır | ✅ çalışıyor | 2026-09-11 |
| [Frankfurter](https://frankfurter.dev) | döviz kuru | hayır | ✅ çalışıyor | 2026-09-11 |
| [Open-Meteo](https://open-meteo.com) | hava durumu | hayır | ✅ çalışıyor | 2026-09-11 |
| [CoinGecko](https://coingecko.com) | kripto fiyat | hayır | ✅ çalışıyor | 2026-09-11 |

## Yeni Python kütüphaneleri

PyPI'da yeni yayınlanan, puanlamayı geçen paketler. Puan; sürüm sayısı, kaynak kod deposunun varlığı, lisans ve açıklama kalitesinden hesaplanır.

| Paket | Sürüm | Ne işe yarar | Puan | Eklendi |
|---|---|---|---|---|
| [chinese-char-counter-mcp](https://pypi.org/project/chinese-char-counter-mcp/) | 0.1.1 | MCP server (stdio) that counts Chinese characters in a text, excluding punctuation, whites | 80 | 2026-09-11 |
| [sema-core](https://pypi.org/project/sema-core/) | 2.1.0 | Python SDK for sema-core: thin client over the sema-grpc bridge | 90 | 2026-09-11 |
| [pykokoro](https://pypi.org/project/pykokoro/) | 0.9.4 | A python library for Kokoro TTS | 90 | 2026-09-11 |
| [protolib](https://pypi.org/project/protolib/) | 0.4.4 | Pure-Python, from-scratch declarative binary protocol (de)serializer — node-protodef style | 95 | 2026-09-11 |
| [prompt-flamegraph](https://pypi.org/project/prompt-flamegraph/) | 0.3.0 | Lightweight, dependency-free prompt context flamegraph generator for LLMs | 95 | 2026-09-11 |
| [hasdata-yelp-mcp](https://pypi.org/project/hasdata-yelp-mcp/) | 1.0.0 | MCP server for Yelp through HasData's hosted API. 1,000 free credits every month. | 65 | 2026-09-09 |
| [VeraGridMcp](https://pypi.org/project/VeraGridMcp/) | 6.5.24 | VeraGrid is a Power Systems simulation program intended for professional use and research | 65 | 2026-09-09 |
| [netops-api-navigator](https://pypi.org/project/netops-api-navigator/) | 0.3.0 | Independent MCP server for graph-backed network API discovery and automation | 65 | 2026-09-09 |
| [gooddata-dbt](https://pypi.org/project/gooddata-dbt/) | 1.74.0 | dbt plugin for GoodData | 70 | 2026-09-09 |
| [csp-tarayici](https://pypi.org/project/csp-tarayici/) | 0.4.0 | Cash-secured put scanner using CBOE options data with a curses TUI, no API keys required | 90 | 2026-09-09 |
| [catan-toolbox](https://pypi.org/project/catan-toolbox/) | 0.1.6 | Interactive and algorithmic tools for matching and curating neurons across calcium imaging | 70 | 2026-09-09 |
| [lightlogger](https://pypi.org/project/lightlogger/) | 0.1.1 | Live web dashboard for your Python logs — one line of code, zero dependencies | 75 | 2026-09-09 |
| [taprivo](https://pypi.org/project/taprivo/) | 0.1.0b5 | Turn finger taps into a playful Motion Energy budget for AI coding agents. | 75 | 2026-09-09 |
| [agent-augury](https://pypi.org/project/agent-augury/) | 0.4.0 | Model-agnostic passive awareness multi-agent runtime — concept inherited from AgentRadio ( | 80 | 2026-09-09 |
| [instana-client](https://pypi.org/project/instana-client/) | 1.1.2 | Instana REST API documentation | 85 | 2026-09-09 |

## Açık kaynak otomasyon araçları

Son 30 günde açılmış, yıldız hızı yüksek depolar. Yıldız hızı günlük kazanılan yıldız demektir, tek seferlik zirveleri değil süregelen ilgiyi ölçer.

| Depo | Ne işe yarar | Yıldız | Yıldız/gün | Eklendi |
|---|---|---|---|---|
| [datawhalechina/zero-to-sglang](https://github.com/datawhalechina/zero-to-sglang) | Official SGLang × Datawhale course on LLM inference (中英双语): understand inference | 732 | 48.8 | 2026-09-11 |
| [tigerless-labs/agent-memory](https://github.com/tigerless-labs/agent-memory) | Long-term memory runtime for AI agents — plain Markdown as the source of truth,  | 963 | 107.0 | 2026-09-11 |
| [Player-YN/PawWork_ZhuaZhua](https://github.com/Player-YN/PawWork_ZhuaZhua) | Paw Work - selection-first web agent for Chrome: select on the live page, descri | 2546 | 195.8 | 2026-09-11 |
| [jzjzzzzzzz/agent-me](https://github.com/jzjzzzzzzz/agent-me) | Distill your knowledge, memories, and decisions into an open-source, inspectable | 184 | 12.3 | 2026-09-11 |
| [crwdla/tokentab](https://github.com/crwdla/tokentab) | A CLI that reads Claude Code, Codex, and Gemini CLI session logs and works out h | 318 | 106.0 | 2026-09-11 |
| [Nanako0129/sepia](https://github.com/Nanako0129/sepia) | De-AI writing skill for any Agent Skills-compatible agent (77+ via the Skills CL | 2486 | 207.2 | 2026-09-09 |
| [useagenthq/useagent](https://github.com/useagenthq/useagent) | The open-source AI coworker for your team: agents with their own cloud computer, | 284 | 28.4 | 2026-09-09 |
| [bam-bam-2/solo-skills](https://github.com/bam-bam-2/solo-skills) | 1인 사업가 생산성 키트 — 직원 없이 49개를 자동화했고, 그중 바로 쓸 수 있는 AI 에이전트 스킬 26개(+실행 스크립트)를 공개합니다 | 362 | 21.3 | 2026-09-09 |
| [browser-use/macos-harness](https://github.com/browser-use/macos-harness) | The simplest, thinnest harness that gives an LLM complete freedom to control a M | 838 | 36.4 | 2026-09-09 |
| [totec448-spec/chat-on-steroids](https://github.com/totec448-spec/chat-on-steroids) | Cross-platform local MCP capabilities for ChatGPT with Chrome integration, Goal, | 1639 | 96.4 | 2026-09-09 |
| [bawadou/ai-data-extractor](https://github.com/bawadou/ai-data-extractor) | Free open-source extractor for AI coding assistant chat histories. Supports Clau | 555 | 24.1 | 2026-09-09 |
| [hkqr/my-free-code](https://github.com/hkqr/my-free-code) | Open-source multi-provider AI gateway for Claude Code and other coding agents, w | 632 | 52.7 | 2026-09-09 |
| [2akouwu/reverify](https://github.com/2akouwu/reverify) | Stop your AI from making things up — it proposes, deterministic tools decide, ev | 1058 | 117.6 | 2026-09-09 |
| [xzf-thu/VoiceMem](https://github.com/xzf-thu/VoiceMem) | Infrastructure for the next generation of voice agents, designed to provide univ | 1098 | 47.7 | 2026-09-09 |
| [guillaumemeyer/watermarks-remover](https://github.com/guillaumemeyer/watermarks-remover) | A privacy-first app that strips AI watermarks from content you own. | 21478 | 767.1 | 2026-09-09 |

## Nasıl katkı verirsin

Bildiğin ücretsiz bir servis eksikse issue aç, şu üç bilgiyi yaz: servisin adresi, ne verdiği, kredi kartı isteyip istemediği. Test adresini de yazarsan bir sonraki güncellemede otomatik test edilir.

Listeden düşmesi gereken bir kayıt görürsen de issue aç. Zaten her güncellemede test ediliyor ama gözden kaçabilir.

## Değişiklik günlüğü

- **2026-09-11** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-09-09** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor
- **2026-09-09** — 5 kütüphane, 5 araç eklendi; 8/8 API çalışıyor

---

Bu liste bir otomasyon tarafından üretiliyor. Kaynaklar: PyPI akışları, GitHub arama API'si ve canlı servis testleri. Hiçbir kayıt elle uydurulmuyor.