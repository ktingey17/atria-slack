# Atria Acquisitions — Second Brain

Shared acquisitions workspace and **second brain** for Keegan Tingey and Connor Finch. Value-add retail, office, and flex deals in the California Central Valley and select Bay Area submarkets. Sub-$10M typical.

This repo is a **persistent memory layer for Slack.** Keegan and Connor work deals in Slack with Claude; meaningful outputs — memos, lease abstracts, rent roll audits, comp work, decisions, post-mortems — get committed back here. The `memory/` folder keeps Claude current across sessions so every Slack interaction picks up where the last one left off.

## How it works

1. **Discussion happens in Slack.** @mention Claude in the Atria channel with whatever the deal needs — underwriting questions, lease review, rent roll audit, memo draft, comp pull, waterfall audit.
2. **Claude reads the brain first.** `CLAUDE.md` + `memory/context.md` give it team, thesis, conventions, current pipeline state, recent decisions, and lessons learned.
3. **Claude does the work and commits it back.** Output lands in the right folder. Memory files get updated when state changes.
4. **You can always come back.** Pull up any deal folder and see the full history — what we looked at, what we decided, what we learned.

## Structure

```
memory/              → The second brain core: live state, decisions, lessons, glossary
deals/active/        → Currently active deal folders
deals/passed/        → Dead deals with post-mortems
deals/closed/        → Closed deals
market/              → Submarket notes, comps, broker network
research/            → Playbooks, strategies, general research
meetings/            → Call notes, weekly syncs
planning/            → Strategic planning, goals, pipeline targets
conversations/       → Archived high-value Slack threads
claude.md            → Claude's operating instructions
```

## Example Slack prompts

```
@Claude abstract the attached lease and drop it in the Fairfield deal folder
@Claude audit the Quail Lakes waterfall — disposition proceeds look off
@Claude draft a one-page memo for the Fairfield deal based on what's in the folder
@Claude pull together a rent comp set for Stockton flex under 10k sf and save it
@Claude write a post-mortem for [dead deal] — why we passed
@Claude what's our current pipeline look like?
@Claude what did we decide on Quail Lakes?
@Claude what lessons have we learned about waterfall audits?
```

## Not in scope

OpenClaw development, personal tax strategy, True North deals, anything unrelated to active acquisitions work with Connor.
