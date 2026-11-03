### Hi there, I'm EvgHaze 👋

I build things that keep working after I close the laptop: Telegram bots and watchers, search and data pipelines, customer-facing AI assistants, and the occasional native port of a console game.

Python and TypeScript most days, C++ when code has to run on the machine it ships to.

---

### 🚀 Projects I'm Building & Maintaining

#### 🤖 Telegram bots & automation

- **RugRadar** — answers "is this token buyable at all" in about half a minute from open data: free check, paid report, group bot, landing page. *(private)*
- **Desk Bot** — one bot instead of ten tabs: finds orders, drafts the reply, keeps the lead pipeline moving. *(private)*
- **kwsearch** — search across Telegram channels and the web: Python server, SQLite FTS5 catalogue, a collector that runs every morning. *(private)*
- **daily-digest** — a single message at login with everything the RSS feeds picked up overnight. *(private)*
- **Order Radar / Chat Monitor / Price Monitor** — watchers over chats and prices that ping only when something actually moved. *(private)*
- **gh-radar** — follows new console-game recompilations across the GitHub Search API and Reddit feeds, scores them, delivers a Telegram digest. *(private)*

#### 📊 Data & prediction markets

- **Polymarket Desk** — analysis desk for prediction markets: resolution rules, fair probability, edge after fees and spread, term curve, book microstructure, a red-team pass and a paper journal. *(private)*

#### 🧩 Assistants and tools for clients

- **Knowledge-base assistant** — answers customers strictly from the client's own documents: price lists, regulations, FAQ. When the answer is not in the base it says so instead of inventing one. *(private)*
- **HR assistant** — the same idea aimed inward, a FastAPI service answering staff questions over internal docs. *(private)*
- **Booking bot** — Telegram intake for a small business: records, reminders, no phone calls. *(private)*
- **Product cards for Wildberries and Ozon** — marketplace listing generation. *(private)*

#### 🎮 Reverse engineering & native ports

- **[GTA: Vice City Stories — native macOS arm64 port](https://github.com/gothamor/gta-vcs-recomp/pull/30)** — Apple clang + ThinLTO, MoltenVK backend, profiler and PGO. Open upstream pull request, +923 / −82.
- **[gta-vcs-recomp](https://github.com/EvgHaze/gta-vcs-recomp)** — my fork of the [upstream project](https://github.com/gothamor/gta-vcs-recomp); the `macos-arm64` branch is where the port lives.
- **Need for Speed: SHIFT recompiler** — Xenon PPC with VMX128 translated to C++ and built for arm64 on top of [XenonRecomp](https://github.com/hedge-dev/XenonRecomp), with a ported GPL runtime and a differential harness that checks each translated function against the original instruction stream. *(private)*

---

### 🔗 Links & Resources

- **GitHub:** [github.com/EvgHaze](https://github.com/EvgHaze)
- **Vice City Stories recompiler (upstream):** [gothamor/gta-vcs-recomp](https://github.com/gothamor/gta-vcs-recomp)
- **Xbox 360 recompilation tooling:** [hedge-dev/XenonRecomp](https://github.com/hedge-dev/XenonRecomp)
- **Need for Speed native ports (PC, Mac, Steam Deck):** [SpeedBreakerProject/speedbreaker](https://github.com/SpeedBreakerProject/speedbreaker)
- **Index of existing recompilations:** [BlueInterlude/awesome-recompilations](https://github.com/BlueInterlude/awesome-recompilations)

Most of the work above sits in private repositories: client projects keep their code with the client, and the game ports cannot ship game files. Public code lands here as soon as it can.

---

### 🤝 How I work

A tool that needs me standing behind it is not finished yet, so most of what I build is meant to run unattended and report only when it has something to say. I would rather ship one narrow tool that people keep using than a dashboard nobody opens.

Answers from a model have to be traceable to a document, a price list or a disassembly — anything else is a guess wearing a confident voice.
