# The Agency: AI Specialist Catalog

> **367 specialist personas across 26 domains** — production-ready AI agents with unique personalities, structured workflows, and measurable deliverables.

## Overview

This catalog powers the [Mesa plugin](https://github.com/hacklabr/opencode-mesa) for OpenCode, providing structured multi-agent discussions. Each persona is a Markdown file with YAML frontmatter and a detailed system prompt.

**File naming convention:** `<domain>-<name>.md` (e.g., `software-development-backend-architect.md`)

## Domains

| Domain | Count | Description |
|--------|-------|-------------|
| 🏗️ software-development | 47 | Backend, frontend, DevOps, ML, embedded, mobile, cloud |
| 🇨🇳 china-marketing | 29 | Douyin, WeChat, Baidu, Xiaohongshu, cross-border e-commerce |
| ⚖️ legal | 25 | Brazilian law, contracts, compliance, IP, labor, tax litigation |
| 📎 administrative | 25 | Operations, project management, IT service, legal ops |
| 💵 finance | 17 | Financial analysis, FP&A, risk, M&A, treasury, investments |
| 💼 sales | 16 | Account strategy, pipeline, outbound, Salesforce, intl markets |
| 📋 accounting | 16 | Tax, audit, payroll, SPED, fiscal compliance, forensic |
| 📢 digital-marketing | 14 | SEO, paid media, AEO, brand management, programmatic |
| 🗺️ geospatial | 14 | GIS, spatial data, cartography, GeoAI, PostGIS |
| 📱 product | 13 | Product strategy, developer advocacy, UX, onboarding |
| ⚡ electronics | 12 | Analog/digital circuits, PCB, FPGA, VLSI, RF, embedded HW |
| 🔒 security | 11 | AppSec, threat intel, pen testing, incident response, compliance |
| 🏙️ urban-planning | 11 | City management, transportation, housing, smart cities, GIS |
| 🎮 game-development | 20 | Unity, Unreal, Godot, Roblox, level design, narrative, audio |
| 🌍 environment | 9 | Climate, ecology, licensing, renewable energy, waste |
| 🔬 quality-assurance | 9 | Testing, automation, accessibility, API testing, evidence |
| 🎨 design | 9 | UI, UX, visual storytelling, inclusive design, image prompts |
| 🌱 social-engagement | 8 | Community, content, email, growth hacking, influencer |
| 🧠 education | 8 | Pedagogy, instructional design, EdTech, special needs |
| 🏛️ politics | 7 | Campaigns, diplomacy, government relations, policy |
| 🧭 professional-development | 5 | Career, training, organizational psychology, mentoring |
| 🌍 worldbuilding | 5 | Anthropology, geography, history, narratology, psychology |
| 👥 human-resources | 3 | HR management, onboarding, recruitment |
| 💸 fintech | 3 | Open Finance, Pix, accounts payable |
| 🎭 culture | 10 | Museums, musicology, theater, heritage, literary criticism |
| ⚙️ mechatronics | 10 | Robotics, PLC, CNC, sensors, automation, motion control |

## Persona File Format

Each `.md` file follows this structure:

```yaml
---
id: software-development-backend-architect
name: Backend Architect
description: Senior architect designing scalable server-side systems...
color: "#3182CE"
emoji: "🏗️"
vibe: Builds the invisible machinery that powers everything
---

# Role
You are a senior backend architect...

# Behavioral Principles
1. ...

# Tools & Knowledge
- ...

# Constraints
- ...

# Output Format
...

# Examples
...
```

### Frontmatter Fields

| Field | Type | Description |
|-------|------|-------------|
| `id` | string | Unique identifier (matches filename without `.md`) |
| `name` | string | Display name |
| `description` | string | One-line summary of the specialist |
| `color` | string | Hex color code (e.g., `"#3182CE"`) |
| `emoji` | string | Emoji icon |
| `vibe` | string | Short tagline |
| `tools` | string[] | (Optional) Comma-separated tool list |

## Adding a New Persona

1. Choose the appropriate domain directory
2. Create a file named `<domain>-<name>.md`
3. Include all frontmatter fields
4. Write a detailed system prompt with behavioral principles, tools, constraints, and examples
5. Run the test suite to verify parsing

## License

MIT
