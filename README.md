# TopofMind.AI — Hermes Agent Skills

Open-source skills for [Hermes Agent](https://github.com/NousResearch/hermes-agent) by [Keith Motte](https://topofmind.ai) @ **TopofMind.AI**.

## Install

Add this repo as a skill tap in Hermes:

```bash
hermes skills tap add chasbottle-del/topofmind-hermes-skills
```

Then install any skill:

```bash
hermes skills install hermes-architecture-diagram
```

## Available Skills

### hermes-architecture-diagram (v2.0.0)

Auto-generates verified architecture visualizations of your Hermes Agent install. Discovers your OS, terminal backend, model, and provider — then produces output in your choice of four formats:

| Format | Output | Best For |
|--------|--------|----------|
| **A: SVG/HTML** | Interactive diagram in browser | Documentation, READMEs, quick reference |
| **B: AI Image** | High-fidelity illustration via image_generate | Presentations, social media, pitch decks |
| **C: Animated HTML** | GSAP-powered step-by-step walkthrough | Demos, onboarding, live presentations |
| **D: HyperFrames MP4** | Deterministic video via HeyGen's open-source framework | YouTube, content marketing, investor decks |

Every format includes a **Bar Raiser verification gate** — an AWS-inspired quality check that ground-truths every claim in the output against your live system. Zero hallucinations.

**Features:**
- Auto-detects OS, terminal backend, model, provider, username
- Two-zone (local backend) or three-zone (remote backend) topology
- Supports all backends: local, modal, docker, ssh, singularity, daytona
- Works on macOS, Linux, Windows/WSL
- Bundled scripts: `discover-env.sh` and `bar-raiser.sh`

## About TopofMind.AI

We build AI automation systems that actually work. Skills, services, and tooling for businesses that want AI agents doing real work — not demos.

- **Website:** [topofmind.ai](https://topofmind.ai)
- **Author:** Keith Motte
- **License:** MIT

## Contributing

PRs welcome. All skills include a Bar Raiser verification step — if it can't be verified against reality, it doesn't ship.
