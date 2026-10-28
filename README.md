# Read The Tape

An interactive website that teaches order-flow trading on Nasdaq (NQ) futures.

**Live site:** https://scriptter1234.github.io/read-the-tape/

## Features

- **Live DOM simulator.** A depth-of-market ladder and time & sales tape driven by a small order-book model: market orders consume resting limit liquidity, and price ticks when a level is emptied. Tracks cumulative delta with a sparkline.
- **Seven lessons**: the auction, the DOM and the tape, delta and cumulative delta, footprint charts, absorption and exhaustion, volume profile, and a full trade process.
- **Footprint lab.** A canvas-rendered footprint chart (bid × ask per price) with diagonal imbalance detection (3:1), bar point of control, and a session volume profile with a 70% value area.
- **Quiz.** Five real-session scenarios with instant feedback.
- **Tape, the tutor bot.** Answers order-flow questions from a built-in knowledge base. Runs entirely in the browser, no API.
- Click effects, animations, mobile layout, and reduced-motion support.

## Tech

Single-file static site: HTML, CSS, and vanilla JavaScript. No frameworks, no build step. Hosted on GitHub Pages.

## Disclaimer

Education only. Not financial advice. All market data on the site is simulated.

Built by Hai Le.
