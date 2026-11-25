# Prashant Kumar

Product leader and MIT Sloan Fellow (MBA, May 2027). I build applied AI and agentic products, and I build with AI myself.

Most recently I was Head of Product at Oesia, where I ran the Digital Solutions P&L and built Oesia Knowledge Manager, an on-premises agentic platform that used a knowledge graph with Graph RAG. Before that I worked at Amazon across Marketplace, Retail and Amazon Business.

Website: [pkumarpmleader.com](https://www.pkumarpmleader.com)

## Live demos

- **[Emberhollow · The Last Hearth](https://pkumar1301.github.io/emberhollow/)**: a fantasy village strategy game, playable through Level 4 and still in progress. In a minute you can start a story, name your chief and build toward the opening raid. ([repo](https://github.com/pkumar1301/emberhollow))
- **[Jungle Soldier (Arcade Archer)](https://pkumar1301.github.io/Arcade_Archer/)**: a browser run-and-gun game with a 36-stage campaign. In a minute you can clear the first stretch of jungle with W, the mouse and Space. ([repo](https://github.com/pkumar1301/Arcade_Archer))
- **[World Cup Almanac](https://github.com/pkumar1301/world-cup-almanac)**: every men's World Cup from 1930 to 2026, plus an Elo and Monte-Carlo forecast for 2026. Run locally: open `index.html`, or `python3 -m http.server 8000`.
- **[Fantasy Auction Model](https://github.com/pkumar1301/fantasy-auction-model)**: team project, AI Edge Project 1 (15.071), forked from [gaspardcheng/fantasy-auction-model](https://github.com/gaspardcheng/fantasy-auction-model). It predicts NBA stats from 30 seasons of box scores and injury-report text, then prices players for an auction draft.

## How I build

- I build with AI coding tools. The repos carry the briefs I wrote for them, such as `START_HERE_CLAUDE.md` and `README_FOR_CODEX.md` in Arcade Archer.
- JavaScript and Three.js for the games; plain HTML, CSS and JavaScript with no build step for the almanac and Emberhollow.
- Python for engines and data pipelines. Emberhollow resolves every battle with a Python engine that runs in the browser through Pyodide. The almanac pipeline uses the standard library only.
- Automated checks: Emberhollow runs its unit, campaign and browser tests on GitHub Actions on every push; the almanac rebuilds its data and forecast daily on GitHub Actions; Arcade Archer has Playwright checks with recorded results.

## What I work on

Agentic products, retrieval grounding, AI platform product, pricing and monetization.
