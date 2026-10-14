<p align="center">
  <img src="https://raw.githubusercontent.com/Thurbeen/.github/main/figures/thurbeen-emblem.svg" width="360" alt="Thurbeen" />
</p>

<h3 align="center">Several coding agents, side by side in one terminal.</h3>

<p align="center">
  <a href="https://thurbox.thurbeen.eu/">Website</a> ·
  <a href="https://discord.gg/fGumcHaxFY">Discord</a> ·
  <code>brew install thurbeen/thurbox/thurbox</code>
</p>

## 📦 thurbox

**[thurbox](https://github.com/Thurbeen/thurbox)** — TUI for agentic code orchestration, written in Rust. Several coding agents side by side in one terminal, each in a persistent session that survives crashes, restarts and reboots. Install it from **[homebrew-thurbox](https://github.com/Thurbeen/homebrew-thurbox)**.

### 🧩 Plugins

Every pane is a Lua file you own. These add to it:

- **[thurbox-info-panel](https://github.com/Thurbeen/thurbox-info-panel)** — Session, git, agent, account quota and system readouts beside the terminal.
- **[thurbox-code-review](https://github.com/Thurbeen/thurbox-code-review)** — A Review tab beside Agent and Shell: the session's diff against its base branch, with notes sent to the agent.
- **[thurbox-automations](https://github.com/Thurbeen/thurbox-automations)** — A pane for scheduled automations: run, switch, create and edit them, and see why a run failed.
- **[thurbox-auto-continue](https://github.com/Thurbeen/thurbox-auto-continue)** — When a Claude Code session hits its usage limit, waits for the reset and types `continue`, once. No LLM involved.
- **[thurbox-doom](https://github.com/Thurbeen/thurbox-doom)** — DOOM as a tab of the agent pane.

## 🛰️ fleet

**[fleet](https://github.com/Thurbeen/fleet)** — A control plane over thurbox. Give it a goal: it splits it into tasks, runs one worker session per task in the real repository, and hands you back pull requests to review.

## 🧠 Agent skills

- **[publish](https://github.com/Thurbeen/publish)** — Gates committed work before it leaves the machine: adversarial review, tests, lint and docs, then push, open the change request and answer every review.
- **[thurview](https://github.com/Thurbeen/thurview)** — Your coding agent writes the review; you read it in the browser, anchored to the code, and approve it or send it back.

## 🧰 More

- **[gdcruiser](https://github.com/Thurbeen/gdcruiser)** — Static dependency analyzer for Godot: GDScript dependency graphs, cycle detection and architecture rules, ready for CI.
- **[template](https://github.com/Thurbeen/template)** — Starter template for bootstrapping new projects.
