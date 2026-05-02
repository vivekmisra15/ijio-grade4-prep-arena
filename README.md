# IJIO Grade 4 Prep Arena 🏆

> A modern, interactive study hub for the **International Junior Informatics Olympiad (IJIO/NJIO)** — featuring concept deep dives, realistic drills, and full mock exams tailored for Grade 3 & 4 students.

**[→ Launch the app](https://vivekmisra15.github.io/ijio-grade4-prep-arena/)**

---

## What is this?

A **single-file HTML app** (no build tools, no dependencies to install) that covers the complete IJIO/NJIO syllabus for Grades 3 & 4. Everything runs in the browser — no server required. Just open `index.html`.

## Features

### 📚 10 Deep-Dive Topics
Each topic uses a **5-layer pedagogy** designed for students encountering these concepts for the first time:

1. **Intuition** — a concrete story or analogy
2. **Naive approach** — what students typically try first and why it fails
3. **Correct approach** — fully worked step-by-step examples
4. **"Aha" moment** — the one key insight that makes it click
5. **Common traps** — real IJIO exam mistakes and how to avoid them

**Topics covered:**
| Topic | Exam Weight | Description |
|-------|-----------|-------------|
| Bubble Sort | ~15% | Adjacent swaps, pass tracing |
| Selection Sort | ~12% | Find-minimum-and-swap |
| Combinations & Counting | ~10% | C(n,r), multiplication principle |
| Queues & Stacks | ~8% | FIFO vs LIFO operations |
| Graph Traversal | ~12% | Weighted graphs, Dijkstra's, constraints |
| Block Programming | ~30% | MakeCode/Scratch, variable tracing, loops, conditionals |
| Encryption & Ciphers | ~6% | Caesar cipher, substitution |
| Binary & Encoding | ~6% | Variable vs fixed-length codes |
| Sets & Inclusion-Exclusion | ~6% | Venn diagrams, counting |
| Decomposition & Scheduling | ~8% | Critical path, parallel tasks |

### ⚡ 50+ Core Drill Questions
- Filter by topic
- Mixed practice mode
- **Curated 10-question sprint** with a 3-minute timer (hand-picked for speed and traps)
- Immediate feedback with step-by-step explanations

### 📝 Full Mock Paper
- **20 questions** split into Section A (10 CT questions, 30 marks) and Section B (10 harder algorithm/block questions, 60 marks)
- 60-minute countdown timer
- Per-section scoring after submission
- **Full explanations** for every question shown after submit

### 🏦 Question Bank (150+ Extra Questions)
- **159 additional practice questions** organised into 10 topic tabs
- Difficulty filter (Easy / Medium / Hard)
- Per-topic accuracy tracking
- Covers: sorting traces, combination calculations, queue/stack operations, graph shortest paths, code tracing, cipher decoding, binary conversion, Venn diagrams, and scheduling problems

### 📊 Dashboard
- Mastery donut chart
- Per-topic score bar chart
- 12 achievements with transparent unlock conditions
- Daily goals
- Activity log

### 🎨 Visual Learning Tools
- **CSS block-code renderer** — MakeCode-style coloured blocks (events, variables, loops, conditionals, display) rendered in pure HTML/CSS
- **SVG weighted graphs** — nodes, edges, weights, blocked paths
- **SVG Venn diagrams** — overlapping circles with calculated counts
- **LED grid** — 5×5 Microbit-style dot matrix
- **Maze grid** — walls, start/goal, highlighted paths
- **Animated sorting visualisers** — step-through bubble sort and selection sort

## Tech Stack

- **Single HTML file** — no build step, no assets, no images
- Bootstrap 5.3 (CDN)
- Font Awesome 6 (CDN)
- Chart.js 4 (CDN)
- Canvas Confetti (CDN)
- Google Fonts (Nunito + Playfair Display)
- All progress saved to `localStorage`

## Exam Format Reference

| | Section A | Section B | Bonus | Total |
|---|-----------|-----------|-------|-------|
| **Questions** | 10 CT | 10 Block Programming | — | 20 |
| **Marks** | 30 | 60 | 10 | 100 |
| **Duration** | 60 minutes | | | |
| **Format** | Online · Closed book | | | |

## Deploy

This is a static single-file app. To deploy:

1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your site is live at `https://<username>.github.io/ijio-grade4-prep-arena/`

Or just open `index.html` locally in any browser.

## Question Count

| Category | Count |
|----------|-------|
| Core drills | 46 |
| Question Bank | 160 |
| **Total** | **206** |

### Question Bank Breakdown

| Topic | Questions |
|-------|-----------|
| Bubble Sort | 15 |
| Selection Sort | 15 |
| Combinations | 16 |
| Queues & Stacks | 15 |
| Graphs | 16 |
| Block Programming | 25 |
| Encryption | 15 |
| Binary | 14 |
| Sets & Logic | 15 |
| Decomposition | 14 |

### Question Quality Standards (V5)

All 160 question bank questions have been reviewed by an informatics olympiad coaching lens and meet these standards:

- **Accuracy verified** — every answer index confirmed correct with fully traced solutions
- **No hedging in explanations** — no "actually," "wait," or "let me recheck" language; every explanation is confident and direct
- **No purely definitional questions** — every question requires computation, tracing, or multi-step reasoning (not "which data structure is LIFO?")
- **Minimum explanation depth** — every explanation shows the reasoning process, names the trap being tested, and explains *why* the wrong answers are wrong
- **IJIO-aligned difficulty** — easy questions still require careful reading; hard questions involve multi-pass tracing, constraint reasoning, or edge cases

## License

MIT — free to use, modify, and share.

---

Built with ❤️ for young informatics olympiad competitors.
