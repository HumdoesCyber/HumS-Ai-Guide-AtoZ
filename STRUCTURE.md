# Structure of the guide

One book, told as four "books" plus a reference section: 40 chapters. Each book can be read
on its own, and every chapter is a separate unit of work, so progress shows up chapter by
chapter.

This replaces the earlier layout of Parts 0–29, which grew by addition: parts wedged in as
7.5, 17.5 and 21.5, topics spread across several places (incident response lived in five),
and chapters ordered by when they were written instead of how people learn.

## Start here: reading paths

| You are | Start with | Then |
|---|---|---|
| Owner, executive or manager | Ch. 1–2, then Book IV | Ch. 22 (incident response), Ch. 38 (cheat sheet) |
| Developer or platform engineer | Book I, then Book II | Book III as you deploy |
| Security analyst, SOC or red team | Book I, then Book III | Ch. 8, Ch. 20 |
| Cloud or ML engineer | Ch. 1–4, then Ch. 25–28 | Ch. 16–17 |

## Book I — Understand (Ch. 1–9)
What agents are, who should use them how, and how they break.

| Ch | Title | Built from (old layout) |
|---|---|---|
| 1 | What an AI agent actually is | Part 1 |
| 2 | AI at your size: where you fit | New: one page each for solo founder, small business, mid-size, enterprise, with what to do first and where to read next (condensed from Parts 0, 10–13) |
| 3 | How agents get attacked: the threat model | Part 2 |
| 4 | The five layers of defense | Part 3 |
| 5 | Prompt injection: the problem that won't go away | Part 6 (first half) |
| 6 | Memory, browsers and cross-session attacks | Part 6 (second half), incl. the author's AI-008/009 hypothesis |
| 7 | Tools, MCP and agent-to-agent boundaries | Part 7 |
| 8 | Thinking like a red team | Part 8 |
| 9 | When it went wrong: case studies | Part 19 |

## Book II — Build (Ch. 10–20)
Hands-on, from a first agent to production.

| Ch | Title | Built from |
|---|---|---|
| 10 | Your first secure agent | 4.1–4.3, 4.11, 30-minute speedrun |
| 11 | Tools, approval gates and acting as the user | 4.4–4.6 |
| 12 | Logging, safety checks and attacking your own agent | 4.7, 4.8, 4.12 |
| 13 | Your own MCP server I: foundations | 4.9, 4.10, 7.5.1–7.5.7 (merged, duplicates removed) |
| 14 | Your own MCP server II: authentication and sandboxing | 7.5.8–7.5.10 |
| 15 | Your own MCP server III: test, ship, run | 7.5.11–7.5.19 |
| 16 | Going to production: deploy, RAG, streaming, retries | 4.13–4.16 |
| 17 | Testing, CI/CD, PII and cost control | 4.17–4.20 |
| 18 | Your homelab: local models, local agents, hardening | Part 5 |
| 19 | Coding agents in the enterprise | Part 27 |
| 20 | Loopholes: bugs that bite production | Part 25 |

## Book III — Run and Defend (Ch. 21–28)
Operating agents safely, on your own hardware or on AWS.

| Ch | Title | Built from |
|---|---|---|
| 21 | Monitoring and detection | Part 9 |
| 22 | Incident response (one home for it) | Part 18, plus the incident pieces of Parts 13 and 21 |
| 23 | Air-gapped deployments | Part 17 |
| 24 | OT and NERC CIP | Part 17.5 |
| 25 | AI on AWS I: accounts, identity, network | 28.1–28.6 |
| 26 | AI on AWS II: guardrails, logging, agents | 28.7–28.11 |
| 27 | Training and fine-tuning your own models | 29.1–29.4 |
| 28 | Protecting, testing and hosting your models | 29.5–29.8 |

## Book IV — Lead (Ch. 29–37)
Rolling AI out and governing it.

| Ch | Title | Built from |
|---|---|---|
| 29 | The 90-day rollout | Part 0 |
| 30 | Solo founders and startups (1–5 people) | Part 10 |
| 31 | Small business (5–50) | Part 11 |
| 32 | Mid-size organizations (50–500) | Part 12 |
| 33 | Large enterprise (500+) | Part 13 |
| 34 | Legal issues and how to work through them | Part 14 |
| 35 | SOC 2 and audits | Part 15 |
| 36 | Frameworks you should know | Part 16 |
| 37 | Buying AI safely: procurement | Part 26 |

## Reference (Ch. 38–40)

| Ch | Title | Built from |
|---|---|---|
| 38 | Cheat sheet and one-page emergency card | Parts 21 and 21.5 |
| 39 | Templates | Part 22 |
| 40 | Tools, research links and glossary | Parts 20, 23, 24 |

**Front and back matter:** who this guide is for, what changed, reading paths, contents;
closing thoughts; Appendix A (self-review and verification status); Appendix B (references
and sources).

## Rules that keep the structure stable

- Chapter numbers are fixed once published. New material goes into an existing chapter or
  into the reference section, never as "Chapter 7.5."
- Each topic has one home. Other chapters link to it instead of repeating it.
- Cross-references use chapter numbers ("see Ch. 22") and are checked automatically at
  every build.
