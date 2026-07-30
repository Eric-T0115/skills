# Skills

Curated Codex/Agent Skills workspace that packages five upstream skill collections
into one tracked repository.

## Included Collections

- Marketing Skills: 49 skills imported from `coreyhaines31/marketingskills`
- Stop Slop: prose de-AI editing skill from `hardikpandya/stop-slop`
- UI UX Pro Max: UI/UX design intelligence from `nextlevelbuilder/ui-ux-pro-max-skill`
- Remotion Best Practices: Remotion router skill set from `remotion-dev/skills`
- Context Engineering Skills: 17 skills from `muratcankoylan/Agent-Skills-for-Context-Engineering`

## Repository Layout

- `.agents/skills/`: workspace-local installed skills
- `.agents/tools/`: shared tool integration references used by Marketing Skills
- `PROJECT_HISTORY.md`: import history, pinned commits, and validation notes
- `THIRD_PARTY_NOTICES.md`: third-party attribution and licensing notes

## Install Result

This repository currently tracks 69 imported skill directories:

- 49 Marketing Skills
- 17 Context Engineering Skills
- 1 Stop Slop skill
- 1 UI UX Pro Max skill
- 1 Remotion router skill

## Validation Summary

The initial import on July 30, 2026 included:

- successful validation of all 69 skill directories
- resolution of broken Stop Slop reference files
- smoke tests for Marketing, Stop Slop, UI/UX, Remotion, and Context Engineering
- local Git publication on branch `codex/add-agent-skills`

## Global Codex Install

The same skill set was also copied into:

`C:\Users\USER-30\.codex\skills`

That global directory includes the 69 imported skills plus pre-existing Codex
system folders such as `.system` and `codex-primary-runtime`.

## Notes

- Upstream source commits are pinned in `PROJECT_HISTORY.md`
- Third-party licensing details are recorded in `THIRD_PARTY_NOTICES.md`
- Remotion content should be treated as evaluation material until its upstream
  redistribution terms are confirmed
