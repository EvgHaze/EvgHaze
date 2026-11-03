### Hi there, I'm EvgHaze 👋

I build Telegram bots, search and data pipelines, customer-facing assistants, and native ports of console games.

Python, TypeScript, C++.

---

### 🚀 Projects I'm Building & Maintaining

#### 🤖 Telegram bots & automation

- **RugRadar** — scam check for tokens from open data: free verdict in about 30 seconds, paid report, chat bot, landing page. *(private)*
- **Desk Bot** — one bot instead of ten tabs: finds orders, drafts replies, keeps the lead pipeline. *(private)*
- **kwsearch** — search across Telegram channels and the web: Python server, SQLite FTS5 catalogue, daily collector. *(private)*
- **daily-digest** — runs at login and folds the overnight RSS feeds into one digest. *(private)*
- **Order Radar / Chat Monitor / Price Monitor** — monitors over chats and prices: new orders, leads and price moves, reported when they happen. *(private)*
- **gh-radar** — new console-game recompilations from the GitHub Search API and Reddit feeds, scored and delivered as a digest. *(private)*

#### 📊 Polymarket desk

- **Desk** — read-only web desk over the public Polymarket APIs: resolution rules, fair probability, edge after fees and spread, term curve, order book microstructure, red-team pass, paper journal. React and Hono on Cloudflare Workers, Russian interface. *(not on GitHub yet)*
- **polyx** — the same valuation gates as a Telegram scanner for geopolitical markets: up to three signals per scan, explicit EV math, quarter-Kelly sizing capped at 10 % of bankroll, execution stays manual. *(private)*
- **polytracker** — Telegram alerts on buys and sells of chosen wallets, from the public Data API. *(private)*

#### 🧩 Assistants for clients

- **Document assistant** — answers staff and customer questions from the price lists, regulations and internal policy a business already has. It asks to clarify when it did not understand, passes a question to a person when nothing in those pages covers it, and counts how much was resolved alone. FastAPI, Russian and Spanish. *(private)*
- **Booking bot** — appointment bot for a salon or a self-employed master: services, working days and hours set with buttons, no commands; the client books in three clicks from a personal link, with no public catalogue. Week grid, day off in one tap, schedule templates. *(private)*

#### 🎮 Reverse engineering & game ports

- **[GTA: Vice City Stories — native macOS arm64 port](https://github.com/gothamor/gta-vcs-recomp/pull/30)** — Apple clang + ThinLTO, MoltenVK backend, profiler, PGO. +923 / −82, upstream pull request open.
- **[gta-vcs-recomp](https://github.com/EvgHaze/gta-vcs-recomp)** — my fork; the `macos-arm64` branch holds it.
- **Need for Speed: SHIFT recompiler** — Xenon PPC with VMX128 translated to C++ and built for arm64 using [XenonRecomp](https://github.com/hedge-dev/XenonRecomp), a ported GPL runtime and a differential harness that checks each translated function against the original instruction stream. *(private)*

Most of the list is private: work done for a business stays off GitHub, and a game image cannot be redistributed with the code. What clears both rules lands here.

---

### 🔗 Links

- **GitHub:** [github.com/EvgHaze](https://github.com/EvgHaze)

---

### 🤝 How I work

- Nothing spends money or trades on its own. No exchange keys in the code: the tool shows the math, the position and the cap, a person presses the button.
- Game files and client documents never end up in a repository. A port asks for your own disc, an assistant answers only from the pages it was given and passes on what those pages do not cover.
- The numbers written here are measured, not estimated: +923 / −82 is the diff of the open pull request, and the assistant's ten control questions were actually run, five of them in Spanish.
- A project that stops paying for its upkeep gets frozen with a written reason instead of being left half-alive.
