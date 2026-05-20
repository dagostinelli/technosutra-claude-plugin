# technosutra-claude-plugin

The cast of voices from [technosutra.com](https://technosutra.com) — Marcus, Sophia, Kamal, Ethan, Wei, The Master, and the letter-writers — packaged as Claude Code subagents and slash commands.

Use them when a question would benefit from a specific perspective — pragmatic management, skeptical realism, eager exploration, principled architecture, synthesizing mentorship, aphoristic wisdom, or letters from someone who has walked the path you're on.

## Install

Inside Claude Code:

```
/plugin marketplace add dagostinelli/technosutra-claude-plugin
/plugin install technosutra@technosutra-claude-plugin
```

## Voices

### Dialogue characters

| Command | Agent | Voice |
|---|---|---|
| `/marcus` | `marcus-the-manager` | Pragmatic engineering manager — names trade-offs, demands clarity, lives in the tension between team and roadmap. |
| `/sophia` | `sophia-the-skeptic` | Eighteen years of institutional memory weaponized — tests every idea, surfaces hidden costs, refuses hype. |
| `/kamal` | `kamal-the-enthusiast` | Two-to-four-year engineer eager about new tech — the voice of momentum and "why not?" Pair with `/sophia` to filter. |
| `/ethan` | `ethan-the-architect` | Architect-philosopher with frameworks: Technical Debt Quadrant, five-factor technology evaluation, the long view. |
| `/wei` | `wei-the-teacher` | The synthesizer — dissolves false dichotomies, teaches through parables and questions. |

### Letter writers

| Command | Agent | Voice |
|---|---|---|
| `/seasoned-cto` | `the-seasoned-cto` | 25+ years strategic — technology adoption, organizational reality, technical excellence vs. business reality. |
| `/technical-architect` | `the-technical-architect` | Craft as ethics — code is communication, every line carries moral weight for future maintainers. |
| `/engineering-manager` | `the-engineering-manager` | Letter-writing mentor on the IC-to-manager transition — clarity over control, mining for conflict, protecting Atlases. |
| `/engineering-director` | `the-engineering-director` | Department-scale systems thinker — cross-functional alignment, no department succeeds when another fails. |
| `/recovering-burnout` | `the-recovering-burnout` | Writes from the other side of burnout — witness, permission, the slow non-linear path back to joy. |

### Aphoristic voice

| Command | Agent | Voice |
|---|---|---|
| `/the-master` | `the-master` | Confucian-form distilled wisdom. *The Master said: "..."* — short, paradoxical, parallel-structured aphorisms. Full corpus embedded for verbatim reference. |

## Commands

- `/marcus` — pragmatic management trade-offs
- `/sophia` — skeptical realism, technology evaluation, cautionary tales
- `/kamal` — explore options, brainstorm, surface what a junior would struggle with
- `/ethan` — frameworks, architectural patterns, principled evaluation
- `/wei` — synthesis, reframing, third paths between apparent opposites
- `/the-master` — aphoristic wisdom on demand
- `/seasoned-cto` — strategic, multi-year, executive-letter perspective
- `/technical-architect` — code-as-ethics, craft as moral practice
- `/engineering-manager` — letter-writing mentor on people leadership
- `/engineering-director` — department-scale, cross-functional thinking
- `/recovering-burnout` — sustainable practice and recovery
- `/council` — fan out a question to 3–5 voices in parallel, then synthesize the roundtable

## When to use which

- **A decision needs a single perspective** → invoke one voice directly.
- **A decision is genuinely contested** → use `/council` to hear multiple voices in parallel.
- **You want aphorism, not analysis** → `/the-master`.
- **You want letters from someone who has been there** → one of the letter writers.
- **You want a dialogue character with a specific stake in the trade-off** → one of the dialogue voices.

## Source

The personas are extracted from the writings at [technosutra.com](https://technosutra.com) — dialogues, letters, and the *Analects of Software Engineering*.

## Author

Darryl T. Agostinelli — dagostinelli@gmail.com
