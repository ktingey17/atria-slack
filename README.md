# Tingey/Finch Acquisitions

Shared acquisitions workspace for Keegan Tingey and Connor Finch. Value-add retail, office, and flex deals in the California Central Valley and select Bay Area submarkets. Sub-$10M typical.

This repo is a **living knowledge base**. Keegan and Connor work deals in Slack with Claude; meaningful outputs — memos, lease abstracts, rent roll audits, comp work, decisions, post-mortems — get committed back here. Over time it becomes a searchable archive of every deal we've touched and why.

## How it works

1. **Discussion happens in Slack.** @mention Claude in a deal channel with whatever the deal needs — underwriting questions, lease review, rent roll audit, memo draft, comp pull, waterfall audit.
2. **Claude reads this repo first.** `CLAUDE.md` gives it team, thesis, underwriting conventions, and behavioral guidelines. Deal folders give it deal-specific context.
3. **Claude does the work and commits it back.** Output lands in the right deal folder via PR. Review, merge, move on.
4. **You can always come back.** Pull up any deal folder and see the full history — what we looked at, what we decided, what we learned.

## Structure

- `CLAUDE.md` — context and conventions. Start here.
- `deals/` — one folder per deal, named `YYYY-MM-Property-City/`
- `market/` — submarket notes, broker relationships, demographic data
- `conversations/` — optional archive of high-value Slack threads

## Example Slack prompts

```
@Claude abstract the attached lease and drop it in the Fairfield deal folder
@Claude audit the Quail Lakes waterfall — disposition proceeds look off
@Claude draft a one-page memo for the Fairfield deal based on what's in the folder
@Claude pull together a rent comp set for Stockton flex under 10k sf and save it
@Claude write a post-mortem for [dead deal] — why we passed
```

## Using this as a launch pad

This repo is also meant to seed new work. Pull a deal folder into a fresh Claude Code session when you want to go deeper — build a model, draft an LOI, prep for a broker call — and the context travels with you.

## Not in scope

OpenClaw development, personal tax strategy, True North deals, anything unrelated to active acquisitions work with Connor.
