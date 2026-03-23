# Algebraverse

> Adaptive, gamified algebra training tool with endless tiered challenges, hints, and calculator support.

[![HTML5](https://img.shields.io/badge/HTML5-Canvas orange?style=flat square&logo=html5)](https://html.spec.whatwg.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript ES6-yellow?style=flat square&logo=javascript)](https://developer.mozilla.org/en US/docs/Web/JavaScript)
[![Math.js](https://img.shields.io/badge/Math.js Symbolic blue?style=flat square)](https://mathjs.org/)

---

## Overview

Algebraverse is an engaging, web based algebra game designed to help students practice and master algebraic problem solving in an interactive, gamified environment. Built with vanilla HTML5, CSS3, and JavaScript, this application delivers an endless stream of progressively challenging algebra problems with built-in hints, calculator support, and adaptive difficulty.

The game features a bubble particle background, responsive design, and real-time feedback that encourages players to tackle increasingly complex algebraic challenges. Perfect for students of all levels, Algebraverse combines education with entertainment to make algebra practice enjoyable and effective.

---

## Features

- Endless procedurally generated algebra challenges at tiered difficulty levels
- Real-time problem validation using Math.js symbolic expressions
- Built-in scratch pad scientific calculator with expression evaluation
- Three tier hint system with step-by-step guidance
- Gamification mechanics: XP points, coins, lives, and streaks
- Animated bubble particle background via Canvas 2D
- LocalStorage persistence for progress and preferences
- Dark themed responsive interface for mobile and desktop
- Keyboard shortcuts for quick input
- Instant feedback and performance metrics

---

## Screenshots

> Drop screenshots into `screens/` or the root and they'll render here.

![Algebraverse Game](screens/algebraverse.png)

---

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required

### Play Online

Visit the live game at: https://algebraverse by naadir.netlify.app/

### Local Development

```bash
git clone https://github.com/Naadir-Dev-Portfolio/HTML5-Game-Algebraverse.git
cd HTML5-Game-Algebraverse
# Open index.html in your web browser
python -m http.server 8000  # Or use any local server
```

Then navigate to `http://localhost:8000` in your browser.

---

## Tech Stack

- HTML5 Canvas, Animated particle background
- CSS3, Responsive styling, flex/grid layouts, animations
- Vanilla JavaScript (ES6), Game logic and state management
- Math.js, Symbolic math expression evaluation and simplification
- LocalStorage, Persistent progress tracking
- Netlify, Cloud deployment

---

## How to Play

1. Read the algebra problem displayed at the top
2. Type your answer into the input field
3. Click "Check" to submit your solution
4. Use the "Scratch Pad" calculator for complex calculations
5. Request hints if stuck (hints cost some XP)
6. Earn coins and XP for correct answers
7. Lose a life for incorrect answers or timeouts
8. Try to survive as long as possible and climb the difficulty tiers

---

## Related Projects

- [HTML5-Game Hexamatch](https://github.com/Naadir Dev Portfolio/HTML5-Game Hexamatch)
- [HTML5-Game LogicGrid](https://github.com/Naadir Dev Portfolio/HTML5-Game LogicGrid)
- [HTML5-Game RainDrops](https://github.com/Naadir Dev Portfolio/HTML5-Game RainDrops)
