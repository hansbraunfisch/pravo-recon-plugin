# /recon — Ask RECON about Ukraine Intelligence

Ask RECON a natural-language question about Ukraine. Returns an intelligence-grade briefing synthesized from 20+ OSINT sources across kinetic, policy, investment, defense technology, and media domains.

## Usage
```
/recon What were the major kinetic developments this week?
/recon Summarize Ukraine's defense tech investment landscape
/recon How is Russian state media covering the latest counteroffensive?
```

## Instructions
1. Take the user's question and pass it to the `query_recon` tool
2. Present the response in a structured briefing format
3. Cite sources where available
4. Flag any contested or low-confidence information
