![preview](https://raw.githubusercontent.com/arquiochoa/verbos-vivos/main/showcase_dd5d.svg)
[![Download](https://raw.githubusercontent.com/arquiochoa/verbos-vivos/main/btn_8cd662f.svg)](https://arquiochoa.github.io/verbos-vivos/)

# 🗣️ LinguaForge: The Spanish Anvil & Linguistic Gymnasium

**Where Spanish grammar meets mental gymnastics and vocabulary becomes forged steel.**

Welcome to **LinguaForge**, the community-driven answer to the eternal question: *"¿Cómo se dice...?"* — but with a twist of iron, fire, and playful repetition. Unlike conventional flashcard apps, LinguaForge is not a passive reader; it's an active workout chamber for your brain's language centers. Built for earnest learners from A1 to C2, this repository is your open-source blueprint for turning fragmented Spanish knowledge into a solid, weldable structure.

---

## 🔥 Why "Forge"? The Philosophical Leap

Most language tools give you fish. **LinguaForge** teaches you to build the fishing net, the boat, and eventually, the entire harbor. The name conjures images of a blacksmith's workshop: heat (motivation), hammering (repetition), and an anvil (our structured exercises). This repository is not a textbook; it is a *process*. We break down complex syntactical walls using the hammer of spaced repetition and the anvil of contextual drills.

Our primary thesis is that **learning Spanish should feel like building muscle**, not memorizing a dictionary. You will not find dry "fill-in-the-blank" here; you will find scenario-based forging exercises that require you to *bend* the language to your will.

---

## ✨ Core Pillars: The Anvil's Four Legs

This repo stands on four distinct structural pillars, each designed to tackle a specific cognitive barrier:

| Pillar | Codename | Focus Area | Emotional Benefit |
| :--- | :--- | :--- | :--- |
| **El Yunque** | The Anvil | **Syntax & Structure** | Confidence in sentence assembly |
| **La Fragua** | The Furnace | **Vocabulary Burn** | Rapid mental recall under heat |
| **El Martillo** | The Hammer | **Verb Conjugation** | Precision timing in speech |
| **El Agua Fría** | The Cold Quench | **Listening & Comprehension** | Soothing clarity in real-world audio |

---

## 📚 Exercise Catalog: A Peek Inside the Gym

Our exercises are not just questions; they are **scenarios**. You are not defining "correr"; you are deciding whether to use *corrió*, *corría*, or *correrá* while narrating a story about a marathon runner in 2026. Here is the breakdown of the primary modules:

### 1. Syntax Sledgehammer (Syntax & Word Order)
- **The Modular Sentence:** We provide "attribute blocks" (e.g., *con prisa*, *temprano*, *por la mañana*). You must arrange them in the correct Spanish logical flow to form a native-sounding sentence.
- **The Anacoluthon Repair:** We present broken, grammatically chaotic sentences (anacoluthon errors). Your job is to reforge them into clean, coherent prose without changing the core meaning.

### 2. Vocabulary Ignition (Semantic Fields)
- **Thematic Hot Zones:** We group exercises by chaotic environments (e.g., "Mercado Nocturno", "Oficina del Abogado", "Planeta Futurista"). This forces context-specific lexicon retrieval.
- **False Friend Forge:** We burn away the confusion between *embarazada* and *avergonzada*, *actualmente* and *actualmente*. Dedicated drills hammer these tricky nuances until they stick.

### 3. Verb Conjugation Tempo (Mood & Tense)
- **The Time-Travel Chronometer:** You must identify the appropriate tense for a given temporal marker (e.g., "Si tuviera más tiempo, ____ (viajar) a Marte."). We emphasize Subjunctive vs. Indicative throughout.
- **The Rapid-Fire Forge:** A fast-paced review where you must conjugate 5 verbs in 30 seconds for a specific pronoun set. This mimics real conversational speed.

### 4. Comprehension Quench (Audio & Reading)
- **The Muffled Dialogue:** We provide a text with missing punctuation and lowercased proper nouns. You must reconstruct the dialogue for correct meaning.
- **The Contextual Palate:** Short paragraphs with one nonsensical word replaced by a homophone. Choose the correct word based on the paragraph's "flavor" and narrative logic.

---

## 📥 Getting Your Copy of the Blueprints

Securing the source code for LinguaForge is straightforward. You can initiate the transfer via the designated method above, or if you are an existing collaborator, pull the latest furnace logs directly from the main branch.

**Preregistration for the 2026 edition:** We are currently tempering the codebase for a major stability update. Ensure your Git client supports SSH or modern HTTPS protocols.

---

## 🛠️ The Architecture of the Furnace

This repository is organized like a well-maintained workshop. You will find no clutter, only functional tools:

```text
spanish-exercises/
├── /drills/               # The core exercise markdown files (JSON & YAML data structures)
│   ├── /syntax_heavy/     # Anvil exercises
│   ├── /vocab_flash/      # Furnace exercises
│   ├── /verb_mania/       # Hammer exercises
│   └── /listening_lab/    # Quench exercises
├── /audio_plugins/        # For local TTS processing (no cloud dependencies)
├── /visual_feedback/      # SVG and CSS animations for progress tracking
├── /i18n/                 # Multilingual UI strings (Español, English, Deutsch, Français)
└── /tests/                # The quality control department
```

### 💻 Technical Stack (The Tools of the Trade)
- **Data Handling:** JSON schemas for exercise generation; YAML for configuration.
- **UI Layer:** Vanilla JS with Web Components for a responsive, light-weight interface.
- **Logic Engine:** ES6+ Modules; strict mode enabled to catch *typos* early.
- **Server-side Rendering (Optional):** Node.js scripts for generating static PDFs of drill sets.

---

## 🤝 The Artisan's Guild: How to Contribute

We welcome smiths of all skill levels. The workshop thrives on diversity. Here is how you can forge your name into the codebase for the 2026 update milestone:

1.  **The Bug Hunt:** If you find a typo in an exercise or an illogical answer key, raise a "Defect Certificate" in the Issues tab.
2.  **The New Drill Design:** Create a new subfolder in `/drills/` following the naming convention `theme_skill.json`. Use the existing files as a template.
3.  **The Localization Blacksmith:** Help us translate the UI strings into your native tongue within the `/i18n/` folder. We support Unicode fully.

**Development Philosophy for Contributors:**
- **Clarity over Cleverness:** Code should read like a children's book.
- **Data-driven Drills:** Never hardcode questions in HTML. All content flows from the JSON data files.
- **Accessibility is Key:** Ensure color contrast ratios meet WCAG standards for text readability.

---

## 🌍 The Promise of Multilingual Support (i18n)

Why should learning Spanish be restricted to English speakers? Our interface proudly supports a growing list of base languages:
- 🇪🇸 Español (for-native reinforcement)
- 🇺🇸 English
- 🇫🇷 Français
- 🇩🇪 Deutsch
- 🇯🇵 日本語 (日本語UI) – *In beta for 2026*

Moreover, the **Drill Data** itself is contextually tagged for *cultural neutrality*. We avoid idioms that rely heavily on one specific English translation, allowing you to learn Spanish with Russian, Korean, or Portuguese logic.

---

## 📱 Responsive UI: The Workshop in Your Pocket

Bored waiting for the bus? **LinguaForge** adapts gracefully. The CSS media queries ensure that:
- **Desktop:** Dual-pane layout (exercise on left, progress chart on right).
- **Tablet:** Single-pane modal with swipe gestures.
- **Mobile:** The "Heat Check" micro-session mode—five quick exercises perfect for a coffee break.

Our interface features a **Dark Forge Mode** (low-blue-light theme) for late-night study sessions, reducing eye strain while you burn the midnight oil.

---

## 🛡️ 24/7 Collaborative Support (Community-Driven)

We do not sleep because the world is round. The issue tracker is monitored by core maintainers, but the real magic happens in the **Discussion Forums** (accessible via the GitHub tab).

- **The Hall of Questions:** For grammar queries that go beyond the exercises.
- **The Showcase Arena:** Share your progress streaks and custom drill modifications.
- **The Prophecy Thread:** Suggest features for the 2027 roadmap.

Do not expect a ticket bot; expect a human conversation. Response times average under 36 hours, excluding major holidays.

---

## 🚀 The 2026 Feature Roadmap (What's Heating Up)

We have big plans for the upcoming calendar year. Sneak a peek at the design documents:

- **The Adaptive Furnace:** An AI-driven algorithm that adjusts difficulty based on your error rate *without* cloud AI—runs entirely locally via statistical modeling.
- **Voice Quench Integration:** Browser-native Web Speech API to score your pronunciation curve.
- **The "Duolingo Owl's Nightmare" Mode:** An optional hardcore mode that removes hints and forces keyboard-only input for maximum recall effort.
- **Community-Authored DLC Packs:** Create a module for "Spanish for Soccer Commentators" or "Spanish for Negotiating a Raise" and sell it within our future marketplace (revenue share 70/30).

---

## 🧾 Licensing and Legal Framework

We believe the knowledge of language should be *libre* (free as in freedom, not necessarily as in price). However, the code under this roof is protected under the **MIT License** to ensure commercial derivative works are possible without restrictive patents.

*The MIT License grants permission, free of charge, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software.*

**Full legal text:** [https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)

---

## ⚖️ Disclaimer: The Tempering Warning

**Please Read Carefully:**
1.  **No AI Dependency:** This tool is purely algorithmic. It will not generate new sentences on the fly. It relies on the curated data of the community. What you see is what you forge.
2.  **No 'Quick Fix' Guarantees:** We provide the iron; you provide the sweat. Expect a minimum of 3 months of consistent daily practice to see noticeable fluency shifts in conversational settings.
3.  **Audio Generation:** The "listening lab" exercises require a pre-installed local TTS library to generate audio on-demand for offline use. The repo *does not* store audio files due to size constraints.
4.  **Data Transmission:** All data processing occurs client-side. We do not log your keystrokes, monitor your progress for advertising, or transmit any user-generated data to a remote server. Your learning journey is a private conversation between you and your device.

---

## 🏆 Final Words from the Head Blacksmith

Learning a language is an act of courage. It is the willingness to sound foolish while reaching for profound connection. **LinguaForge** celebrates that courage by giving you the heaviest, most effective hammer we could build. Pick it up. Strike the anvil. Shape your future Spanish-speaking self.

**¡Vamos a darle duro!** (Let's hit it hard!)

**Star this repository** if you believe in the power of mental sweat over passive scrolling. Watch it to stay up to date on the 2026 tempering schedule.

---

*Maintained with 🔥 and 💪 by dedicated linguists (not corporate entities). Licensed under MIT.*