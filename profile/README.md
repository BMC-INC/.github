# BMC INC · ExecLayer

**Tools and research for AI systems that can explain what they remember, what they are allowed to do, and what actually happened.**

This public collection includes James Benton's personal projects, open-source tools, research, experiments, and project websites. Projects have different levels of maturity; each README describes what is implemented and how it has been tested.

**The public repositories are one part of BMC INC's work.** The company maintains a broader portfolio of private repositories for its products and internal development. This page is a guide to the public collection, rather than a complete inventory of company products or private development. A public project website or prototype should be evaluated according to its stated scope and status.

[Company & founder](https://execlayer.net) · [Selected work](https://execlayer.net/work) · [Research](https://execlayer.net/research) · [Evidence & primary sources](https://execlayer.net/evidence)

## Start with the tools

| Project | What it does | Where to start |
| --- | --- | --- |
| [IronMem](https://github.com/BMC-INC/Iron-mem) | Persistent memory for AI coding assistants, with local storage, retrieval, provenance, and policy controls. | Rust runtime and MCP server; source installation and verification in the README. |
| [Coding Ledger](https://github.com/BMC-INC/coding-ledger) | Connects local AI coding activity and estimated spend with Git activity to support delivery analysis. | Python CLI and local dashboard; Elastic-2.0 source-available license. |
| [exfetch](https://github.com/BMC-INC/exfetch) | Gives agents structured web-fetching tools and a browser-extension bridge. | Rust CLI and MCP server; review current capabilities and security boundaries before connecting a browser. |
| [Sovereign Prompt](https://github.com/BMC-INC/Sovereign-Prompt) | Refines prompts locally and exposes the workflow through MCP and an optional API proxy. | Development-stage Rust application; local setup and integration limits are documented. |
| [AI Bot Checker](https://github.com/BMC-INC/ai-bot-checker) | Inspects a website's robots.txt rules for named AI crawlers and generates policy templates. | Python CLI or web interface; policy inspection does not prove crawler compliance or AI visibility. |

## Integrations and companion tools

| Project | Purpose |
| --- | --- |
| [IronMem for Cursor](https://github.com/BMC-INC/ironmem-cursor-plugin) | Cursor plugin configuration, rules, and skills for the separately installed IronMem runtime. |
| [Coding Ledger Homebrew tap](https://github.com/BMC-INC/homebrew-coding-ledger) | Homebrew distribution and installation instructions for Coding Ledger. |
| [Buddy Voice](https://github.com/BMC-INC/buddy-voice) | macOS text-to-speech for terminal companions, with a CLI and experimental editor integration. |

## Research and evaluation

| Project | What you will find |
| --- | --- |
| [ExecLayer Papers](https://github.com/BMC-INC/execlayer-papers) | Published papers, versioned publication links, citation guidance, and separately identified pre-release work. |
| [IronMem LoCoMo evaluation](https://github.com/BMC-INC/ironmem-locomo-benchmark) | Evaluation code and committed results for a specified conversational-memory benchmark configuration, with methodology and limitations. |

Research proposals and benchmark results have a different scope from product guarantees. Each repository points to the relevant evidence and explains its validation limits.

## Public websites and interactive demonstrations

| Project | Scope |
| --- | --- |
| [execlayer.net](https://github.com/BMC-INC/execlayer-net) | Source for the public founder, products, research, and evidence website. |
| [QueueFlow Architecture](https://github.com/BMC-INC/queueflow-architecture) | Interactive presentation of the webhook pipeline; the product implementation is maintained separately. |
| [VeriReceipt Website](https://github.com/BMC-INC/verireceipt-site) | A personal project's information, support, and policy website. This public repository contains the website; it does not provide an installable receipt application or establish that the app is complete. |
| [The Map and the Flood](https://github.com/BMC-INC/flood-map) | Interactive editorial scenario about automation and work, with visible assumptions and an illustrative role index. |

## Evaluate, contribute, or collaborate

Start with a project's README for its supported setup, current status, verification commands, and limitations. Use that repository's issues for reproducible bugs and focused proposals. For customer, investment, or research conversations, visit [execlayer.net](https://execlayer.net).

Licensing is repository-specific. Some projects are open source, Coding Ledger is source-available, and some public websites and research materials have no repository-wide software license. Check the relevant license or publication record before reuse.
