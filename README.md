# Data Odyssey — ML Aptitude Quiz

An interactive ML education experience built in a **single HTML file** — no React, no bundler, no dependencies beyond Chart.js.

**[Play it live →](https://sanjaayyy7.github.io/data-odyssey/)**

---

## What it covers

10 core machine learning and statistics concepts, each with a live visualization:

| Round | Concept | Visualization |
|-------|---------|---------------|
| 1 | Correlation vs Causation | Dual-axis line chart — reveal the confounding variable |
| 2 | Simpson's Paradox | Interactive bar chart — toggle aggregate vs split view |
| 3 | P-Value Significance | Sequence ordering interaction |
| 4 | Overfitting | Animated train/validation loss curves diverging |
| 5 | Survivorship Bias | Canvas 2D pixel-art bomber diagram |
| 6 | A/B Test Novelty Effect | MCQ with real-world framing |
| 7 | R² / Variance Explained | Scatter plot with correlation slider |
| 8 | Skewed Distributions | Salary histogram with mean vs median lines |
| 9 | Accuracy Paradox | 10×10 fraud grid + confusion matrix |
| 10 | Regression to the Mean | Boss round — statistical trap |

## Tech stack

| | |
|-|-|
| **Language** | Vanilla JavaScript (ES6+) |
| **Rendering** | Canvas 2D API + Chart.js 4.4.0 |
| **Audio** | Web Audio API (pure synthesis, no audio files) |
| **Fonts** | Press Start 2P + Space Mono (Google Fonts) |
| **Bundler** | None |
| **Frameworks** | None |
| **File count** | 1 |

## Features

- Pixel-art retro aesthetic with scanline overlay and particle physics
- Per-question live ML visualizations (Chart.js line, bar, scatter, radar; Canvas 2D)
- **IN THE WILD** callouts — real FAANG/industry applications after every answer
- Difficulty stars on each question
- 3-lives system, streak multipliers, XP bar, world map
- 8 unlockable achievements
- Results screen: **ML Profile radar chart**, percentile rank, performance insights
- One-click **LinkedIn post generator** (clipboard copy)
- **Downloadable score card** (PNG canvas render)
- Zero server required — open `index.html` and play

## Run locally

```bash
# Just open the file — no install step needed
open index.html
```

## Project structure

```
data-odyssey/
├── index.html   # The entire game — ~3,300 lines of vanilla JS
└── README.md
```

---
