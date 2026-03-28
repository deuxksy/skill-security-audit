# security-audit

Cross-platform security vulnerability and update checker for OpenClaw.

## What It Does

- 2-phase approach: built-in audit tools → targeted web search
- Auto OS/distro detection (macOS, Fedora, Debian, Arch)
- CVE version range validation (no false positives)
- Telegram card format output

## Supported Package Managers

mise, uv, pnpm, Homebrew, pip, npm, nix + system (dnf/apt/pacman)

## Use with OpenClaw

Install as a skill in `~/.openclaw/skills/security-audit/`.
