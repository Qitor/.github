# QitOS

Open-source infrastructure for agent-native research, AI safety evaluation, and trustworthy autonomous systems.

## What We Build

QitOS is a research-driven open-source organization building composable tools for the AI agent ecosystem. Our focus:

- **Agent-native research infrastructure** — frameworks designed around the agent lifecycle, not web scaffolding
- **Safety evaluation and risk discovery** — reproducible benchmarks, signal detection, and forensics for frontier AI
- **Reusable open-source tooling** — small composable kernels over monolithic platforms
- **Research-friendly defaults** — observability, replay, and reproducibility built in from the start

We build frameworks, not products. Everything is designed to be inspected, extended, and recomposed.

## Featured Projects

<table>
<tr>
<td width="50%">

### [qitos](https://github.com/Qitor/qitos)

[![Stars](https://img.shields.io/github/stars/Qitor/qitos?style=social)](https://github.com/Qitor/qitos)
[![PyPI](https://img.shields.io/pypi/v/qitos.svg)](https://pypi.org/project/qitos/)
[![License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/Qitor/qitos/blob/main/LICENSE)

The torch-flavor framework for agent researchers. One `AgentModule + Engine` kernel with built-in `qita` observability.

**Status:** Core Framework &nbsp;·&nbsp; Agent orchestration · Benchmark harness · Trajectory inspection

[Docs](https://qitor.mintlify.app/) · [Quickstart](https://qitor.mintlify.app/quickstart)

</td>
<td width="50%">

### [snowl](https://github.com/Qitor/snowl)

[![Stars](https://img.shields.io/github/stars/Qitor/snowl?style=social)](https://github.com/Qitor/snowl)
[![Python](https://img.shields.io/badge/python-%3E%3D3.10-blue)](https://github.com/Qitor/snowl)

A safety evaluation framework for AI agents. Reproducible, observable, and retryable evaluations across benchmarks and environments.

**Status:** Core Framework &nbsp;·&nbsp; Safety evaluation · Benchmark adapters · Risk analysis

[Docs](https://qitor.github.io/snowl)

</td>
</tr>
<tr>
<td width="50%">

### [qitos-zoo](https://github.com/Qitor/qitos-zoo)

[![Stars](https://img.shields.io/github/stars/Qitor/qitos-zoo?style=social)](https://github.com/Qitor/qitos-zoo)
[![Python](https://img.shields.io/badge/python-3.10%2B-3776AB)](https://github.com/Qitor/qitos-zoo)

Applications and showcase agents built with QitOS. Demonstrates how the core framework powers real agent systems.

**Status:** Zoo &nbsp;·&nbsp; Showcase agents · Application templates · QitOS integration examples

</td>
<td width="50%">

### [EyeHermes](https://github.com/Qitor/EyeHermes)

[![Stars](https://img.shields.io/github/stars/Qitor/EyeHermes?style=social)](https://github.com/Qitor/EyeHermes)
[![Python](https://img.shields.io/badge/python-3.10%2B-3776AB)](https://github.com/Qitor/EyeHermes)

An AIGC forensics agent for detecting AI-generated content. Multi-modal analysis with evidence-backed verdicts and reproducible reports.

**Status:** Research Tooling &nbsp;·&nbsp; AIGC forensics · Evidence analysis · Multi-modal detection

</td>
</tr>
</table>

## Principles

- **Research-first, production-aware** — Designed for researchers who need observability and reproducibility, not just demo scaffolding.
- **Composable by design** — Small kernels that compose. No framework lock-in, no hidden orchestration.
- **Safety and evaluation built in** — Benchmarks, signal detection, and forensics are first-class concerns, not afterthoughts.
- **Minimal core, rich ecosystem** — The core stays small. Applications and domain agents live outside it.
- **Open benchmarks and reproducible experiments** — Every run leaves a trace. Every evaluation can be replayed.

## Get Started

| Resource | Link |
|----------|------|
| QitOS Framework | [github.com/Qitor/qitos](https://github.com/Qitor/qitos) |
| QitOS Docs | [qitor.mintlify.app](https://qitor.mintlify.app/) |
| Safety Evaluation | [github.com/Qitor/snowl](https://github.com/Qitor/snowl) |
| Agent Zoo | [github.com/Qitor/qitos-zoo](https://github.com/Qitor/qitos-zoo) |
