<p align="center">
  <picture>
    <img alt="Runtime Notes" src="https://raw.githubusercontent.com/runtimenoteslabs/.github/main/profile/banner-light.png" width="100%">
  </picture>
</p>

<p align="center">
  <a href="https://runtimenotes.com">Blog</a> ·
  <a href="https://runtimenotes.com/projects/">Projects</a> ·
  <a href="https://runtimenotes.com/about/">About</a> ·
  <a href="https://runtimenotes.com/rss.xml">RSS</a>
</p>

---

Public code from [runtimenotes.com](https://runtimenotes.com). Maintained by [@AnandDN](https://github.com/AnandDN).

## Projects

| Project | What it does | Links |
| :--- | :--- | :--- |
| **[gladiator](https://github.com/runtimenoteslabs/gladiator)**<br>`Python` | Two zero-human AI companies competing for GitHub stars on identical starter repos. Nine Claude agents, growth-first against quality-first, running on Paperclip orchestration and Hermes Agent workers. Built for the Nous Research Hermes Agent hackathon, March 2026. | [Demo](https://youtu.be/YqLcMmzl3Yg) · [Notes](https://runtimenotes.com/blog/two-ai-companies-zero-humans/) |
| **[memory-layer](https://github.com/runtimenoteslabs/memory-layer)**<br>`Python` | Persistent memory for AI coding agents that learns from outcomes. Advice that works gets boosted, advice that fails gets penalized. Five weighted retrieval signals, nine knowledge categories, served over MCP, REST, SDK and CLI. Retrieval precision went from 70% to 90% across 12 weeks of use. | [Series](https://runtimenotes.com/blog/why-does-my-ai-keep-forgetting/) |
| **[cc-rig](https://github.com/runtimenoteslabs/cc-rig)**<br>`Python` | Project setup generator for Claude Code. Pick a framework and a workflow, get the agents, hooks, commands, skills, plugins and team memory written out as native Claude Code files. 16 frameworks × 5 workflows, no runtime dependencies. | [PyPI](https://pypi.org/project/cc-rig/) · [Notes](https://runtimenotes.com/blog/most-claude-code-setups-are-half-configured/) |
| **[sideband](https://github.com/runtimenoteslabs/sideband-public)**<br>`Rust` | Monitor control for Windows over DDC/CI. Brightness, contrast, input, volume and RGB gains on any brand of display, plus window layouts you draw yourself. It asks each display what it supports instead of matching it against a model list, so displays the manufacturer stopped supporting keep working. One 347 KB binary. | [Site](https://sideband.runtimenotes.com) · [Releases](https://github.com/runtimenoteslabs/sideband-public/releases/latest) |
| **ScribeOps**<br>`Rust · WASM` | Local-first markdown editor. Parsing, sanitizing and highlighting run in the browser in Rust and WebAssembly, keyed by content hash per block, so a 10,000-line file redraws in 19 ms per keystroke. Files open and save on your own disk. | [Site](https://scribeops.runtimenotes.com/landing/) · [Benchmark](https://scribeops.runtimenotes.com/bench/) |
| **Cairn**<br>`Python · React` | Personal knowledge base for X bookmarks and likes. Imports your saves into a local database, connects them into a knowledge graph and answers questions across them using your own model and key. Alpha. | [Demo](https://www.youtube.com/watch?v=McyaXZLH5kc) · [Guide](https://runtimenotes.com/blog/retrieving-likes-and-bookmarks-from-x/) |

## Writing

[runtimenotes.com](https://runtimenotes.com) covers AI agents, payments infrastructure, engineering and trading. A few places to start:

- [Running a coding model on RunPod: 8 things that will break](https://runtimenotes.com/blog/running-a-coding-model-on-runpod/) · self-hosting with vLLM, with cold boot, latency and prefill measured on an RTX PRO 6000
- [I spent 6 weeks building AI memory that learns from what ships](https://runtimenotes.com/blog/why-does-my-ai-keep-forgetting/) · the entry point to a four part series on memory-layer, from landscape review to retrieval scoring to integration
- [Most Claude Code setups are half-configured](https://runtimenotes.com/blog/most-claude-code-setups-are-half-configured/) · Claude Code reads far more than CLAUDE.md on startup and most projects configure none of it
- [What a company brain is and what it isn't](https://runtimenotes.com/blog/what-a-company-brain-is/) · three layers, three knowledge tiers and six product categories that get confused for the same thing
- [Building a payment orchestration layer](https://runtimenotes.com/blog/building-a-payment-orchestration-layer/) · vault design, routing engines and the production operations behind a multi-processor payment system

Subscribe by [RSS](https://runtimenotes.com/rss.xml).
