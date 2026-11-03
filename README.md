### Hi there, I'm EvgHaze 👋

I build automation that runs unattended: Telegram bots and watchers, search and data pipelines, assistants over a client's own documents, and native ports of console games.

Python and TypeScript most days, C++ when code has to run on the machine it ships to.

---

### 🚀 Projects I'm Building & Maintaining

#### 🤖 Telegram bots & automation

- **RugRadar** — scam check for tokens from open data: free verdict in about 30 seconds, paid report, chat bot, landing page. *(private)*
- **Desk Bot** — one bot instead of ten tabs: finds orders, drafts replies, keeps the lead pipeline. *(private)*
- **kwsearch** — search across Telegram channels and the web: Python server, SQLite FTS5 catalogue, daily collector. *(private)*
- **daily-digest** — runs at login and collects the overnight RSS feeds into one digest. *(private)*
- **Order Radar / Chat Monitor / Price Monitor** — watchers over Telegram chats and prices: new orders, leads and price moves, reported when they happen. *(private)*
- **gh-radar** — new console-game recompilations from the GitHub Search API and Reddit feeds, scored and delivered as a Telegram digest. *(private)*

#### 📊 Data & prediction markets

- **Polymarket Desk** — analysis desk for prediction markets: resolution rules, fair probability, edge after fees and spread, term curve, order book microstructure, red-team pass, paper journal. *(private)*

#### 🧩 Assistants for clients

- **Document assistant** — answers questions from the client's own documents: price lists, regulations, internal policy. Asks for clarification when it does not understand and hands the question to a person when the documents do not cover it. FastAPI service, Russian and Spanish, with a count of how much it resolved on its own. *(private)*
- **Booking bot** — appointment bot for a salon or a self-employed master: services, working days and hours set with buttons, no commands; the client books in three clicks from a personal link, with no public catalogue. Week grid, day-off in one tap, schedule templates. *(private)*

#### 🎮 Reverse engineering & native ports

- **[GTA: Vice City Stories — native macOS arm64 port](https://github.com/gothamor/gta-vcs-recomp/pull/30)** — Apple clang + ThinLTO, MoltenVK backend, profiler, PGO. +923 / −82, upstream pull request open.
- **[gta-vcs-recomp](https://github.com/EvgHaze/gta-vcs-recomp)** — my fork; the `macos-arm64` branch holds the port.
- **Need for Speed: SHIFT recompiler** — Xenon PPC with VMX128 translated to C++ and built for arm64 using [XenonRecomp](https://github.com/hedge-dev/XenonRecomp), a ported GPL runtime and a differential harness that checks each translated function against the original instruction stream. *(private)*

Most of the list is private for now: client code stays with the client, and a game port cannot ship game files. Public code lands here as it clears that.

---

### 🔗 Links

- **GitHub:** [github.com/EvgHaze](https://github.com/EvgHaze)

---

### 🤝 How I work

Everything here is built to run without me: it writes a log, sends one message when something changed, stays quiet otherwise.

When an assistant cannot find the answer in the documents, it says so and passes the question to a person.
