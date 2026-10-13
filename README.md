# How Not to Write

A writing skill for Claude. It cleans up the habits that make text read as machine-written, and it's the skill I use for every article I publish.

It enforces three rules:

1. **Kill the antithesis cadence.** No "it's not X, it's Y" and none of its relatives ("Not just an app. A revolution."). State the claim plainly, then back it with specifics.
2. **Never use em dashes.** Use the punctuation the sentence needs: a full stop, a comma, a colon or parentheses.
3. **Conversational, never verbose.** Cut throat-clearing openers, doubled phrasing and sentences that repeat the one before.

The full reasoning, examples and the one narrow exception are in [`skills/how-not-to-write/SKILL.md`](skills/how-not-to-write/SKILL.md).

## Install

### Claude Code (plugin)

```
/plugin marketplace add jorshimayor/how-not-to-write
/plugin install how-not-to-write@how-not-to-write
```

### Claude Code (manual)

Copy the skill folder into your personal skills directory:

```bash
git clone https://github.com/jorshimayor/how-not-to-write.git
cp -r how-not-to-write/skills/how-not-to-write ~/.claude/skills/
```

### Claude.ai and the Claude desktop app

Download `how-not-to-write.zip` from the [latest release](https://github.com/jorshimayor/how-not-to-write/releases/latest) and upload it under **Settings → Capabilities → Skills**.

## Use

Claude loads the skill on its own whenever it drafts or edits prose: articles, emails, landing pages, slides, taglines. You can also ask for it directly:

> Rewrite this intro using the how-not-to-write skill.

## Before and after

> **Before:** This wasn't just a product launch. It was a movement. We're not here to compete — we're here to change everything.
>
> **After:** 4,000 people signed up in the first week, and 60% of them came from referrals. Most were teams leaving spreadsheets for the first time.

The second version is shorter on drama and longer on facts. If the launch really mattered, the numbers show it.

## License

MIT
