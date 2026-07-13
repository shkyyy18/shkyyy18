<div align="center">

# Practical, local-first automation

I turn recurring operational pain into small open-source tools with clear failure modes, offline defaults, reproducible demos, and honest scope.

[OpenBid Intel demo](https://shkyyy18.github.io/openbid-intel/) | [Flagship projects](#flagship-projects) | [Engineering principles](#engineering-principles)

</div>

## Flagship projects

<table>
<tr>
<td width="50%" valign="top">

### [OpenBid Intel](https://github.com/shkyyy18/openbid-intel)

**Rank public tender notices into explainable sales opportunities, locally.**

- reusable industry profile packs and multi-profile routing
- CSV, JSON, JSONL, RSS/Atom, and conservative connector architecture
- SQLite history, feedback calibration, CRM export, digest, and portable dashboard
- **104 offline tests**, Linux/Windows CI, zero runtime dependencies

[Live synthetic demo](https://shkyyy18.github.io/openbid-intel/) | [30-second quick start](https://github.com/shkyyy18/openbid-intel#30-second-quick-start) | [Contribute](https://github.com/shkyyy18/openbid-intel/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)

[![CI](https://github.com/shkyyy18/openbid-intel/actions/workflows/tests.yml/badge.svg)](https://github.com/shkyyy18/openbid-intel/actions/workflows/tests.yml)
[![Release](https://img.shields.io/github/v/release/shkyyy18/openbid-intel)](https://github.com/shkyyy18/openbid-intel/releases/latest)
[![Stars](https://img.shields.io/github/stars/shkyyy18/openbid-intel?style=social)](https://github.com/shkyyy18/openbid-intel)

</td>
<td width="50%" valign="top">

### [AgentCron](https://github.com/shkyyy18/cc-autopilot)

**Cron plus a watchdog for unattended AI coding agents.**

- Codex, Gemini CLI, and custom commands
- retries, timeout, process-tree cleanup, and silent-failure detection
- structured local logs and privacy-safe webhook failure notifications
- Windows Task Scheduler plus Linux/macOS cron; zero runtime dependencies

[30-second quick start](https://github.com/shkyyy18/cc-autopilot#30-second-quick-start) | [Notifications](https://github.com/shkyyy18/cc-autopilot/blob/main/docs/notifications.md) | [Contribute](https://github.com/shkyyy18/cc-autopilot/issues)

[![CI](https://github.com/shkyyy18/cc-autopilot/actions/workflows/ci.yml/badge.svg)](https://github.com/shkyyy18/cc-autopilot/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/shkyyy18/cc-autopilot)](https://github.com/shkyyy18/cc-autopilot/releases/latest)
[![Stars](https://img.shields.io/github/stars/shkyyy18/cc-autopilot?style=social)](https://github.com/shkyyy18/cc-autopilot)

</td>
</tr>
</table>

## Labs

### [Personal Health Sync](https://github.com/shkyyy18/personal-health-sync)

A cross-platform, vendor-neutral local observation store with generic CSV import, a no-hardware synthetic demo, portable HTML reporting, and optional Strava/Xiaomi connectors. Apple Health, Health Connect, Huawei, and Garmin adapters are roadmap items, not claimed as complete.

### [AI Money Lab](https://github.com/shkyyy18/ai-money-lab)

An evidence ledger for small AI business experiments. Machine-readable manifests and CI keep status, dates, evidence levels, and revenue claims consistent. The first experiment is explicitly **inconclusive** because a local self-test is not market validation.

## Current external signal

AgentCron received the portfolio's first outside fork and code contribution. The webhook notification adapter was reviewed through isolated GitHub Actions, merged with contributor credit, and then security-hardened for the next release.

## Engineering principles

- useful before complicated;
- local-first where privacy or portability matters;
- synthetic demos before credentials or hardware;
- tests and CI on the platforms users actually run;
- explicit limits instead of pretending roadmap features already exist;
- external contributions reviewed, tested, and credited.

If a project fits your workflow, run its quick start and open an issue describing the real failure mode you want solved.
