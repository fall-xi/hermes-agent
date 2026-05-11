# Hermes Agent

> Autonomous AI agent with persistent memory, self-improving skills, browser automation, multi-platform messaging, and extensible tooling.

Hermes Agent is an open-source autonomous AI agent designed to run continuously on your machine or server. Unlike traditional chatbots or IDE copilots, Hermes maintains persistent memory, builds reusable skills from experience, and supports automation across messaging platforms, terminals, browsers, and APIs. :contentReference[oaicite:0]{index=0}

---

## Features

### Persistent Memory
Hermes remembers conversations, preferences, projects, and workflows across sessions using structured memory systems and searchable context. :contentReference[oaicite:1]{index=1}

### Self-Improving Skills
The agent can create reusable “skills” from solved tasks and reuse them later. Skills are searchable, versioned, and compatible with the `agentskills.io` standard. :contentReference[oaicite:2]{index=2}

### Multi-Platform Support
Use Hermes from:

- Terminal / CLI
- Telegram
- Discord
- Slack
- WhatsApp
- Signal
- Email
- IDE integrations

A single gateway process can connect multiple platforms simultaneously. :contentReference[oaicite:3]{index=3}

### Browser & Web Automation
Hermes supports:

- Web search
- Page extraction
- Browser automation
- Screenshot capture
- Vision analysis
- Voice transcription

This enables autonomous workflows involving websites and web apps. :contentReference[oaicite:4]{index=4}

### Parallel Subagents
Spawn isolated child agents with dedicated terminals, tools, and contexts for parallel task execution. :contentReference[oaicite:5]{index=5}

### Scheduling & Automation
Built-in cron-style scheduling allows recurring jobs, automated reports, backups, and monitoring tasks. :contentReference[oaicite:6]{index=6}

### Multiple LLM Providers
Hermes supports many model providers including:

- OpenAI-compatible APIs
- OpenRouter
- Nous Portal
- Local vLLM deployments
- Custom endpoints

Fallback providers and credential pools are also supported. :contentReference[oaicite:7]{index=7}

---

## Installation

### One-Line Install

```bash
curl -fsSL https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh | bash
