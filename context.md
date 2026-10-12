# Project Context

## What this repo is
This repository is a small front-end web game project called "My-First-Github-game". It is a playable Memory/Concentration game built with plain HTML, CSS, and JavaScript.

The main app is in [memory-game.html](memory-game.html). It lets a player match pairs of cards, track moves, time, and star rating, and switch between different board sizes.

## What it does
The game includes:

- A 4x4 and 6x6 card grid
- Card-flip matching gameplay
- Move counter and timer
- Star rating based on performance
- Best score tracking with browser local storage
- Keyboard accessibility support
- Responsive layout for desktop and mobile screens
- A dark mode toggle feature described in the PRD

This is a lightweight browser game designed for learning, practice, and simple interactive web development.

## What the project name stands for
"My-First-Github-game" is a descriptive project name rather than an acronym. It means:

- "My First" = beginner-friendly project
- "GitHub" = the project is hosted and shared on GitHub
- "Game" = the project is a playable browser game

So the name essentially means: a beginner’s first game project on GitHub.

## Key files
- [README.md](README.md) — project overview and how to run it
- [memory-game.html](memory-game.html) — full game implementation
- [PRD_new_dark_mode_feature.md](PRD_new_dark_mode_feature.md) — requirement doc for the dark mode feature

## Overall purpose
The repo is meant to demonstrate a simple but complete web game built without frameworks or libraries. It is useful for learning:

- DOM manipulation in JavaScript
- CSS layout and responsive design
- state tracking and timers
- browser local storage
- accessibility and UI behavior

## How to run it
Open [memory-game.html](memory-game.html) directly in a browser, or serve the folder locally with a simple static server such as:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/memory-game.html
```
