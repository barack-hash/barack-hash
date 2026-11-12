<h1 align="center">Yitbarek Tegene <sub>(Barack)</sub></h1>

<p align="center">
  <b>Co-Founder, Eiqora Technologies</b> &middot; AI-native product &amp; hardware builder<br>
  <a href="https://barack-hash.github.io/">Portfolio</a> &middot;
  <a href="https://eiqora.com">eiqora.com</a> &middot;
  <a href="https://github.com/barack-hash?tab=repositories">Repositories</a>
</p>

I build software for institutions that usually run on WhatsApp threads and spreadsheets —
mosques, schools, employment and travel agencies. My platforms are multi-tenant by design,
with tenant isolation enforced **inside Postgres** rather than in application code, and they
ship in the languages their users actually read, including Amharic and right-to-left Arabic.
Away from the web I build edge hardware.

## Co-founder: Eiqora Technologies

Bespoke, per-client software platforms for community institutions, handed over to the
client's own staff to run. I co-founded the company and architect and build the platform.

| | |
|---|---|
| **Live** | [eiqora.com](https://eiqora.com) &middot; [admin.eiqora.com](https://admin.eiqora.com) &middot; [bic.eiqora.com](https://bic.eiqora.com) (BIC Masjid Platform) |
| **Stack** | Next.js 16 &middot; React 19 &middot; TypeScript &middot; Supabase &middot; Postgres (schema-per-client isolation) &middot; Stripe &middot; Inngest &middot; Cloudflare R2 &middot; Tailwind v4 &middot; Vercel |
| **Source** | Private (company repository). Happy to walk through the architecture or arrange access for a technical screen. |

## Production platforms

| Platform | What it is | Links |
|---|---|---|
| **BIC Masjid Platform** | Live platform for the Bangladesh Islamic Center: member community app, madrasa learning-management system and imam console. | [bic.eiqora.com](https://bic.eiqora.com) |
| **Darul Amal** | Four-portal operations platform for an Ethiopian foreign-employment agency: staff, employer (Arabic RTL), worker and broker portals in four languages, with WhatsApp Business API and AI translation. | [darul-amal.com](https://www.darul-amal.com) |
| **Nejashi / Sakina** | Multi-tenant SaaS for mosques in Ethiopia: marketing site, operator console, imam console and Amharic-first member app in one Turborepo monorepo on Neon Postgres with row-level security. | [nejashi.vercel.app](https://nejashi.vercel.app) |
| **Dar Al Safar** | Public website and internal operations portal for a luxury travel and concierge agency: CRM, GDS-style ticketing, visa pipeline Kanban, ledger and payroll. | [darulsafar.com](https://www.darulsafar.com) &middot; [source](https://github.com/barack-hash/darul-safar-web) |

## Open source

| Project | What it is |
|---|---|
| [**multitenant-platform**](https://github.com/barack-hash/multitenant-platform) | Business-agnostic multi-tenant SaaS foundation as a modular monolith: tenant isolation enforced by Postgres row-level security, billing and entitlements, transactional outbox, hash-chained audit ledger, operator console. 224 automated checks in one command. |
| [**offline-survival-llm**](https://github.com/barack-hash/offline-survival-llm) | Fully offline survival-reference device on a Raspberry Pi 5: local LLM via llama.cpp with hybrid FAISS + BM25 retrieval over public-domain manuals, Arduino keypad input. Every build session, mistake and benchmark is logged. |
| [**flipperTrack**](https://github.com/barack-hash/flipperTrack) | Flipper Zero USB-HID activity simulator in C: settings-menu UI, four independent actions, per-action min/max randomized timing down to 50 ms, background worker thread. |
| [**desktop-agent**](https://github.com/barack-hash/desktop-agent) | Pip, a macOS desktop pet whose brain is Claude Code running headless; permission cards before any change, scheduled chores. |
| [**quran-hifz-trainer**](https://github.com/barack-hash/quran-hifz-trainer) | Offline-first PWA for Quran memorization with a custom spaced-repetition engine (sabaq / sabqi / manzil loops) and Madinah Mushaf page rendering. 255 automated tests. |
| [**Sovereign-architect**](https://github.com/barack-hash/Sovereign-architect) | Local-first deterministic life planner: critical-path scheduling, five-capital simulation, Pareto exploration and Monte Carlo risk trials. 104 unit tests. |
| [**telegram-channel-scraper**](https://github.com/barack-hash/telegram-channel-scraper) | Local tool with a web UI that archives public Telegram channel history to JSON/CSV incrementally via the official API. |

## How I work

I am transparent about it: my hand-written coding is Python basics. Every project here was
built by directing AI development tools — Claude Code and Cursor — through specifications,
phase plans and line-by-line reviews. My craft is writing precise specs, spotting and fixing
AI-generated defects, and testing until it is production-ready. The measured benchmarks,
build logs and regression suites across these projects are the proof.

**Measured results:** 224/224 automated checks passing in one command (multitenant-platform)
&middot; 255 test cases incl. one regression test per shipped bug (quran-hifz-trainer)
&middot; 34/34 retrieval hit@4 after adding hybrid BM25 search, 4.7 tok/s on-device at 69–70 °C
without throttling (offline-survival-llm) &middot; 4 shipped locales incl. Arabic RTL and Amharic
(Darul Amal) &middot; 6 live production apps, two with paying institutions.

<p align="center"><sub>
TypeScript &middot; React &middot; Next.js &middot; Node &middot; Fastify &middot; Python &middot; C &middot; PostgreSQL / RLS &middot; Supabase &middot; Neon &middot; Drizzle &middot; Stripe &middot; Playwright &middot; Vitest &middot; llama.cpp &middot; FAISS &middot; Raspberry Pi &middot; Arduino &middot; Electron
</sub></p>
