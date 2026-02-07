# Solana Anchor Claude Skill

A Claude Code skill for creating and editing Solana Anchor projects with best practices and conventions.

> [!NOTE]
> Looking for a Claude RULES file (`CLAUDE.md`) for Solana? You're in the right place. We've updated this repo to use the newer Claude Code **skills** format, which provides better integration and automatic application of guidelines.

## What are Claude Skills?

Claude Code supports "skills" - reusable instruction sets that Claude automatically applies when working on your code. Skills are stored in `.claude/skills/` directories and can be invoked manually or triggered automatically based on context.

This repo includes a Claude skill that teaches Claude the specific patterns and best practices for Solana/Anchor development, including proper variable naming, avoiding magic numbers, using modern Anchor 0.32.1 syntax, and following Solana-specific conventions.

## Installation

```bash
npx skills add https://github.com/quiknode-labs/solana-anchor-claude-skill
```

This automatically installs the skill to your Claude Code skills directory (`~/.claude/skills/`).

## Usage

Once installed, the skill automatically applies when Claude Code works on Solana/Anchor projects. You can also manually invoke it with:

```
/solana-anchor-claude-skill
```
