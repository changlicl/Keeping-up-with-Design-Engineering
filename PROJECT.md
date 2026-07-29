# PROJECT.md

# Keeping up with Design Engineering

> An AI-powered daily brief that filters the most relevant AI, Product Design, and Design Engineering updates into one actionable Markdown report.

---

# 1. Overview

## Goal

The goal of this project is **not** to summarize Twitter/X.

The goal is to help product designers and design engineers quickly understand what actually matters in the AI industry without spending hours scrolling social media.

Instead of consuming hundreds of posts every day, the system filters public content and produces one concise Markdown report.

The report should help with:

- Portfolio rebuilding
- Case study writing
- Interview preparation
- AI knowledge
- Design Engineering knowledge
- Product thinking
- Understanding how AI impacts designers

---

# 2. Problem

Currently, most information is scattered across:

- X
- LinkedIn
- YouTube
- Company blogs
- Podcasts
- GitHub

Finding valuable information requires reading hundreds of posts.

Most posts are:

- repetitive
- promotional
- unrelated
- low quality

The user only wants information that directly contributes to becoming a better Product Designer or Design Engineer.

---

# 3. Target User

Primary User:

Product Designers

Design Engineers

New Grad Designers

UX Designers learning AI

---

# 4. Success Metrics

A successful daily brief should allow the user to understand the previous 48 hours of important discussions in less than 15 minutes.

The user should rarely feel the need to manually browse X afterwards.

---

# 5. V1 Scope

Version 1 intentionally stays very small.

Included:

✅ Public X accounts

✅ Past 48 hours

✅ Markdown output

✅ Original post links

✅ AI summaries

✅ Relevance ranking

Excluded:

❌ Images

❌ Screenshots

❌ Videos

❌ Authentication

❌ Notion integration

❌ Website

❌ LinkedIn

❌ YouTube

❌ GitHub

---

# 6. Sources

Input:

feeds.yaml

Each feed contains:

- account
- category
- priority

Only public accounts are supported.

---

# 7. Ranking Logic

The system should NOT rank only by likes.

Each post should receive a relevance score.

Factors include:

- Engagement
- Source Priority
- Novelty
- Relevance to Product Design
- Relevance to AI
- Relevance to Design Engineering
- Portfolio usefulness
- Interview usefulness

Large accounts should not automatically dominate rankings.

---

# 8. Categories

Every selected post should belong to one category.

Examples:

AI

AI Engineering

Product Design

Design Engineering

Design Tools

Portfolio

Case Study

Career

Hiring

Research

Opinion

---

# 9. Output

Generate

briefs/YYYY-MM-DD.md

---

The report should contain:

# Today's Signal

A short summary of the biggest trend.

---

# Top Stories

Approximately 10–15 important posts.

Each post includes:

Title

Author

Category

Published Time

Engagement

Summary

Why it matters

Recommended Action

Original Post Link

---

# Category Highlights

Group remaining posts by topic.

Example:

AI Engineering

Product Design

Design Engineering

Portfolio

Career

---

# Worth Opening

Recommend 3 original posts that deserve reading in full.

---

# Today's Takeaway

One sentence.

"What should I remember today?"

---

# 10. Design Principles

The report should be:

Clear

Scannable

Minimal

Actionable

Objective

Do not summarize everything.

Filter aggressively.

Quality over quantity.

---

# 11. Non Goals

This project is NOT trying to become:

A news website

A Twitter client

A social network

A bookmarking app

A recommendation engine

The only purpose is producing one useful daily report.

---

# 12. Future Roadmap

V1

Public X

↓

V2

GitHub Releases

↓

V3

Company Blogs

↓

V4

LinkedIn Hiring

↓

V5

YouTube

↓

V6

Notion Export

---

# 13. Tech Stack (Suggested)

Language

TypeScript

Runtime

Node.js

Output

Markdown

Configuration

YAML

LLM

Codex

---

# 14. Repository Structure

keeping-up-with-design-engineering/

README.md

PROJECT.md

feeds.yaml

prompts/

daily-brief.md

briefs/

src/

---

# 15. Guiding Principle

Do not optimize for collecting more information.

Optimize for helping designers spend less time scrolling and more time learning.
