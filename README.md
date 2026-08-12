# Visla Agent Skills

Create AI-generated videos from text scripts, URLs, documents, ideas, visual resources, or audio using Visla. Use this skill when a user asks to generate a video, turn a webpage into a video, convert a PPT/PDF into a video, create a video from images/audio, or check Visla account credits/balance.

## Installation

Install using the [add-skill](https://github.com/vercel-labs/add-skill) CLI:

```bash
# Install globally
npx skills add visla-us/skills -g

# Or install to the current project only
npx skills add visla-us/skills
```

This works with Claude Code, Cursor, Codex, and [13 other agents](https://github.com/vercel-labs/add-skill#available-agents).

## Usage

Skills are automatically available once installed. The agent will use them when relevant tasks are detected.

**Examples:**

```
Create a video from the script in ~/video_script.md
```

```
Create a video from https://visla.us
```

```
Create a video from ~/example.pdf
```

```
Create a video from my idea about machine learning
```

```
Create a video from ~/photo.jpg
```

```
Create a video from ~/interview.m4a
```

## Credentials

You need a Visla API key and secret. See the authentication docs at https://developer.visla.us/reference/api-authentication.

## API Reference

See the developer docs at https://developer.visla.us/.

## Requirements

- Visla API key and secret
- Python 3.7+ (no third-party packages required — the CLI uses only the standard library)
- Any AI agent that supports add-skill (e.g., Claude Code, Codex, Cursor, OpenCode, OpenClaw)

## License

MIT
