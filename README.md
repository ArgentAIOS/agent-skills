# ArgentOS Agent Skills

A collection of 48 portable agent skills compatible with [AgentSkills.io](https://agentskills.io) — the open standard for giving AI agents new capabilities.

## Compatible With

These skills work with any AgentSkills-compatible platform:

Claude Code, Cursor, VS Code/Copilot, OpenAI Codex, Gemini CLI, JetBrains Junie, Databricks, Snowflake, Goose, OpenHands, Roo Code, and [30+ more](https://agentskills.io).

## Install

### ArgentOS
```bash
argent skills install https://github.com/ArgentAIOS/agent-skills
```

### Claude Code
Copy any skill directory to your project's `.claude/skills/` directory.

### Other Platforms
Copy the skill directory to your platform's skills location. See [agentskills.io](https://agentskills.io) for platform-specific instructions.

## Skills

| Skill | Description |
|-------|-------------|
| `apple-notes` | Create and search Apple Notes via CLI |
| `apple-reminders` | Manage Apple Reminders via CLI |
| `autonomous-unblock` | Self-unblock when stuck on a task |
| `bear-notes` | Create, search, and manage Bear notes |
| `bird` | Interact with Bluesky social network |
| `blogwatcher` | Monitor RSS feeds and blog posts |
| `blucli` | Bluetooth device management via CLI |
| `camsnap` | Capture webcam snapshots |
| `coolify` | Manage Coolify self-hosted deployments |
| `easydmarc` | DMARC email authentication management |
| `eightctl` | Eight Sleep smart mattress control |
| `email-delivery` | Email sending and delivery management |
| `food-order` | Reorder food delivery + track ETA |
| `gemini` | Google Gemini AI interactions |
| `gifgrep` | Search and create GIFs |
| `github` | Full GitHub CLI (issues, PRs, runs, API) |
| `gog` | Google Calendar management |
| `goplaces` | Find nearby places and businesses |
| `himalaya` | Email client via himalaya CLI |
| `imsg` | Send and read iMessages |
| `local-places` | Local business search and discovery |
| `mcporter` | MCP server management |
| `model-usage` | Track AI model usage and costs |
| `namecheap` | Domain management via Namecheap API |
| `nano-pdf` | PDF text extraction and processing |
| `notebooklm-research` | NotebookLM research workflows |
| `notion` | Notion workspace management |
| `obsidian` | Obsidian vault management |
| `openai-image-gen` | Generate images with DALL-E |
| `openai-whisper` | Speech-to-text with Whisper |
| `openhue` | Philips Hue smart light control |
| `oracle` | Database queries and management |
| `ordercli` | Food ordering via ordercli |
| `peekaboo` | Screen capture and OCR |
| `railway` | Railway.app deployment management |
| `sag` | Audio generation and speech synthesis |
| `send-payload` | Multi-channel message delivery |
| `skill-creator` | Create new AgentSkills-format skills |
| `slack-signal-monitor` | Monitor Slack channels for signals |
| `songsee` | Music recognition and identification |
| `sonoscli` | Sonos speaker control |
| `spotify-player` | Spotify playback control |
| `summarize` | Text summarization |
| `twilio` | SMS and voice via Twilio API |
| `vercel` | Vercel deployment management |
| `video-frames` | Extract frames from video files |
| `vip-email` | Priority email management |
| `weather` | Weather lookup and forecasts |

## Format

Each skill follows the [AgentSkills.io specification](https://agentskills.io/specification):

```
skill-name/
├── SKILL.md          # Metadata + instructions (YAML frontmatter + Markdown)
├── scripts/          # Optional executable code
├── references/       # Optional documentation
└── assets/           # Optional templates and resources
```

All 48 skills pass the official [skills-ref validator](https://github.com/agentskills/agentskills/tree/main/skills-ref).

## License

MIT — Built by [ArgentOS](https://argentos.ai)
