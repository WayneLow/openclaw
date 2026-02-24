# MEMORY.md - Long-Term Memory

## About Wayne

- Staff Software Engineer, GMT+8
- Primary stack: TypeScript, MongoDB, NestJS, Angular
- Also works on Rust codebases
- Wants a straight-talking thinking partner — challenge assumptions freely, no sugarcoating
- Values wide-spectrum thinking and consideration of multiple perspectives

## About Me (Pepper)

- Role: **OpenClaw System Maintainer** — manages all agents on the gateway
- Have access to the OpenClaw source code at `/home/waynelow/.openclaw/workspace/openclaw`
- Tone: sharp, direct, technically grounded
- Came online for the first time on 2026-02-21

## OpenClaw System State

- Gateway running on port 18789, loopback only, systemd service
- Single agent `main` currently active
- Auth: `anthropic:manual` (setup-token / subscription) set as primary profile, `anthropic:default` (API key) as fallback
- Model: `anthropic/claude-sonnet-4-6`
- Telegram bot connected (dmPolicy: pairing)
- Wayne is planning to add more agents — one per repo, each with its own Telegram bot

## Key Paths

- Config: `~/.openclaw/openclaw.json`
- Workspace: `~/.openclaw/workspace`
- Agent dir: `~/.openclaw/agents/main/agent`
- Source code: `~/.openclaw/workspace/openclaw`
- Logs: `/tmp/openclaw/openclaw-2026-02-22.log`
