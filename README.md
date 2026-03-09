# Pulse of the World

**Feel the numbers.**

A web experience that makes global statistics visceral. A grid of cells, each pulsing at the rhythm of real-world events — births, deaths, deforestation, reforestation. No charts. No axes. Just a heartbeat for every metric that matters.

## Concept

Abstract numbers are hard to grasp. *4.4 births per second* means nothing until you see a cell pulse every 227 milliseconds. *1.8 deaths per second* — a slower, heavier beat. Side by side, they tell a story no bar chart can.

Each cell in the grid represents one global metric:

| Metric | Approx. Rate | Pulse Interval |
|---|---|---|
| Births | ~4.4/sec | ~227ms |
| Deaths | ~1.8/sec | ~556ms |
| Trees cut down | ~15/sec | ~67ms |
| Trees planted | ~5/sec | ~200ms |
| CO₂ emitted (tonnes) | ~1,200/sec | continuous glow |
| Lightning strikes | ~100/sec | rapid flicker |
| *(more to come)* | | |

The grid is alive. Every cell breathes at its own frequency. The viewer doesn't read — they *feel*.

## Design Principles

- **Minimal.** Black background. Cells as colored squares. Nothing else.
- **No interaction required.** It works as a passive display, a digital art piece, a lobby installation.
- **Responsive.** Scales from phone to projector wall.
- **Data-honest.** Every pulse maps to a real, sourced number. No dramatization.

## Tech Stack (Planned)

- Vanilla HTML/CSS/JS — no framework overhead
- CSS animations or `requestAnimationFrame` for smooth pulsing
- Optional: WebGL for large grids with particle effects
- Data sources: UN, WHO, World Bank, Our World in Data

## Roadmap

- [ ] Define initial set of 12–16 metrics with sources
- [ ] Prototype: single pulsing cell with configurable rate
- [ ] Grid layout with responsive scaling
- [ ] Color palette (each metric category gets a hue)
- [ ] Data source attribution overlay
- [ ] Optional: ambient sound layer (subtle heartbeat per cell)
- [ ] Deploy to simiono.com

## Philosophy

> We drown in numbers. This project doesn't add more — it translates them into something the body understands.

## License

AGPL-3.0 — see [LICENSE](LICENSE).

## Author

[simiono](https://simiono.com) · Uwe Trostheide
