# Tingey/Finch Acquisitions

Shared acquisitions workspace for Keegan Tingey and Connor Finch. Value-add retail, office, and flex deals in the California Central Valley and select Bay Area submarkets. Sub-$10M typical.

This repo is accessed primarily through Claude Code in Slack. @mention Claude in a deal channel and it will read this repo for context before responding — underwriting questions, lease reviews, rent roll audits, comp work, memo drafting, whatever the deal needs.

## Structure

- `CLAUDE.md` — context and conventions Claude reads on every session. Start here.
- `deals/` — one folder per deal, named `YYYY-MM-Property-City/`
- `playbooks/` — reusable templates (memo, lease abstract, rent roll, comp set)
- `market/` — submarket notes, demographic data, broker relationships

## Using this repo via Slack

In any Slack channel where Claude is invited:

```
@Claude abstract the attached lease against our standard checklist
@Claude audit the Quail Lakes waterfall — disposition proceeds look off
@Claude draft a one-page memo for the Fairfield deal based on what's in the folder
@Claude pull together a rent comp set for Stockton flex under 10k sf
```

Claude will spin up a session, read `CLAUDE.md` and any referenced files, do the work, and open a PR back into the repo. Review, merge, move on.

## Using this repo directly

Clone it. Edit markdown. Commit. Claude reads whatever is on the default branch at session start, so keep the main branch current.

## Conventions

See `CLAUDE.md`. Short version: follow the deal folder structure, show your math, flag open questions, push back on weak assumptions, never fabricate data.

## Not in scope

OpenClaw development, personal tax strategy, True North deals, anything unrelated to active acquisitions work with Connor.
