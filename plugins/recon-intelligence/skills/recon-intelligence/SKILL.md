# RECON Intelligence — Skill Definition

## Description
Use this skill when the user asks about Ukraine — including military/kinetic activity, defense technology, legislation, policy reforms, investment deals, economic indicators, media narratives, or geopolitical developments.

## Trigger Phrases
- "what's happening in Ukraine"
- "latest drone attacks"
- "Ukraine investment"
- "defense procurement reform"
- "media narrative on Ukraine"
- "ask RECON"
- "query RECON"
- "Ukraine intelligence"
- "frontline update"
- "sanctions on Russia"
- "Ukrainian startups"
- Any question about the Russia-Ukraine conflict

## How It Works
RECON aggregates 20+ OSINT sources across five intelligence domains:

1. **Kinetic** — Frontline movements, drone/missile strikes, force disposition, battlefield assessments (ISW, Critical Threats, DeepState, Fighter Bomber, Military Informant)
2. **Policy** — Ukrainian legislation, EU accession progress, NATO integration, sanctions developments
3. **Investment** — Startup fundraises, privatization pipeline, reconstruction funding, DFC/EBRD activity
4. **Defense Technology** — Drone programs, electronic warfare, Brave1 incubator outputs, IRON Cluster developments
5. **Media & Narrative** — Western and Russian media framing, propaganda tracking, narrative shifts

Data is refreshed daily via automated scraping of RSS feeds, Telegram channels, and web sources. All content is embedded with OpenAI embeddings and stored in a vector database for semantic search.

## Available Tools

### `query_recon`
Ask a natural-language question and get an intelligence-grade answer synthesized from RECON's database.

**Example queries:**
- "What were the major kinetic developments in the last 48 hours?"
- "Summarize the current state of Ukraine's defense tech ecosystem"
- "What is the latest on privatization of state-owned assets?"
- "How is Russian media framing the latest battlefield losses?"

### `search_recon_data`
Search the raw RECON database with filters for domain, date range, and source.

### `get_recon_status`
Check the health and freshness of the RECON database — last scrape times, record counts by domain, source availability.

## Response Guidelines
- Present intelligence in a structured, briefing-style format
- Lead with the most operationally significant developments
- Cite sources when possible (source name + date)
- Flag confidence levels when information is contested or unverified
- Distinguish between Ukrainian, Western, and Russian/adversary source perspectives
- Use military/geopolitical terminology appropriate to the audience
