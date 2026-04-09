# Superteam Copilot

AI agent skill for the Solana Frontier Hackathon ecosystem. Helps builders navigate the main Colosseum hackathon, Superteam Earn side tracks, Colosseum Copilot research tool, and Superteam country chapters — all from your coding assistant.

## Install

```bash
npx skills add superteam-copilot
```

## What it does

- **Main Frontier Hackathon** — prizes ($200k pool), timeline, how to register, accelerator opportunity
- **Superteam side tracks** — browse and filter all ecosystem/chapter tracks on Superteam Earn, sorted by prize
- **Track details** — full submission requirements, evaluation criteria, deadlines, and eligibility for any specific track
- **Colosseum Copilot** — explains the research tool for validating hackathon ideas (5,400+ submissions, 84k+ archive docs, competitor analysis)
- **Country chapters** — all 23 Superteam regional communities with social links

## Frontier Hackathon at a glance

| | |
|---|---|
| **Main event** | [colosseum.com/frontier](https://colosseum.com/frontier) |
| **Register** | [arena.colosseum.org/hackathon](https://arena.colosseum.org/hackathon) |
| **Total prizes** | $200,000 |
| **Grand Champion** | $30,000 |
| **Deadline** | May 11, 2026 |
| **Side tracks** | [superteam.fun/earn/hackathon/frontier](https://superteam.fun/earn/hackathon/frontier) |

## Side tracks

Superteam Earn hosts **ecosystem submission tracks** that run alongside the main Colosseum hackathon. There are two types:

- **Country chapter tracks** — run by Superteam regional chapters (Georgia, India, Nigeria, Japan, Malaysia, etc.), typically 10,000 USDG
- **Ecosystem partner tracks** — run by Solana projects (Adevar Labs, Eitherway, Dune, Umbra, 100xDevs, etc.)

Builders can submit to both the main Colosseum hackathon and multiple Superteam side tracks simultaneously.

## Colosseum Copilot (research tool)

[Colosseum Copilot](https://docs.colosseum.com/copilot/introduction) is a separate research skill that turns your AI assistant into a Solana startup analyst:

- Search 5,400+ hackathon project submissions to find competitors
- Query 84,000+ archive documents (cypherpunk literature, investor research, Solana protocol docs)
- Analyze trends across past hackathons (Renaissance, Radar, Breakout, Cypherpunk)
- Two modes: conversational (quick answers) and deep dive (8-step idea validation)

```bash
# Set up Colosseum Copilot separately
export COLOSSEUM_COPILOT_PAT="your-token-here"
npx skills add ColosseumOrg/colosseum-copilot
```

Get a PAT at [arena.colosseum.org/copilot](https://arena.colosseum.org/copilot).

## Superteam chapters

23 regional communities worldwide. Key chapters by region:

| Region | Chapters |
|--------|----------|
| Southeast Asia | Indonesia, Singapore, Malaysia |
| East Asia / Pacific | Japan, Korea, Australia |
| South Asia | India |
| Europe | Germany, UK, Netherlands, Poland, Ukraine, Georgia, Turkey, Ireland, Balkan, La Familia (Spain) |
| Americas | USA, Canada, Brazil |
| Middle East | UAE |
| Central Asia | Kazakhstan |
| Africa | Nigeria |

## Skill structure

```
skills/superteam-copilot/
├── SKILL.md              — main skill instructions
└── references/
    └── countries.md      — all 23 Superteam chapters (no API call needed)
```

## Links

| Resource | URL |
|----------|-----|
| Frontier Hackathon | https://colosseum.com/frontier |
| Register | https://arena.colosseum.org/hackathon |
| Superteam side tracks | https://superteam.fun/earn/hackathon/frontier |
| Colosseum Copilot docs | https://docs.colosseum.com/copilot/introduction |
| Superteam | https://superteam.fun |
