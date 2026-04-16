# The Builder's Forge — Creative Thinking Skill for Claude Code

An adaptive creative thinking sparring partner that challenges assumptions, expands your solution space, and helps you produce actionable outputs for work challenges.

## Installation

**Option 1: Via the GrillerGeek marketplace** (recommended)

```bash
claude plugin marketplace add https://github.com/GrillerGeek/skills.git
claude plugin install builders-forge
```

**Option 2: Local testing**

```bash
git clone https://github.com/GrillerGeek/builders-forge.git
claude --plugin-dir ./builders-forge
```

## Usage

The skill activates when you bring a problem to think through. No special command needed — just describe what you're working on:

```
"Help me think through our API migration strategy"
"I'm stuck on how to restructure the team around this new product"
"What if we approached the platform consolidation differently?"
"Challenge my thinking on this vendor decision"
```

## How It Works

The Builder's Forge operates through four adaptive phases. It reads where you are in your thinking and meets you there — you don't march through steps linearly.

| Phase | Purpose | What Happens |
|-------|---------|-------------|
| **FRAME** | Find the real problem | Strips symptoms, challenges assumptions, maps constraints, exposes what's actually fixed vs. what just feels fixed |
| **FORGE** | Expand possibilities | Generates options through cross-domain analogies, constraint flipping, perspective shifts, and systematic exploration of the solution space |
| **STRESS TEST** | Pressure-test ideas | Pre-mortems, devil's advocate, second-order effects analysis, stakeholder reality checks |
| **SHAPE** | Crystallize output | Produces the right deliverable — a quick reframe, clarity + next actions, or a structured decision memo |

### Adaptive Entry Points

You don't always start at FRAME. The skill detects your problem state:

| You come in with... | Skill starts at... |
|---|---|
| A vague sense something's wrong | **FRAME** — deep questioning to surface the real problem |
| A clearly defined problem, need ideas | **FORGE** — straight to possibility generation |
| Two options, can't decide | **STRESS TEST** — pressure-test both, expose hidden tradeoffs |
| A breakthrough moment, need to capture it | **SHAPE** — crystallize before the insight fades |

### Inspiration Spark

When you're stuck or the conversation is going in circles, the skill drops a provocation from a completely unrelated domain — a structural parallel from nature, architecture, military strategy, music, or elsewhere. It doesn't explain the connection. It lets you find the bridge.

## Outputs

Sessions produce one of three output formats, matched to what happened in the conversation:

**Quick Reframe** — When the primary value is a shifted perspective (2-3 sentences)

**Clarity + Next Actions** — When you need a sharpened problem statement and concrete steps

**Decision Memo** — When you need a structured artifact with context, options, recommendation, risks, and next steps

## What It Draws From

The Builder's Forge synthesizes techniques from proven creativity and problem-solving frameworks:

| Framework | How It's Used |
|-----------|---------------|
| First Principles Thinking | FRAME — decompose assumptions, separate facts from conventions |
| Synectics | FORGE — cross-domain analogies from nature, engineering, sports, etc. |
| SCAMPER | FORGE — systematic prompts to evolve existing solutions |
| Morphological Analysis | FORGE — map the full solution space for complex multi-variable problems |
| Constraint-Based Creativity | FORGE — flip limitations into creative advantages |
| Socratic Method | All phases — probing questions adapted to each phase's purpose |
| Pre-Mortem Analysis | STRESS TEST — imagine failure and work backward |
| Forced Connections | Inspiration Spark — random cross-domain provocations when stuck |

## Personality

- **Direct** — no hedging, no filler, no "great question"
- **Substantive** — every challenge has a point, never performative
- **Peer-level** — treats you as a fellow builder, not a student
- **Honest** — won't agree with a flawed idea to be polite

## Plugin Structure

```
builders-forge/
├── .claude-plugin/
│   └── plugin.json              # Plugin manifest
├── skills/
│   └── builders-forge/
│       ├── SKILL.md             # Skill behavior and adaptive flow
│       └── techniques.md        # Technique reference catalog
├── README.md
└── LICENSE                      # Apache 2.0
```

## License

This project is licensed under the [Apache License 2.0](LICENSE).
