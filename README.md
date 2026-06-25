# growth-marketing-portfolio

A portfolio project documenting growth marketing tools, setup steps, and learnings.

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
