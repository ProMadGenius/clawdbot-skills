# clawdbot-skills

A collection of skills for Clawdbot/Moltbot agents.

## Available Skills

| Skill | Description |
|-------|-------------|
| [ez-cronjob](./ez-cronjob) | Fix common cron job failures - message delivery, timeouts, timezone bugs |

## Installation

### Via ClawdHub

```bash
clawdhub install <skill-name>
```

### Manual

Copy the skill folder to your workspace or user skills directory:

```bash
# Workspace-level (single agent)
cp -r <skill-name> /path/to/workspace/skills/

# User-level (all agents)
cp -r <skill-name> ~/.clawdbot/skills/
```

## Author

**Isaac Zarzuri** - [@Yz7hmpm](https://x.com/Yz7hmpm)

Website: [metacognitivo.com](https://www.metacognitivo.com)

## License

MIT
