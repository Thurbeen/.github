<p align="center">
  <img src="https://raw.githubusercontent.com/Thurbeen/.github/main/figures/thurbeen-emblem.svg" width="360" alt="Thurbeen" />
</p>

<h3 align="center">Several coding agents, side by side in one terminal.</h3>

<p align="center">
  <a href="https://thurbox.thurbeen.eu/">Website</a> ·
  <a href="https://discord.gg/fGumcHaxFY">Discord</a> ·
  <a href="https://thurbox.thurbeen.eu/docs/installation.html">Install</a>
</p>

## 📦 thurbox

**[thurbox](https://github.com/Thurbeen/thurbox)** — TUI for agentic code orchestration, written in Rust. Several coding agents side by side in one terminal, each in a persistent session that survives crashes, restarts and reboots.

```bash
# Linux / macOS
curl -fsSL https://raw.githubusercontent.com/Thurbeen/thurbox/main/scripts/install.sh | sh
```

```powershell
# Windows (PowerShell)
irm https://raw.githubusercontent.com/Thurbeen/thurbox/main/scripts/install.ps1 | iex
```

### 🧩 Plugins

Every pane is a Lua file you own. These add to it:

- **[thurbox-info-panel](https://github.com/Thurbeen/thurbox-info-panel)** — Session, git, agent, account quota and system readouts beside the terminal.
- **[thurbox-code-review](https://github.com/Thurbeen/thurbox-code-review)** — A Review tab beside Agent and Shell: the session's diff against its base branch, with notes sent to the agent.
- **[thurbox-automations](https://github.com/Thurbeen/thurbox-automations)** — A pane for scheduled automations: run them, switch them on or off, create and edit them, and see why a run failed.
- **[thurbox-auto-continue](https://github.com/Thurbeen/thurbox-auto-continue)** — When a Claude Code session hits its usage limit, waits for the reset and types `continue`, once. No LLM involved.
- **[thurbox-fleetlens](https://github.com/Thurbeen/thurbox-fleetlens)** — Fleet Lens: browse Fleet v2 resources, Tasks first, in one keyboard-first float.
- **[thurbox-doom](https://github.com/Thurbeen/thurbox-doom)** — DOOM as a tab of the agent pane.

## 🛰️ fleet

**[fleet](https://github.com/Thurbeen/fleet)** — Runs one AI agent session per Task: it spawns the session in its own workspace, sends the brief once, records the worker's result and releases the session. One Linux binary, written in Rust.

- **[vega](https://github.com/Thurbeen/vega)** — VEGA, the Mission Control workspace bundled with Fleet. It only routes and steers: every deliverable runs in a worker Task of its own.
- **[agent-observability](https://github.com/Thurbeen/agent-observability)** — Grafana dashboards, Prometheus alerts and an OpenTelemetry quick-start for Fleet and Thurbox.

## 🧠 Agent skills

- **[publish](https://github.com/Thurbeen/publish)** — Gates committed work before it leaves the machine: adversarial review, tests, lint and docs, then push, open the change request and answer every review.
- **[thurview](https://github.com/Thurbeen/thurview)** — Your coding agent writes the review; you read it in the browser, anchored to the code, and approve it or send it back.

## 🧰 More

- **[gdcruiser](https://github.com/Thurbeen/gdcruiser)** — Static dependency analyzer for Godot: GDScript dependency graphs, cycle detection and architecture rules, ready for CI.
- **[template](https://github.com/Thurbeen/template)** — Starter template for bootstrapping new projects.
