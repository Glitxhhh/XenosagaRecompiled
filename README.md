<p align="center">
  <img src="assets/logo.png" alt="Xenosaga Recompiled" width="720">
</p>

<p align="center">
  A planned native PC recompilation project for the Xenosaga series.
</p>

<p align="center">
  <img alt="Status: planned" src="https://img.shields.io/badge/status-planned-blue?style=flat-square">
  <img alt="Platform: PC" src="https://img.shields.io/badge/platform-PC-0078d4?style=flat-square">
  <img alt="Release: none yet" src="https://img.shields.io/badge/release-none%20yet-lightgrey?style=flat-square">
</p>

<p align="center">
  <a href="#project-status">Status</a> ·
  <a href="#project-goals">Goals</a> ·
  <a href="#development-roadmap">Roadmap</a> ·
  <a href="#community--contributing">Contribute</a> ·
  <a href="#support-me">Support</a>
</p>

## Project Status

**Planned project · No playable build · No release date**

**Xenosaga Recompiled** is an upcoming project aimed at bringing the Xenosaga series to PC through native recompilation and platform-specific systems integration.

The intention is to create a proper native PC experience, rather than permanently depending on a console emulator during gameplay. The technical approach, platform support, implementation details and scope will be established through research before active development begins.

**This repository is currently a project placeholder.** No completed recompilation pipeline, functioning native runtime, playable build, installer or measured game compatibility is being claimed. There is **no public release or announced release date**.

## Project Goals

