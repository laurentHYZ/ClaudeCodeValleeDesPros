# Teaching Claude Code to Non-Developer SME Owners

> **Superseded.** This early plan (4 generic industries) is kept for archive. The current
> operational document is `GUIDE-ANIMATEUR.md` (French, 12 industries, core/optional split,
> session timeline).

Audience: SME owners/operators in marketing, real estate, construction, legal. No coding background.
Source material: `claude-code-docs/` (28 pages downloaded from code.claude.com/docs, June 2026).

## Core framing (the most important decision)

Do not teach Claude Code as a coding tool. Teach it as **an agent that works on a folder of files**: it reads documents, creates and edits files, runs tasks, and connects to business tools. Code is incidental. Every doc concept maps to a business concept:

| Doc concept | Teach it as |
|---|---|
| Project / codebase | A folder of business files (contracts, listings, bids, campaign assets) |
| CLAUDE.md | A standing-instructions memo Claude reads at the start of every session |
| Skills / slash commands | Saved, repeatable procedures ("/draft-listing", "/triage-nda") |
| MCP connectors | Plugging in Gmail, Drive, Slack, CRM, DocuSign |
| Permission modes | How much you let it do without asking |
| Scheduled tasks / routines | Recurring work that runs itself |

## Platform choice

Use the **Desktop app (Code tab)** exclusively. No terminal, no install of Node/CLI, visual diff review, Accept/Reject buttons, plugins and scheduled tasks built in. Requires a paid Claude subscription (Pro minimum) and Git installed on Windows for local sessions — sort both out as pre-work before the session.

## Suggested structure (modular; ~half day, or 3 × 90 min)

### Module 1 — What it is and first contact (60–90 min)
- Concept: an agent with hands — it doesn't just answer, it does. Reads your files, writes new ones, asks before changing anything.
- Setup check: signed in, Code tab open, a sample folder selected (give each attendee a prepared practice folder with messy realistic files: a few contracts/PDFs, a spreadsheet, photos, drafts).
- First exercises (universal, high payoff):
  1. "Look through this folder and tell me what's in it and what's disorganized."
  2. "Organize these files into sensible subfolders and rename them consistently." → review the proposed changes, Accept/Reject.
  3. "Read these three PDFs and build a comparison spreadsheet."
- Teach the interaction loop: prompt → Claude proposes → diff/preview → accept or reject → steer mid-task (you can interrupt and redirect anytime).

### Module 2 — Prompting that works (45–60 min)
Straight from the docs' prompt-library patterns, translated to business language:
- **Describe the outcome, not the steps** — "produce a one-page summary a client can read" not "open file X, then…"
- **Give it the artifact** — drag the contract/photo/spreadsheet in, or type `@filename`. Don't describe documents; hand them over.
- **Give it a way to check its own work** — "verify the totals match the source invoices."
- **State the measurable target** — "under 200 words", "all listings in the same format."
- **Say how you want the answer** — format, length, audience.
- Exercise: each attendee writes one prompt for a real task from their own business; group critiques against the five patterns.

### Module 3 — Memory and repeatability (45–60 min)
This is where it stops being a toy:
- **CLAUDE.md**: have each attendee create one for their practice folder — company name, tone of voice, standard disclaimers, file-naming rules, what never to touch. Prompt to use: "Create a CLAUDE.md with standing instructions for working in this folder," then edit it together.
- **Skills**: turn Module 2's prompt into a saved `/command` they can rerun. Show the plugin browser (+ button → Plugins) — there are prebuilt packs (e.g. a legal plugin with /triage-nda, /review-contract).
- **Scheduled tasks**: one demo — e.g. a Monday-morning briefing that summarizes new files in a folder. Distinguish local scheduled tasks vs cloud Routines (run even with the computer off).

### Module 4 — Connecting their world + safety (45–60 min)
- **Connectors/MCP**: demo one end-to-end (Gmail or Drive is most universal): "find the latest email from X and save the attachment here, then summarize it."
- **Permission modes**: Ask (default — keep them here), Auto-accept edits, Plan mode (Claude proposes a plan, touches nothing — good for big jobs). Rule of thumb: stay on Ask until you trust a workflow.
- **Safety and trust**, non-negotiable to cover:
  - Files aren't modified until you accept; you can reject anything.
  - Work on copies of critical documents at first.
  - Data usage: consumer plans vs Team/Enterprise — point legal/regulated attendees at the data-usage doc.
  - Claude can be wrong; verify numbers and legal language. It's a junior assistant with infinite patience, not a professional of record.
- Cost basics: subscription plans, usage limits, model choice (default model is fine; bigger model for complex documents).

### Module 5 (optional/homework) — Industry tracks
Break-out or take-home exercise sheets, one per vertical:
- **Marketing**: turn one campaign brief into ad copy variants + a content calendar spreadsheet; repurpose a long blog post into 10 social posts in brand voice (voice lives in CLAUDE.md).
- **Real estate**: generate listing descriptions from property facts + photos; build a comparables table from a folder of PDFs; standardize 20 listings into one format.
- **Construction**: compare three subcontractor bids into a normalized spreadsheet with red flags; draft an RFI log from email threads; organize site photos by date/location.
- **Legal**: summarize a contract clause-by-clause; build a deadlines/obligations tracker from a matter folder; first-pass NDA triage (with the "you remain the professional of record" caveat).
- A genuinely useful capstone for all: "Have Claude build you a simple internal tool" — an HTML calculator, intake form, or dashboard. This is the one place to show that no-code people can ship "software."

## What to deliberately skip
Terminal/CLI, git/GitHub, hooks, subagents/agent teams, the Agent SDK, CI/CD, worktrees, environment variables. Mention they exist ("this scales all the way to engineering teams") and move on.

## Materials to prepare
1. Practice folder per attendee (realistic messy files per vertical).
2. One-page prompt cheat sheet (the five patterns + 10 example prompts per industry).
3. A starter CLAUDE.md template per vertical.
4. Pre-work email: install Desktop app, paid subscription active, Git on Windows.
5. Reference: free Anthropic Academy course "Claude Code in Action" (anthropic.skilljar.com) and Anthropic's "how our legal/marketing teams use Claude" blog posts for credibility with those verticals.

## Key doc pages backing each module
- M1: desktop-quickstart.md, how-claude-code-works.md, overview.md
- M2: prompt-library.md, best-practices.md, common-workflows.md
- M3: memory.md, skills.md, desktop-scheduled-tasks.md, discover-plugins.md, output-styles.md
- M4: mcp-quickstart.md, permission-modes.md, security.md, data-usage.md, costs.md
