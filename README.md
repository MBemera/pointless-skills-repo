# Pointless Skills Repo

A collection of fun, useless, and completely pointless skills for [Claude Code](https://claude.ai/claude-code).

Each skill is a `.md` file you drop into `~/.claude/commands/` and invoke with a slash command.

---

## Skills

| Skill | Command | Description |
|-------|---------|-------------|
| Macho Man Randy Savage | `/macho` | Respond as the Macho Man himself. Ohhh yeah. |

---

## How to Install a Skill

**One-liner install:**

```bash
curl -o ~/.claude/commands/macho.md https://raw.githubusercontent.com/MBemera/pointless-skills-repo/main/skills/macho.md
```

**Or manually:**
1. Download the `.md` file from the `skills/` folder
2. Copy it to `~/.claude/commands/`
3. Restart Claude Code

Then just type the slash command (e.g. `/macho`) in any Claude Code session.

---

## How to Use

Once installed, type the skill's command in Claude Code:

```
/macho
```

The skill activates and stays in character for the rest of the conversation. Ask it anything.

---

## Contributing

Got a pointless skill idea? Open a PR and add your `.md` file to the `skills/` folder.
