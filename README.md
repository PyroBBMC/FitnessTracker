# Fitness Tracker

A personal 9-week fitness dashboard built as a single HTML file — no build tools, no dependencies to install.

## Features

- **Weekly Workout Planner** — Day-by-day exercise cards with targets across a 9-week program
- **Workout Logger** — Log sets, reps, and weights per exercise; data persists in `localStorage`
- **Progress Charts** — Visualize lift progression over the program
- **Pull-up Tracker** — Dedicated grid to track pull-up volume week by week
- **Nutrition Tab** — Macro targets, meal plans, food swap suggestions, and a daily macro logger
- **Milestones** — Checkable goal cards with target dates and notes
- **Week Navigation** — Step through weeks via sidebar controls; phase label updates automatically

## Usage

Open `fitnessTracker.html` directly in any modern browser — no server required.

All logged data is stored in the browser's `localStorage` and persists between sessions.

## Tech

- Vanilla HTML, CSS, and JavaScript
- Chart.js (loaded via CDN) for progress graphs
- Zero build steps
