# avatar-content-engine
Portable AgentSkills skill for running an AI-avatar short-form content engine — script, image, and lip-synced video for TikTok, Reels &amp; Shorts. Works in OpenClaw &amp; Claude Code.
# Avatar Content Engine — Agent Skill

A portable [AgentSkills](https://github.com/openclaw/openclaw) skill for running an
**AI-avatar short-form content engine** — script, image, and video production for
social-video avatars across TikTok, Reels, Shorts, and Facebook.

It encodes a full production methodology: an emotion-first content philosophy, a
structured 16-second two-clip script contract, ten toggleable virality systems, a
photographic-language approach to consistent avatar portraits, and a voice/video
architecture for lip-synced multi-clip sequences.

The skill is a **reusable template** — the example avatars (Nova, Remy, Kai, Sable) and
the `[BRAND]` slots are meant to be renamed and filled with your own product.

## Install

**OpenClaw**

```bash
# From a Git URL
openclaw skills install https://github.com/<you>/avatar-content-engine

# Or drop it into your workspace manually
mkdir -p <workspace>/skills/avatar-content-engine
cp SKILL.md <workspace>/skills/avatar-content-engine/SKILL.md
```

Start a new session (or `openclaw gateway restart`) so the skill snapshot refreshes,
then invoke it with `/avatar-content-engine` or let it auto-trigger.

**Claude Code**

```bash
mkdir -p .claude/skills/avatar-content-engine
cp SKILL.md .claude/skills/avatar-content-engine/SKILL.md
```

## Compatibility

Follows the AgentSkills spec, so the same folder runs unchanged across OpenClaw,
Claude Code, and other AgentSkills-compatible runtimes. Frontmatter keys are
single-line, as required by OpenClaw's parser.

## Structure

```
avatar-content-engine/
├── SKILL.md      # the skill (frontmatter + instructions)
└── README.md     # this file
```

## License

MIT — see `LICENSE`.
