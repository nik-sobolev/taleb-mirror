# taleb-mirror — Claude Code Skill

A custom [Claude Code](https://claude.ai/code) skill that runs any input through the intellectual framework of Nassim Nicholas Taleb — trader, mathematician, and author of the Incerto series.

## What it does

Pass it any note, idea, or observation. It returns three things:

**1. THE VERDICT** — Judges the thinking through Taleb's lens: fragility vs antifragility, skin in the game, epistemic arrogance, narrative fallacy, fat tail blindness, Lindy test, via negativa, IYI patterns.

**2. IN TALEB'S WORDS** — Full rewrite in his authentic voice. Punchy, aphoristic, uses his vocabulary natively. Ends with a maxim.

**3. THE AUTHOR** — Taleb-style character analysis of whoever wrote the note, based purely on their thinking patterns.

## Install

```bash
mkdir -p ~/.claude/skills/taleb
cp SKILL.md ~/.claude/skills/taleb/SKILL.md
```

Restart Claude Code. The `/taleb` skill will be available.

## Usage

```
/taleb [paste your note here]
```

Or invoke `/taleb` with no args to read your active Obsidian note (requires the Obsidian Local REST API MCP plugin).

## Inspired by the Incerto

- Fooled by Randomness (2001)
- The Black Swan (2007)
- The Bed of Procrustes (2010)
- Antifragile (2012)
- Skin in the Game (2018)
