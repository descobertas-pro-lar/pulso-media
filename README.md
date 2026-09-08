# Pulso Brasil

Canonical repository for [@PulsoBrasil](https://x.com/PulsoBrasil): strategy, approvals, operations and media. Goal: **1,000 followers by September 30, 2026**, with a proposed path toward 10k.

## Start here

1. [Task instructions](AGENTS.md) and [current strategy](strategy/editorial-strategy.md).
2. [CCTV template](strategy/cctv-post-template.md) and [Buffer workflow](operations/buffer-publishing.md).
3. Relevant weekly calendar, pending leads, approval batches and publication log below.

Morning research starts at 06:30 Brasília, aiming for a batch around 07:00. The user reviews captions/media/times; approved posts are scheduled for 08:00, 12:30 and 19:30. The current automation ends September 13. Proposal documents do not change the active mix or publishing authority.

## File guide

| File | Purpose |
|---|---|
| [README.md](README.md) | Repository map and reading order. |
| [AGENTS.md](AGENTS.md) | Instructions for all Pulso tasks and repository synchronization. |
| [.gitignore](.gitignore) | Excludes local environment files, OS metadata and caches. |
| [strategy/editorial-strategy.md](strategy/editorial-strategy.md) | Current positioning, 1k goal, posting plan and sourcing rules. |
| [strategy/cctv-post-template.md](strategy/cctv-post-template.md) | Exact ALERTA caption layout, dates and attachment rules. |
| [strategy/growth-experiment-10k.md](strategy/growth-experiment-10k.md) | Proposed 60/30/10 test and measurement plan; not adopted. |
| [operations/buffer-publishing.md](operations/buffer-publishing.md) | Buffer connection history, native video support and approval workflow. |
| [operations/morning-automation.md](operations/morning-automation.md) | Saved live-job prompt and schedule; Markdown alone does not install a job. |
| [editorial/calendar/2026-09-07-to-2026-09-13.md](editorial/calendar/2026-09-07-to-2026-09-13.md) | Weekly drafts, time slots, verification notes and historical test notes. |
| [editorial/research/pending-leads.md](editorial/research/pending-leads.md) | Unverified leads awaiting footage/context checks. |
| [editorial/published/2026-09.md](editorial/published/2026-09.md) | September published captions, sources, post IDs and historical outcomes. |
| [editorial/batches/README.md](editorial/batches/README.md) | How to record each day’s approval batch. |
| [assets/brand/README.md](assets/brand/README.md) | Brand selection and approval status. |
| [assets/brand/x-banner.png](assets/brand/x-banner.png) | Approved X banner. |
| [assets/brand/pb-avatar.png](assets/brand/pb-avatar.png) | Latest PB avatar candidate; final approval not recorded. |
| [assets/brand/prompts/x-banner.txt](assets/brand/prompts/x-banner.txt) | Banner generation prompt. |
| [assets/brand/prompts/pb-avatar.txt](assets/brand/prompts/pb-avatar.txt) | PB avatar generation prompt. |
| [assets/brand/archive/rejected-pulse-avatar.png](assets/brand/archive/rejected-pulse-avatar.png) | Superseded avatar, historical only. |
| [assets/brand/archive/rejected-pulse-avatar-prompts.txt](assets/brand/archive/rejected-pulse-avatar-prompts.txt) | Prompts for the rejected avatar. |
| [media/README.md](media/README.md) | Media naming and stable URL rules. |
| [media/source-reports/2026-04-09-avenida-brasil-truck-robbery.mp4](media/source-reports/2026-04-09-avenida-brasil-truck-robbery.mp4) | Full downloaded news package from the workflow test. |
| [clips/README.md](clips/README.md) | Prepared clip provenance and compatibility explanation. |
| [clips/tiroteio-cachambi-2026-09-04.mp4](clips/tiroteio-cachambi-2026-09-04.mp4) | Published 26-second incident clip; URL retained. |

## Naming and maintenance

Use descriptive lowercase kebab-case names. Weekly plans: `editorial/calendar/YYYY-MM-DD-to-YYYY-MM-DD.md`; batches: `editorial/batches/YYYY-MM-DD.md`; publication logs: `editorial/published/YYYY-MM.md`. Keep rejected brand work in archive/. Dates on media must have a documented meaning.

The former outputs/ directory has been split by purpose. Existing published clip URLs are retained. Add new decisions and results to the appropriate document, update this guide, and commit/push changes. Always verify live X/Buffer state before mutations; never commit credentials.
