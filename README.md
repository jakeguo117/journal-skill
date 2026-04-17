# Journal Skill

An interactive weekly journaling ritual for [Claude Code](https://claude.com/code) that writes to an [Obsidian](https://obsidian.md) vault in your own voice — not a chatbot's.

## What it does

Runs a guided weekly journal session:

1. **Reads context** — pulls your last 2–3 journal entries and a personal memory file so it knows what's been on your mind
2. **Asks reflective questions** — 2–3 rounds of questions that start broad and pull on specific threads from what you share
3. **Writes the entry** — drafts a full weekly journal in your natural voice (stream-of-consciousness, honest, humor-friendly), saves it to your Obsidian vault with proper frontmatter and topic links
4. **Gives you review control** — lets you request edits before finalizing

## Why it exists

AI journal apps (Rosebud, Day One AI, Mindsera) all write in a flat, polished, generic-AI tone. That's the opposite of what a good journal entry sounds like. This skill is designed to capture your *actual* voice — casual, code-switching, self-referential, topic-jumping — not flatten it into bullet points and "总结" sections.

## Installation

1. Copy `journal.md` into your Claude Code commands directory:

```bash
cp journal.md ~/.claude/commands/journal.md
```

2. Update the paths inside the skill to match your setup:
   - Obsidian journal folder (default is the author's iCloud Obsidian vault)
   - Personal memory file location
3. Run `/journal` inside Claude Code whenever you want to write a weekly entry.

## Customizing for your voice

The skill is tuned to its author's style (bilingual Chinese + English, stream-of-consciousness, casual). To personalize:

- Edit the **Jake's Journal Style** section to describe *your* tone — formal or casual, which languages, what patterns you reject
- Drop 2–3 sample entries into your Obsidian journal folder so the skill can mimic from real examples
- Add a personal memory file with context the skill should remember (family, current projects, ongoing threads)

## Status

Personal tool in active use — shared here for other Claude Code + Obsidian users to adopt and adapt.

## License

MIT — see `LICENSE` for details.
