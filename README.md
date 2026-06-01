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

| Skill | Description |
|-------|-------------|
| **hermes-architecture-diagram** | Auto-generates a verified HTML/SVG architecture diagram of your Hermes Agent install. Discovers your OS, terminal backend, model, and provider — then produces a dark-themed interactive visualization with a Bar Raiser verification gate that ground-truths every claim against your live system. Zero hallucinations. |

## About TopofMind.AI

We build AI automation systems that actually work. Skills, services, and tooling for businesses that want AI agents doing real work — not demos.

- **Website:** [topofmind.ai](https://topofmind.ai)
- **Author:** Keith Motte
- **License:** MIT

## Contributing

PRs welcome. All skills include a Bar Raiser verification step — if it can't be verified against reality, it doesn't ship.
