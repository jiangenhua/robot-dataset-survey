# Robot / Embodied AI Dataset Survey

Interactive survey dashboard and research report for **89 robot manipulation & embodied AI open-source datasets** (2018-2026).

## Live Demo

- **Dashboard**: [https://jiangenhua.github.io/robot-dataset-survey/dashboard.html](https://jiangenhua.github.io/robot-dataset-survey/dashboard.html)
- **Report**: [https://jiangenhua.github.io/robot-dataset-survey/report.html](https://jiangenhua.github.io/robot-dataset-survey/report.html)

## Key Findings

1. **Data resources are highly concentrated** — Top 5 datasets account for 60%+ of total storage; Top 3 robot platforms account for 60%+ of trajectories
2. **Tabletop manipulation is over-represented** — ~90% of datasets focus on tabletop manipulation; humanoid, dexterous hand, and mobile manipulation are severely under-represented
3. **Semantic action annotation is the biggest bottleneck** — Low-level EEF/joint actions are universal, but semantic annotations like "pick up the red cup" cover less than 30%
4. **Cross-embodiment generalization is limited by data imbalance** — Franka dominates (~35%), and OXE-AugE shows 24-45% improvement with more diversity
5. **Sim-to-Real gap is a compound problem** — Not just visual, but visual + control + physics combined
6. **Real-robot evaluation is scaling up** — RoboChallenge, ManipulationNet, ManipArena mark the shift to global evaluation infrastructure
7. **Data standards are rapidly evolving** — RLDS → LeRobot v3.0 dramatically lowers the barrier
8. **Humanoid data is the next explosion point** — humanoid-everyday, HumanPlus, RoboMIND 2.0 are just the beginning

## Tech Stack

- Pure HTML/CSS/JS (no build step)
- Chart.js for visualizations
- Dark theme, responsive design
- GitHub Pages hosting

## Structure

```
├── dashboard.html   # Interactive data dashboard (8 charts)
├── report.html      # Full research report (5 chapters)
├── style.css        # Shared styles
├── data.json        # Dataset JSON (89 entries)
└── README.md
```
