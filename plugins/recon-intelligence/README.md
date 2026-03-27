# RECON Intelligence Plugin for Claude

**Real-time Ukraine intelligence powered by 20+ OSINT sources, satellite imagery analysis, and AI synthesis.**

Built by [Pravo Ventures](https://recon.pravoventures.com) — democratizing access to intelligence-grade analysis on Ukraine's military, economic, and political landscape.

---

## What You Get

Ask Claude about Ukraine and get structured, sourced intelligence briefings across five domains:

- **Kinetic** — Frontline updates, drone/missile strikes, force movements, battlefield assessments
- **Policy** — Legislation, EU/NATO integration, sanctions, diplomatic developments
- **Investment** — Startup deals, privatization pipeline, reconstruction funding, economic indicators
- **Defense Technology** — Drone programs, EW systems, defense incubator outputs
- **Media & Narrative** — Cross-source narrative analysis spanning Western and Russian media

## Installation

```bash
# Add the Pravo RECON marketplace
/plugin marketplace add pravoventures/recon-marketplace

# Install the RECON Intelligence plugin
/plugin install recon-intelligence
```

## Setup

You'll need a RECON API key. Get one at [recon.pravoventures.com](https://recon.pravoventures.com).

Set your API key as an environment variable:

```bash
export RECON_API_KEY=pravo_sk_your_key_here
```

## Commands

| Command | Description |
|---------|-------------|
| `/recon <question>` | Ask RECON any question about Ukraine |
| `/recon-status` | Check database health and data freshness |

## Example Queries

```
/recon What were the major kinetic developments in the last 48 hours?
/recon Summarize the current state of Ukraine's defense tech ecosystem
/recon What is the latest on privatization of state-owned assets?
/recon How is Russian media framing the latest battlefield losses?
```

## Data Sources

RECON aggregates from 20+ sources including ISW, Critical Threats (AEI), DeepState, Ukrinform, Kyiv Independent, Defense Express, Brave1, Fighter Bomber, Military Informant, and more. Data is refreshed daily.

## License

MIT

## About Pravo Ventures

Pravo Ventures democratizes direct reinvestment into Ukraine's entrepreneurial ecosystem, giving Western allies a stake in Ukraine's success. Learn more at [pravoventures.com](https://pravoventures.com).
