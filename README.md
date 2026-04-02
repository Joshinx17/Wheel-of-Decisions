# 🎡 Wheel of Decision

A fun, interactive decision-making wheel built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies, no build step. Just open the file and spin.

## Demo

Add your options → Build the wheel → Spin → Let fate decide.

![Wheel of Decision](https://via.placeholder.com/800x400/0e0c14/c084fc?text=Wheel+of+Decision)

## Features

- **Add up to 12 options** — type anything and hit Add or press Enter
- **Colorful wheel** — each sector gets a unique color, auto-generated from a curated palette
- **Smooth spin animation** — eased deceleration so the wheel slows down naturally
- **Fixed arrow pointer** — clearly shows the winning sector when the wheel stops
- **Confetti burst** — celebrates your result with a small confetti animation
- **Fully responsive** — works on desktop and mobile browsers
- **Zero dependencies** — single HTML file, loads only a Google Font

## Getting Started

No installation needed. Just download and open.

```bash
# Clone the repo
git clone https://github.com/Joshinx17/Wheel-of-Decisions.git

# Open in your browser
open Wheel-of-Decisions.html
```

Or simply [download the HTML file](./wheel-of-decision.html) and double-click it.

## How to Use

1. Type an option into the input field (e.g. *Pizza*, *Sushi*, *Tacos*)
2. Press **+ Add** or hit **Enter** to add it to the list
3. Repeat for all your options (2–12 options supported)
4. Click **Build the Wheel** — your options appear as colored sectors
5. Hit **Spin the Wheel** and watch it go
6. The red arrow on the right points to the final decision when it stops
7. Click **Start over** to reset and try again

## Project Structure

```
wheel-of-decision/
└── wheel-of-decision.html   # The entire app — HTML, CSS, and JS in one file
└── README.md
```

## Built With

- **HTML5 Canvas** — for drawing and animating the wheel
- **Vanilla JavaScript** — spin logic, easing function, confetti
- **CSS3** — dark theme, glow effects, animations
- **[Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) + [DM Sans](https://fonts.google.com/specimen/DM+Sans)** — via Google Fonts

## Customization

Want to tweak it? Everything lives in the single HTML file.

| What | Where |
|---|---|
| Color palette | `const PALETTE` array in the `<script>` block |
| Max options | Change `options.length >= 12` in `addOption()` |
| Spin duration | Adjust `4500 + Math.random() * 1800` in `spin()` |
| Theme colors | CSS variables in `:root` at the top of `<style>` |