The long-term direction is informed by [Xenoblade Chronicles Recompiled](https://github.com/Glitxhhh/XenobladeChroniclesRecompiled), but this is a separate project with its own technical requirements. Its implementation will not simply be a copy of the Xenoblade codebase.

The intended goals are:

- **Ahead-of-time recompilation:** Investigate recompiling the original executable code into a form suitable for native PC execution.
- **Native platform integration:** Implement the operating system, input, audio, filesystem and other supporting functionality needed by the game.
- **Native graphics:** Investigate a PC-native graphics implementation that preserves the original presentation while allowing appropriate improvements.
- **Accuracy and compatibility:** Preserve game behavior, progression, rendering, audio and save functionality.
- **A practical installation workflow:** Plan for a local setup process using game files provided by the user, without distributing copyrighted content.
- **PC quality-of-life features:** Evaluate modern display options, configurable input, graphics settings and other improvements where technically feasible.

These are project objectives, **not implemented features or confirmed capabilities**.

## Planned Scope

The long-term subject of this project is the **Xenosaga** series, including **Episode I: Der Wille zur Macht**, **Episode II: Jenseits von Gut und Böse**, and **Episode III: Also sprach Zarathustra**. The initial development target, order of support and feasibility of individual titles have **not yet been established**. Any eventual support for multiple episodes will require separate validation.

## Development Progress

**Status: Not started**

There are no gameplay screenshots, benchmark figures or development percentages to report yet. Progress tracking will be introduced when there is a sufficiently defined technical plan and measurable implementation work.

Unlike the active Xenoblade Chronicles Recompiled project, this README intentionally does not display estimated completion percentages or screenshots from unrelated builds.

### Technical Considerations

The original Xenosaga titles were developed for the **PlayStation 2**, so their executable formats, processor architecture, graphics systems and console services differ significantly from the Nintendo Switch game targeted by Xenoblade Chronicles Recompiled. A PlayStation 2-specific recompilation strategy and runtime design must be researched before implementation claims can be made.

## Development Roadmap

This is an initial outline. Tasks, priorities and milestones may change once the technical investigation begins.

### Phase 1: Research and Feasibility

**Status: Planned**

- Analyze game executables, platform behavior and file formats.
- Assess static recompilation techniques and the feasibility of reusing existing tooling.
- Identify required native system, graphics, audio and input components.
- Establish test cases, architecture and implementation priorities.

### Phase 2: Recompilation and Native Runtime

**Status: Planned**

- Build or adapt an ahead-of-time recompilation pipeline appropriate to the original game.
- Implement the native execution environment and required platform services.
- Establish loading, memory management, timing, input and filesystem behavior.
- Work toward initial boot and reproducible testing.

### Phase 3: Graphics, Audio and Gameplay Compatibility

**Status: Planned**

- Implement and validate rendering and audio functionality.
- Investigate gameplay issues and missing platform behavior.
- Expand testing across scenes, systems and progression.
- Profile performance and address correctness and stability issues.

### Phase 4: PC Features and Installation

**Status: Planned**

- Design a local installation and preparation workflow.
- Evaluate display resolution, presentation and input configuration improvements.
- Implement suitable quality-of-life features without compromising compatibility.
- Prepare documentation and compatibility-testing procedures.

### Phase 5: Public Testing and Source Release

**Status: Planned**

- Publish source code and build instructions when the project reaches an appropriate stage.
- Provide test builds only when ready for meaningful public testing.
- Establish public bug-reporting and contribution processes.
- Continue improvements based on verified test results.

**No dates are attached to these phases.** They are planning categories rather than commitments to a schedule.

## Current Priorities

The immediate priority remains the ongoing work on [Xenoblade Chronicles Recompiled](https://github.com/Glitxhhh/XenobladeChroniclesRecompiled). Research and technical planning for Xenosaga Recompiled may be undertaken ahead of active development, but no development timeline has been set.

## Community & Contributing

This GitHub repository is the official home for this planned project. Project-specific updates and contribution instructions will be added as development begins.

For now, the most useful support is careful technical research, documentation and experience with recompilation or the original platform. **There is currently no public codebase or build for contributors to test.**

If you are an experienced programmer or reverse engineer and would like to discuss future contributions, contact **[@Glitxhhh](https://github.com/Glitxhhh)**.

Contributors will be expected to follow the established technical direction, review their changes, test their implementations and take responsibility for submitted code. AI coding assistance is acceptable when its output is understood and independently reviewed; unreviewed generated changes are not.

## What to Expect

This repository will remain a source of project information until there is substantive development work to publish.

- No public build, installer or release date is available.
- Technical plans and proposed features are subject to research and validation.
- Future updates will distinguish tested achievements from planned functionality.
- The intended installation process will rely on the user's own legally obtained game files.

**This project does not distribute copyrighted games, game assets, firmware, encryption keys or other protected material. Users must provide their own legally obtained game files.**

## Support Me

I develop my projects in my free time alongside other responsibilities. If you enjoy following my work and want to support me as an individual developer, voluntary personal donations are appreciated.

### Donation Methods

[![Ko-fi](https://img.shields.io/badge/Ko--fi-donate-ff5e5b.svg?logo=ko-fi&style=for-the-badge)](https://ko-fi.com/glitxh)
[![Patreon](https://img.shields.io/badge/Patreon-donate-f96854.svg?logo=patreon&style=for-the-badge)](https://patreon.bifrosthub.ru/)
[![BTC](https://img.shields.io/badge/BTC-donate-f7931a.svg?logo=bitcoin&style=for-the-badge)](https://www.blockchain.com/explorer/addresses/btc/bc1qnwtms7pp8hdfqnuunvs3juwskgu7tartd532pz)
[![ETH](https://img.shields.io/badge/ETH-donate-3c3c3d.svg?logo=ethereum&style=for-the-badge)](https://etherscan.io/address/0x48240481C69904C35EC41B4f4eBE41Af05D81975)
[![SOL](https://img.shields.io/badge/SOL-donate-9945ff.svg?logo=solana&style=for-the-badge)](https://explorer.solana.com/address/8gLiGa61utSAyqRGy4QtoVzP6BNkL3GjQZZBpuRtY8hK)
[![USDT TRC20](https://img.shields.io/badge/USDT--TRC20-donate-26a17b.svg?logo=tether&style=for-the-badge)](https://tronscan.org/#/address/TDgQTrr4i3ivJQtQpYB5M3nEw92VkAmC6D)

<details>
<summary>Cryptocurrency addresses (click to expand)</summary>

| Network | Address |
| --- | --- |
| Bitcoin (BTC) | `bc1qnwtms7pp8hdfqnuunvs3juwskgu7tartd532pz` |
| Ethereum (ETH) | `0x48240481C69904C35EC41B4f4eBE41Af05D81975` |
| Solana (SOL) | `8gLiGa61utSAyqRGy4QtoVzP6BNkL3GjQZZBpuRtY8hK` |
| Tron (TRX / USDT-TRC20) | `TDgQTrr4i3ivJQtQpYB5M3nEw92VkAmC6D` |

The Ethereum address is also used on compatible networks including Base, Linea, BNB Chain, Polygon, Optimism, Arbitrum, and Arc. Verify that your wallet is using the correct network before making a transfer.

</details>

Donations are voluntary personal gifts to me as an individual developer. They are not payment for the project, a product or a service, and they are not a purchase of, or investment in, the project or any software. They do not give any right to early access, specific features, support, or a release date, and they do not make the project a commercial offering.

## How This Project Will Be Developed

In the interest of transparency, I use LLM coding assistants, including **Claude and Codex**, as tools for research, code generation, debugging and technical analysis on my projects.

I remain responsible for the project's goals, architecture, technical direction, reviewing changes, testing and final implementation decisions. Use of these tools in this project will be disclosed as development proceeds.

**AI assistance does not replace engineering review or testing.**

## License

No project license has been published in this repository yet. Licensing terms for original source code will be documented when code is made available.

Any future license will apply only to the project's own original work and will not grant rights to copyrighted game code, assets, game dumps or third-party dependencies.

---

*Xenosaga Recompiled is an independent, upcoming project by Glitxh. It is not affiliated with or endorsed by the original game's rights holders.*
