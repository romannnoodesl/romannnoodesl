<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/romannnoodesl/romannnoodesl/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/romannnoodesl/romannnoodesl/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/romannnoodesl/romannnoodesl/output/github-contribution-grid-snake-dark.svg">
  </picture>
</div>

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=500&color=F7B801&center=true&vCenter=true&width=435&lines=Hey+%F0%9F%91%8B%2C+I'm+Roman;Indie+Developer;Open+Source+Builder;Web+Monetization+Nerd" alt="Typing SVG" />
</h1>

<div align="center">
  <a href="https://earnify.cc"><img src="https://img.shields.io/badge/earnify.cc-09090B?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
  <a href="https://discord.gg/g2JxcVYavJ"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
  <a href="https://dev.to/romannoodles"><img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white" /></a>
  <a href="https://www.youtube.com/@romannoodles4339"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
  <a href="mailto:contact@earnify.cc"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</div>

---

## About Me

I'm Roman — been building stuff for the web for a while now. Started with vanilla JS and jQuery back in the day like everyone else, went through the React rabbit hole, and somewhere along the way fell into Rust and WASM because I wanted things to go faster. Now I spend most of my time thinking about how websites can make money without selling their users down the river.

That whole ad experience on the modern web — the trackers, the popunders, the 15-second unskippables before a 3-minute video — it sucks. I don't think that's the only way. There's a version of the web where publishers get paid and visitors don't feel violated. That's what I'm trying to help build.

I also write about this stuff on Dev.to when I have something worth saying, and occasionally ramble on YouTube about browser internals and indie dev chaos.

**The short version:** I make things, break things, fix them, repeat.

---

## What I'm Building

### [earnify.cc](https://earnify.cc)

Browser-based CPU mining for publishers. The idea is straightforward — instead of plastering ads everywhere, a website can use a tiny bit of your computer's spare processing power while you're browsing, and the publisher gets paid. No ads, no trackers, no data collection.

I landed on this approach after watching the ad-blocking arms race play out for years. Ad blockers win, ad networks adapt, users get more aggressive blockers, publishers get squeezed. It's a lose-lose-lose. Mining isn't perfect either — there's a bad taste left from the CoinHive days and people forcing 100% CPU usage without consent. So earnify is designed differently:

- **Opt-in by default** — publishers can request, users can decline, assuming the publishers implemented it lol
- **doesnt pause off tab** — if you're not looking at it, it wont matter
- **WebAssembly miner** — runs in-browser, no extensions or installs

The hard part isn't the mining logic — it's making the economics work. WebAssembly hash rates are slower than native by a factor of 10-20x. I'm currently working on WASM SIMD optimizations to close that gap. Getting there piece by piece.

### Honest talk about ROI

CPU mining on the web won't replace ad revenue for most sites. Not yet. But for smaller publishers with engaged audiences who hate ads, it can cover hosting costs and then some. The numbers get better every year as hardware improves and the WASM runtime gets faster. I'm playing the long game here.

---

## Current Focus

- **WASM SIMD optimizations** for the miner — squeezing every cycle out of the browser runtime
- **Sub-100KB WASM binary** — currently around 140KB, need to shed more weight
- **Web Worker pool management** — better multi-threaded scheduling without nuking the user's laptop fan
- **Dashboard rewrite** — moving from server-rendered to a SPA for real-time stats
- **Alternative algorithms** — looking at RandomX light mode as a potential option

---

## Stack & Tools

<div align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,rust,html,css,nodejs,react,wasm,webpack,babel,git,github,linux,vscode" />
</div>

| Category     | What I Use                                      | Why                                                                |
|-------------|-------------------------------------------------|--------------------------------------------------------------------|
| Languages   | JavaScript, TypeScript, Rust, HTML5, CSS3       | JS/TS for the web layer, Rust when I need speed                    |
| Frontend    | React, WebAssembly, Web Workers, Canvas API     | React for UIs, WASM for the heavy lifting                          |
| Backend     | Node.js, Express, WebSocket, PostgreSQL         | Node is fine for API work, WebSocket for real-time mining stats    |
| Tools       | Webpack, Vite, Git, GitHub Actions              | Webpack for the main build, Vite for prototypes, Actions for CI    |
| Platform    | Linux, Docker, Cloudflare Workers               | Linux daily driver, Docker for dev env, Workers for edge stuff     |
| Concepts    | Browser internals, CPU mining algos, P2P        | Deep dive into how browsers actually run your code                 |

I run Linux on my daily machine and do everything with vscode and gnome text editor. Tried VIM for a year, went back, do hard lol.

---

## GitHub Analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=romannnoodesl&show_icons=true&theme=dark&hide_border=true&count_private=true&include_all_commits=true&bg_color=0D1117" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=romannnoodesl&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&langs_count=8" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=romannnoodesl&theme=dark&hide_border=true&bg_color=0D1117&fire=F7B801&ring=F7B801&currStreakLabel=F7B801" />
</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=romannnoodesl&theme=darkhub&no-frame=true&margin-w=4&row=2&column=4" />
</div>

I don't chase green squares but I try to ship something every week. Some weeks are busier than others. Life happens.

---

## Activity Graph

[![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=romannnoodesl&theme=react-dark&hide_border=true&area=true&custom_title=Contribution%20Graph)](https://github.com/ashutosh00710/github-readme-activity-graph)

---

## Projects

| Project | What It Does | Made With | Status |
|---------|-------------|-----------|--------|
| [earnify.cc](https://earnify.cc) | CPU mining for publishers that doesn't suck | JS, Rust, WASM | Live & active |
| More coming | Got a few side things cooking | — | Soon-ish |

---

## What I'm Reading / Learning Right Now

- **Gothic Violence** (again) — every time I read it I catch something I missed, but dont get me wrong i do not support any actions in that book
- **Industrial Society and Its Future** — love this book, i find ted very interesting.
- **Mastering Monero: The future of private transactions** — bought this book for my cousin but read it beforehand 
- **Programming Basics with JavaScript** — this is how i got into coding

I do like to read from very technichal to very political books and novels.

---

## Blog Posts & Writing

I write on [Dev.to](https://dev.to/romannoodles) about web monetization, indie dev, and the occasional hot take about the ad industry. Some posts I've done:

- Browser mining in 2025 — is it dead or just hibernating?
- Why I stopped trying to compete with ads
- WASM vs Native: benchmarking the gap
- Building a CPU miner from scratch in Rust

More writing on the way as earnify develops and I learn new things worth sharing.

---

## Let's Connect

<div align="center">
  <a href="https://earnify.cc"><img src="https://img.shields.io/badge/Website-09090B?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
  <a href="https://discord.gg/g2JxcVYavJ"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
  <a href="https://dev.to/romannoodles"><img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white" /></a>
  <a href="https://www.youtube.com/@romannoodles4339"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" /></a>
  <a href="mailto:contact@earnify.cc"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</div>

<div align="center">
  <br />
  <img src="https://komarev.com/ghpvc/?username=romannnoodesl&color=F7B801&style=flat-square&label=Profile+Views" />
  <br />
  <br />
  <img src="https://img.shields.io/github/followers/romannnoodesl?style=social" />
  <img src="https://img.shields.io/github/stars/romannnoodesl?style=social" />
</div>

<div align="center">
  <br />
  <sub>If you got this far, thanks for reading. Now go build something.</sub>
</div>
