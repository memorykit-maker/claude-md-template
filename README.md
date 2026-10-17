# claude-md-template

A starting `CLAUDE.md` for Claude Code, built from rules that came out of real failures instead of a wish list.

Claude Code reads `CLAUDE.md` at the start of every session and again after context is compacted, so whatever is in it, Claude already knows when you sit down. Most of the ones I see are long lists of preferences. This one is short on purpose: identity, a startup routine, and the few rules that must never lapse. Everything else belongs in notes that Claude opens only when it needs them.

## Use it

1. Make a folder for your notes and open Claude Code in your working folder.
2. Copy `CLAUDE.md` into that folder.
3. Fill in the four bracketed spots: who you are, how you want Claude to work with you, where your notes live, and the name of your index note.
4. Create the index note and an open-items note. A single page each is enough.
5. Open a brand-new session and ask what you're working on. If it answers without you explaining, it's working.

## Why it is built this way

- **Short file, living notes.** The file holds what can never be forgotten. The notes hold what changes. A giant file that is never touched again goes stale and gets ignored.
- **Every rule has a reason.** Rules that come with their why are easier to keep and easier to prune when they stop earning their place.
- **The rules come from failure.** Sessions died after resuming from a long idle, and while viewing huge screenshots. A session that stayed open past midnight filed work under the wrong day. Guesses got reported as facts. Each rule is a scar.

## Honest limits

- Some rules are guesses about cause. The "start fresh after a long idle" rule is based on a pattern (sessions dying on the first prompt after a long idle) and a plausible explanation (an expired prompt cache), not proof. Keep the rule if the pattern matches yours; drop it if it doesn't.
- This is one person's setup. Your list should end up different. Delete rules you don't need, and add your own when something goes wrong twice.
- It is a text file. It improves how Claude behaves; it does not enforce anything. For hard enforcement you need hooks.

MIT licensed.
