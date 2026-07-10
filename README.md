# Nsketch CLI

Generate images, videos, voice, motion transfer, and more with [Nsketch AI](https://nsketch.ai) from your terminal — or let your AI agent (Claude Code, Codex, Cursor) do it for you.

```
npm install -g @nsketch/cli
```

## Quick start

```bash
# Sign in (opens a browser, takes 5 seconds)
nsketch auth login

# Generate an image and get the result URL
nsketch generate image --prompt "a corgi surfing at golden hour" --wait

# Seedream 5 Pro at 2K
nsketch generate image --model img-seedream-v5-pro --resolution 2K \
  --prompt "a cinematic mountain village" --wait

# Seedream 5 Pro edit using the reference image's natural aspect ratio
nsketch generate image --model img-seedream-v5-pro-edit --resolution 2K \
  --aspect-ratio auto_2K --image ./reference.png \
  --prompt "make this cinematic" --wait

# Image-to-video — local files are auto-uploaded
nsketch generate video --prompt "the corgi rides the wave" --image ./corgi.png --wait
```

## Commands

| Command | What it does |
|---|---|
| `nsketch auth login\|logout\|status` | Browser OAuth sign-in; credentials in `~/.config/nsketch/` |
| `nsketch account status` | Credits and plan |
| `nsketch models list [--type image\|video\|voice]` | Model catalog (see [MODELS.md](MODELS.md)) |
| `nsketch generate image` | Text-to-image and image editing |
| `nsketch generate video` | Text/image-to-video |
| `nsketch generate voice` / `clone-voice` | Text-to-speech, voice cloning |
| `nsketch generate lipsync` | Lipsync video or animate a photo to audio |
| `nsketch generate motion-transfer` | Transfer motion from a video onto a character |
| `nsketch generate upscale` / `remove-bg` / `reshoot` | Enhancement tools |
| `nsketch status <request-id>` | Check an async generation |
| `nsketch upload <file>` | Upload media, get a hosted URL |

Global flags: `--wait` (block until done, print result URL), `--wait-timeout 10m`, `--wait-interval 3s`, `--json` (machine-readable stdout).

## For AI agents

- Install the agent skills: [`npx skills add Nsketch-AI/skills`](https://github.com/Nsketch-AI/skills)
- Prefer connectors? Use the hosted MCP server instead: `https://nsketch.ai/api/mcp`
- All commands support `--json`; async jobs support `--wait` so the CLI handles polling.

## Development

The CLI is developed in the Nsketch monorepo and published to npm as [`@nsketch/cli`](https://www.npmjs.com/package/@nsketch/cli). This repository hosts documentation and the issue tracker.
