# Startup Idea Validator

A free, open-source AI skill that validates any startup idea with a **VC-grade 7-dimension scorecard** — the same framework real investors use to evaluate seed-stage companies.

Describe your idea in a few sentences. Get back a weighted score, honest strengths/risks analysis, and a concrete next step.

## What You Get

- **7-dimension weighted scorecard** with evidence-backed rationales
- **Weighted total score** (X.X / 10) with investment priority rating (Strong / Promising / Weak / Pass)
- **Key strengths** — what's working in your favor
- **Critical risks** — with early warning signals and mitigation tactics
- **7-day action item** — one specific thing to do this week
- **Adaptive research** — uses web search when available, falls back to LLM knowledge gracefully
- **Multi-language** — responds in whatever language you use

## Scoring Dimensions

| Dimension | Weight | What It Evaluates |
|-----------|--------|-------------------|
| **Market** | 25% | TAM/SAM/SOM, growth rate, why now |
| **Founder-Market Fit** | 25% | Domain expertise, unique advantages, network |
| **Problem-Solution Fit** | 15% | Pain severity, differentiation, willingness to pay |
| **Competition** | 10% | Landscape, moat potential, whitespace |
| **Business Model** | 10% | Unit economics, pricing power, path to profit |
| **Go-to-Market** | 10% | Path to first 100 customers, channel feasibility |
| **Execution Risk** | 5% | Buildability, capital needs, time to MVP |

Weights reflect actual seed-stage VC priorities: **Market + Founder-Market Fit = 50%** because investors bet on big markets and strong teams above all else.

## Install

### Claude Code

```bash
# Clone the repo
git clone https://github.com/VibeCom-AI/startup-idea-validator.git

# Copy to your skills directory (personal)
cp -r startup-idea-validator ~/.claude/skills/

# Or add to a project (shared with team)
cp -r startup-idea-validator .claude/skills/
```

### Cursor / Windsurf / Other AI IDEs

Copy the contents of `SKILL.md` into your AI rules or system instructions.

### Manual

Just paste the content of `SKILL.md` into any AI chat as context before describing your idea.

## Usage

Once installed, just describe your startup idea:

> "I want to build an AI tool that helps solo founders validate their startup ideas before writing any code"

The skill triggers automatically and returns a full scorecard analysis.

## Example Output

```
# Startup Validation: IdeaCheck AI

## Executive Summary

This is a **Promising** idea. The startup validation space has proven
demand ($2B+ market), but competition from established players like
CB Insights and Crunchbase means differentiation through AI-native
UX and speed is critical.

## VC Scorecard

| Dimension            | Weight | Score | Rationale                                          |
|----------------------|--------|-------|----------------------------------------------------|
| Market               | 25%    | 7/10  | $2.4B market research TAM, 12% CAGR                |
| Founder-Market Fit   | 25%    | 5/10  | No domain expertise provided                       |
| Problem-Solution Fit | 15%    | 8/10  | 42% of startups fail from no market need (CB)      |
| Competition          | 10%    | 5/10  | Crowded: DimeADozen, Validator AI, Founderpal       |
| Business Model       | 10%    | 7/10  | Freemium SaaS proven in category, $20-50/mo range  |
| Go-to-Market         | 10%    | 7/10  | Indie hacker communities + Product Hunt launch      |
| Execution Risk       | 5%     | 8/10  | LLM wrapper, MVP in 2-4 weeks                      |

**Weighted Score: 6.6 / 10 — PROMISING**
```

## Built by VibeCom

This skill is created by [VibeCom](https://vibecom.app) — an AI-powered startup advisor that gives founders VC-grade validation in minutes.

VibeCom's full platform goes deeper with:

- **Real-time competitor research** — detailed profiles with pricing, positioning, and threat analysis
- **TAM/SAM/SOM market sizing** — with cited sources and methodology
- **Customer discovery** — ICP analysis, pain points, buying triggers
- **AI PRD generator** — production-ready product specs for vibe coding
- **Go-to-market strategy** — 90-day launch playbook with channel tactics
- **Business plans** — investor-ready docs for YC and fundraising

Try it free at **[vibecom.app](https://vibecom.app)**

## Contributing

Contributions welcome! Feel free to open issues or submit PRs.

## License

MIT
