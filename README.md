# Claude Skills by Creative Intelligence Engineering

Free, ready-to-use skills for Claude. Each folder is one skill: a `SKILL.md` file that teaches Claude a repeatable job.

| Skill | What it does |
|---|---|
| [check-the-deal](check-the-deal/SKILL.md) | Tells you if a Black Friday / Cyber Monday / any sale price is really a deal: exact model (spots "doorbuster" versions), usual price, 2 alternatives, seller and returns, and a Buy now / Wait / Skip verdict. |

## How to use a skill

**Claude app (claude.ai, desktop):**
1. Download the skill folder (for example `check-the-deal`) and zip it.
2. In Claude, open **Settings → Capabilities → Skills** and upload the zip. (Skills need to be enabled for your plan.)
3. Ask: *"Check this deal: 55-inch TV model XYZ-123 for $299 at <store>."*

**Claude Code:**
1. Copy the folder into `~/.claude/skills/` (all projects) or `.claude/skills/` in your project.
2. Ask Claude Code to check a deal; it picks up the skill automatically.

Menus can change; if a step looks different, search Claude's help center for "skills".

## Notes
- Claude can't see live price-history charts. Always confirm the price history in a free price tracker before you buy.
- Shopping information, not financial advice. You make the final call and checkout yourself.

New skills and step-by-step tutorials every Sunday on YouTube: **Creative Intelligence Engineering** (@VishalSBhandare).

Made by Vishal S Bhandare · [LinkedIn](https://www.linkedin.com/in/vishal-bhandare-a3123657/) · [GitHub](https://github.com/vbvishal19) · MIT License
