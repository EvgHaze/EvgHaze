### Hi there, I'm EvgHaze 👋

I turn console game binaries into native programs. Static recompilation: the original PS2 or Xbox 360 machine code is translated into C++ ahead of time, so the result runs at native speed on Windows, Linux and Apple Silicon — no interpreter loop, no emulator overhead.

I care about **keeping playable the games nobody is going to re-release, native performance, and open tooling**.

---

### 🚀 Projects I'm Building & Maintaining

#### 🎬 Console recompilation — public

- **[GTA: Vice City Stories — native macOS arm64 port](https://github.com/gothamor/gta-vcs-recomp/pull/30)** — Apple clang + ThinLTO, MoltenVK backend, profiler and PGO. Open upstream pull request, +923 / −82.
- **[gta-vcs-recomp](https://github.com/EvgHaze/gta-vcs-recomp)** — my fork of the [upstream project](https://github.com/gothamor/gta-vcs-recomp); the `macos-arm64` branch is where the port lives.

#### 🛠️ Xbox 360 (Xenon) — private for now

- **Need for Speed: SHIFT recompiler** — Xenon PPC with VMX128 translated to C++ and built for arm64 on top of [XenonRecomp](https://github.com/hedge-dev/XenonRecomp), with a ported GPL runtime: window and Vulkan/MoltenVK backend, jump-table handling, and a differential harness that checks each translated function against the original instruction stream.
- **gh-radar** — a Python watcher for new console-game recompilations: GitHub Search API plus Reddit feeds, scored, delivered as a Telegram digest.

Both stay private while the generated trees and the game-side tooling settle. Neither would ship game files.

---

### 🔗 Links & Resources

- **GitHub:** [github.com/EvgHaze](https://github.com/EvgHaze)
- **Vice City Stories recompiler (upstream):** [gothamor/gta-vcs-recomp](https://github.com/gothamor/gta-vcs-recomp)
- **Xbox 360 recompilation tooling:** [hedge-dev/XenonRecomp](https://github.com/hedge-dev/XenonRecomp)
- **Need for Speed native ports (PC, Mac, Steam Deck):** [SpeedBreakerProject/speedbreaker](https://github.com/SpeedBreakerProject/speedbreaker)
- **Index of existing recompilations:** [BlueInterlude/awesome-recompilations](https://github.com/BlueInterlude/awesome-recompilations)

Questions about the Vice City Stories port belong on the upstream repository — forks cannot have issues enabled.

---

### 🤝 Why recompilation

An emulator re-creates the original hardware at runtime and pays for it every frame. A recompiled binary leaves that behind: the game's own code, at the speed of the machine you are on, in a folder you can read and mod.

Give it your own disc. Recompiled, not emulated.
