# I Have ADHD, Matt's Version

An action-first output skill for AI coding tools. It helps turn a long answer into a clear decision, a few bounded steps, and an obvious next move.

This is Matt Reichard's fork of [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd). The original is MIT-licensed and remains credited below.

## What changed

The original skill makes answers easier to act on. This version also asks the AI to:

- recommend one path when it can;
- separate verified facts from inference;
- show what is done, next, or blocked;
- state verification and remaining risk for product or code work;
- write plainly, without hype, em dashes, or generic AI phrasing.

These are Matt's preferences, not universal rules. Copy what helps. Remove what does not.

## Install

### Claude Code

```bash
claude plugin marketplace add mattreichard-ai/i-have-adhd-mattreichard
claude plugin install i-have-adhd-mattreichard@i-have-adhd-mattreichard
```

Then type `/i-have-adhd-mattreichard`.

### ChatGPT Codex

```bash
codex plugin marketplace add mattreichard-ai/i-have-adhd-mattreichard --ref main
codex plugin add i-have-adhd-mattreichard@i-have-adhd-mattreichard
```

Then type `$i-have-adhd-mattreichard`.

### Cursor

```bash
npx skills add mattreichard-ai/i-have-adhd-mattreichard -a cursor -y
```

Start a new chat, then type `/i-have-adhd-mattreichard`.

See [INSTALL.md](./INSTALL.md) for update, uninstall, and other-agent instructions.

## Make it yours

Use the skill for real work first. Then add only a few rules that change how you act on an answer.

Ask yourself:

1. What do I regularly lose track of?
2. What kind of AI answer makes me delay starting?
3. What should AI always make explicit?
4. What tone makes me trust or ignore an answer?

## Notion guide

Read the [setup and customization guide](https://adaptable-nightshade-c98.notion.site/Make-Claude-Get-to-the-Point-3a70c682647581fdb2c3fc5e5b9dd6b8).

## Credit and license

Based on [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) by Ayoub G. The original is loosely based on *The Adult ADHD Tool Kit* by J. Russell Ramsay and Anthony L. Rostain.

This fork is licensed under the [MIT License](./LICENSE).
