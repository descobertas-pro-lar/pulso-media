# Pulso Brasil

Canonical repository for the Pulso Brasil social media operation, organized **one folder per social platform**. Currently active: [@PulsoBrasil on X](https://x.com/PulsoBrasil). Goal: **1,000 followers by September 30, 2026**, with a proposed path toward 10k.

## Structure

| Folder | Purpose |
|---|---|
| [social/x/](social/x/) | X/Twitter — the active channel: strategy, editorial, clips, publication log. |
| [social/instagram/](social/instagram/) | Instagram — reserved for future expansion. |
| [social/tiktok/](social/tiktok/) | TikTok — reserved for future expansion. |
| [social/linkedin/](social/linkedin/) | LinkedIn — reserved for future expansion. |
| [social/threads/](social/threads/) | Threads — reserved for future expansion. |
| [shared/brand/](shared/brand/) | Brand assets: avatar, banner, watermark spec (apply across platforms). |
| [shared/media/](shared/media/) | Raw source material (news packages, archive photos) shared across platforms. |
| [shared/operations/](shared/operations/) | Cross-platform operations: Buffer publishing workflow, morning automation. |
| [shared/skills/](shared/skills/) | Reusable skills (e.g. Pulso Viral Scout). |

## Start here (X channel)

1. [Task instructions](AGENTS.md) and [current strategy](social/x/strategy/editorial-strategy.md).
2. [Post formats](social/x/strategy/post-formats.md): exact layouts, media and source placement; then [Buffer workflow](shared/operations/buffer-publishing.md).
3. Relevant weekly calendar, pending leads, approval batches and publication log under [social/x/editorial/](social/x/editorial/).

Morning research starts at 06:30 Brasília, aiming for a batch around 07:00. The morning package also includes 3–5 suggested replies with target post links for the user to post. Aim for three main posts drawn from CCTV, scams and relevant politics. The user reviews captions/media/times; approved posts are scheduled for 08:00, 12:30 and 19:30. The current automation ends September 13. Proposal documents do not change the active mix or publishing authority.

## File guide (X channel)

| File | Purpose |
|---|---|
| [social/x/strategy/post-formats.md](social/x/strategy/post-formats.md) | Canonical format guide: CCTV, news/politics, scams, follow-ups and commentary. |
| [social/x/strategy/editorial-strategy.md](social/x/strategy/editorial-strategy.md) | Current positioning, 1k goal, posting plan and sourcing rules. |
| [social/x/strategy/scam-post-template.md](social/x/strategy/scam-post-template.md) | Required scam caption and meaningful evidence-media format. |
| [social/x/strategy/cctv-post-template.md](social/x/strategy/cctv-post-template.md) | Exact ALERTA caption layout, dates and attachment rules. |
| [social/x/strategy/growth-experiment-10k.md](social/x/strategy/growth-experiment-10k.md) | Proposed 60/30/10 test and measurement plan; not adopted. |
| [shared/operations/buffer-publishing.md](shared/operations/buffer-publishing.md) | Buffer connection history, native video support and approval workflow. |
| [shared/operations/morning-automation.md](shared/operations/morning-automation.md) | Saved live-job prompt and schedule; Markdown alone does not install a job. |
| [social/x/editorial/calendar/2026-09-07-to-2026-09-13.md](social/x/editorial/calendar/2026-09-07-to-2026-09-13.md) | Weekly drafts, time slots, verification notes and historical test notes. |
| [social/x/editorial/research/pending-leads.md](social/x/editorial/research/pending-leads.md) | Unverified leads awaiting footage/context checks. |
| [social/x/editorial/published/2026-09.md](social/x/editorial/published/2026-09.md) | September published captions, sources, post IDs and historical outcomes. |
| [social/x/editorial/batches/](social/x/editorial/batches/) | Daily approval batches with previews. |
| [social/x/editorial/research/](social/x/editorial/research/) | Sourcing and inspection records per story. |
| [social/x/editorial/scripts/](social/x/editorial/scripts/) | Video scripts (e.g. AI simulation proposals). |
| [social/x/clips/](social/x/clips/) | Prepared/published clips; stable public URLs, never overwrite. |
| [shared/brand/video-branding.md](shared/brand/video-branding.md) | Current centered PB logo + handle watermark specification, both at 50% opacity. |
| [shared/brand/README.md](shared/brand/README.md) | Brand selection and approval status. |
| [shared/media/README.md](shared/media/README.md) | Media naming and stable URL rules. |
| [.gitignore](.gitignore) | Excludes local environment files, OS metadata and caches. |

## Naming and maintenance

Use descriptive lowercase kebab-case names. Weekly plans: `social/<platform>/editorial/calendar/YYYY-MM-DD-to-YYYY-MM-DD.md`; batches: `social/<platform>/editorial/batches/YYYY-MM-DD.md`; publication logs: `social/<platform>/editorial/published/YYYY-MM.md`. Keep rejected brand work in shared/brand/archive/. Dates on media must have a documented meaning.

Existing published clip URLs are retained (paths unchanged under social/x/clips/). Add new decisions and results to the appropriate document, update this guide, and commit/push changes. Always verify live X/Buffer state before mutations; never commit credentials.

## September 9 review batch

- [Three-post batch](social/x/editorial/batches/2026-09-09.md), with actual previews in social/x/editorial/batches/media/2026-09-09/.
- [Sources and inspection](social/x/editorial/research/2026-09-09-three-posts.md). Awaiting approval; no new publishing.

September 9 item 3 now uses the São Benedito CCTV preview (`social/x/editorial/batches/media/2026-09-09/sao-benedito-cctv-preview.mp4`), replacing the PF/STF proposal at the user's request.

## Reusable skills

- [Pulso Viral Scout](shared/skills/pulso-viral-scout/SKILL.md): scan X for promising Brazilian stories, inspect footage, compare traction and produce sourced Portuguese recommendations. The repository copy includes Codex UI metadata in `shared/skills/pulso-viral-scout/agents/openai.yaml`. Install the `pulso-viral-scout` folder in your personal Codex skills directory to use `$pulso-viral-scout`. Scouting does not authorize publication.

## September 9 direction

Scam content is paused at the user's request due to reported weak performance. Prioritize actual incident footage; the former scam allocation is superseded. September 10 has a three-video review batch; no scheduling approval yet.

- [September 10 batch](social/x/editorial/batches/2026-09-10.md) and [source/inspection record](social/x/editorial/research/2026-09-10-viral-scout.md). Videos: [Flamengo store](social/x/clips/2026-09-10-flamengo.mp4), [Curicica](social/x/clips/2026-09-10-curicica.mp4), [Santana pharmacy](social/x/clips/2026-09-10-farmacia.mp4).

September 10 batch: all three videos approved and scheduled via Buffer; IDs and verification recorded in the batch and September publication log.

- [Football-betting opinion thread](social/x/editorial/batches/2026-09-10-futebol-bets-opinion.md): six-post draft with an original, visibly AI-labelled opening illustration; scheduled for 09:00 BRT Sep 10 with watermarked video `social/x/clips/0909-watermarked-v1.mp4`.
