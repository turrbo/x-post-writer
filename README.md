# X Post Writer

Master authentic X.com (Twitter) content generator using emotion-first, phased architecture. Creates tweets and threads that sound genuinely human through cognitive state simulation, not just rule-following. Use when the user asks to write a tweet, create X.com content, write a Twitter post, compose a thread, draft social media content for X/Twitter, or needs help with X.com engagement. Includes adversarial committee review, Claude-ism detection, and interactive refinement workflow. Supports single tweets, threads, quote tweets, and reply strategies.

## What this repo contains

- `SKILL.md` — the primary agent skill definition and workflow.
- `references/` — supporting playbooks, platform rules, examples, or data used by the skill.

## Reference material

- `references/examples.md`
- `references/thread-strategies.md`
- `references/tool-mentions.md`
- `references/communities.md`
- `references/claude-isms.md`

## Installation

Copy this repository or the skill directory into your agent's skills directory, then load the skill by name when the task matches its use case.

```bash
# example
cp -R x-post-writer ~/.claude/skills/x-post-writer
```

## Repository layout

```text
references/
  claude-isms.md
  communities.md
  examples.md
  thread-strategies.md
  tool-mentions.md
LICENSE
SKILL.md
```

## Notes

The root README summarizes the live repository contents. The complete operational instructions remain in `SKILL.md`.
