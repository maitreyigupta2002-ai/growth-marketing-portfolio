# growth-marketing-portfolio

A portfolio project documenting growth marketing tools, setup steps, and research on B2B SaaS YouTube content strategy.

---

## Research: YouTube Content Strategy for B2B SaaS

**Last updated:** 29 June 2026

This repository includes primary research on how B2B SaaS founders and marketers use YouTube, LinkedIn, and SEO together to drive pipeline and revenue.

### What was collected

| Folder | Contents |
|--------|----------|
| [`/research/sources.md`](research/sources.md) | 10 experts with profile links, research dates, and annotations |
| [`/research/linkedin-posts/`](research/linkedin-posts/) | Latest LinkedIn posts organized by author (10 files) |
| [`/research/youtube-transcripts/`](research/youtube-transcripts/) | Video transcripts organized by video (6 transcripts) |
| [`/research/other/`](research/other/) | Supplementary articles, podcast notes, and reference materials |

### Why these experts were chosen

The 10 experts were selected because they represent distinct, proven approaches to B2B SaaS content marketing — with a focus on YouTube as a pipeline channel:

1. **Samu Kovacs (KS Media)** — Runs 40+ B2B YouTube channels; the leading practitioner of YouTube-first demand gen for SaaS
2. **Sam Dunning (Breaking B2B)** — Built $2M+ ARR using the "deadly trio" of SEO, YouTube, and LinkedIn founder brand
3. **Dave Gerhardt (Exit Five)** — Former Drift CMO; authority on founder-led marketing, community, and how AI is reshaping B2B buying
4. **Kipp Bodnar & Kieran Flanagan (HubSpot)** — Hosts of Marketing Against the Grain; inbound marketing and AI-era content strategy at scale
5. **Adam Robinson (RB2B)** — Documented case study of LinkedIn-to-YouTube flywheel; scaled RB2B to $9M+ ARR with founder transparency
6. **TK Kader (Unstoppable)** — GTM advisor with a structured framework (ICP → Manifesto → Broadway Show) for founder-led content
7. **Rob Walling (TinySeed / MicroConf)** — Bootstrapped SaaS authority; 5 stages of awareness framework for B2B content strategy
8. **Denis Shatalin** — Data-backed growth experiments with measurable client outcomes across 100+ B2B SaaS niches
9. **Simon Høiberg (FeedHive)** — Combines AI-assisted workflows with founder-led LinkedIn + YouTube for micro-SaaS growth
10. **Jonathan Rintala (Univid)** — Documents scaling with 1-person GTM team and 95% organic inbound via YouTube + webinars

**Selection criteria:** Each expert actively publishes on LinkedIn and/or YouTube, shares measurable results (not just theory), and demonstrates a repeatable content system relevant to B2B SaaS companies building YouTube into their GTM motion.

### Key themes from the research

- **YouTube is a search + trust channel**, not a vanity metrics play — 1,500 targeted views can outperform 100k generic impressions
- **The flywheel:** YouTube → transcript → LinkedIn post → SEO article → sales enablement playlist
- **SEO + YouTube + LinkedIn** work as an integrated system (Sam Dunning's "deadly trio")
- **Founder-led content** is the common thread — authenticity and transparency build trust faster than corporate marketing
- **Timeline:** Expect 90 days for initial signals; compounding results at 4–12 months with consistent publishing

---

## Project Setup Journey

### Overview

This repository documents the complete setup of a modern AI-assisted development environment, undertaken as part of a portfolio project. It covers tool installation, configuration, troubleshooting, and integration of AI coding assistants within a version-controlled workflow.

### Tools Installed

| Tool | Purpose |
|------|---------|
| **Cursor IDE** | AI-native code editor — [cursor.com](https://cursor.com) |
| **Claude Code (Cursor Extension)** | Anthropic's AI coding assistant, integrated via Cursor Extensions |
| **OpenAI Codex (Cursor Extension)** | OpenAI's AI coding assistant, integrated via Cursor Extensions |
| **GitHub Desktop** | GUI client for managing Git repositories and GitHub integration |

### Steps Completed

#### 1. Installed Cursor IDE

- Downloaded and installed Cursor IDE from [cursor.com](https://cursor.com).

#### 2. Resolved Cursor Startup Crash

Encountered a startup crash on first launch. Diagnosed and resolved the issue:

- Identified the root cause as a corrupted configuration/cache folder
- Navigated to `AppData > Roaming > Cursor > GPUcache` and removed the problematic folder
- Restarted the system and successfully relaunched Cursor

#### 3. Installed Claude Code Extension

- Opened Extensions in Cursor and searched for "Claude Code"
- Installed the extension successfully
- The setup redirected to the Anthropic sign-in page; noted that a subscription is required for full access

#### 4. Installed OpenAI Codex Extension

- Opened Extensions in Cursor and searched for "Codex"
- Installed the extension successfully
- Explored available free-access options upon sign-in redirect

#### 5. Created a Public GitHub Repository

- Signed into GitHub via GitHub Desktop
- Created a new public repository with a name, description, and initialized README
- Verified repository visibility and configuration

#### 6. Cloned the Repository into Cursor

- Initially unfamiliar with the cloning workflow inside Cursor
- Followed documentation and video tutorials to understand the process
- Successfully cloned the GitHub repository into Cursor and verified the local project setup

#### 7. Configured Git Integration

- Linked the local project to the remote GitHub repository
- Verified that commits and pushes function correctly within Cursor

#### 8. Created and Updated README.md

- Created this README file directly within the repository
- Documented all tools, steps, issues encountered, and resolutions
- Committed and pushed the README to GitHub

### Issues Encountered & Resolutions

| Issue | Resolution |
|-------|------------|
| Cursor crashed on startup | Deleted corrupted config/cache folder from `AppData > Roaming > Cursor > GPUcache` and restarted the system |
| Unfamiliar with cloning a repo inside Cursor | Followed YouTube tutorials on Git + Cursor workflow; successfully cloned from terminal in Cursor |
| Claude Code requires a paid subscription | Proceeded with Codex for project setup, local development, and GitHub operations |
