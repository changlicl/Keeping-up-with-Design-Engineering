# Keeping up with Design Engineering

> An AI-powered daily brief that filters the most relevant AI, Product Design, and Design Engineering updates from public X accounts into one actionable Markdown report.

---

## Why this project?

Every day, hundreds of valuable ideas are shared across X, but finding the few that actually matter takes hours.

This project is built for designers who want to stay current without constantly scrolling social media.

Instead of reading everything, the system filters public posts and generates one concise Markdown brief focused on:

- AI
- Product Design
- Design Engineering
- AI workflows
- Portfolio inspiration
- Case studies
- Interview preparation

The goal is simple:

> Spend less time scrolling. Spend more time learning.

---

## Features

- Curated public X sources
- 48-hour rolling summaries
- AI-generated insights
- Original post links
- Relevance-based ranking
- Clean Markdown output
- Zero manual curation

---

## Example Output

```text
briefs/

2026-07-30.md
```

Each report contains:

- Today's Signal
- Top Stories
- AI Engineering
- Product Design
- Design Engineering
- Portfolio & Career
- Worth Opening
- Today's Takeaway

---

## Project Structure

```

keeping-up-with-design-engineering/

├── PROJECT.md
├── README.md
├── feeds.yaml
├── prompts/
│ └── daily-brief.md
├── briefs/
└── src/

```

---

## How It Works

```

Public X Accounts

↓

Collect Posts (48 hours)

↓

Remove Noise

↓

Rank by Relevance

↓

Generate AI Summary

↓

Output Markdown Brief

```

---

## Current Scope (V1)

Included

- Public X accounts
- Markdown reports
- AI summaries
- Original post links
- Relevance ranking

Not Included

- Images
- Screenshots
- Notion integration
- LinkedIn
- GitHub
- YouTube
- Website UI

---

## Example Workflow

```

npm install

npm run generate

```

Output:

```

briefs/
2026-07-30.md

```

---

## Configuration

All tracked sources are stored in

```

feeds.yaml

```

Categories include:

- AI
- Product Design
- Design Engineering
- Design Tools
- Companies
- Founders
- Creative Technology

Adding a new source should only require updating this file.

---

## Roadmap

### V1

- Public X accounts
- Markdown reports

### V2

- GitHub Releases
- Open-source projects

### V3

- Company engineering blogs

### V4

- LinkedIn hiring insights

### V5

- YouTube talks and conference videos

### V6

- Notion export
- Web dashboard

---

## Philosophy

This project is **not** a news aggregator.

It is a signal filter.

Rather than collecting everything, it identifies the small number of updates that are most useful for designers building AI products.

---

## License

MIT
