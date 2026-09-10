# Pulso Brasil

Canonical repository for the Pulso Brasil social media operation, organized **one folder per social platform**. Currently active: [@PulsoBrasil on X](https://x.com/PulsoBrasil).

## For agents: read this first

1. [AGENTS.md](AGENTS.md) — task instructions and repo rules (read before any work).
2. [social/x/strategy/editorial-strategy.md](social/x/strategy/editorial-strategy.md) — current positioning, goals, posting plan, sourcing rules.
3. [social/x/strategy/post-formats.md](social/x/strategy/post-formats.md) — exact caption layouts, media rules, source placement.
4. [shared/operations/buffer-publishing.md](shared/operations/buffer-publishing.md) — how publishing works (Buffer, approvals, native video).
5. [social/x/editorial/published/](social/x/editorial/published/) — what has already been published (dedupe against this).

Day-to-day state (batches, research, leads) lives under `social/x/editorial/` — check the newest dated files there, not this README.

## Structure

| Folder | Purpose |
|---|---|
| [social/x/](social/x/) | X/Twitter — the active channel. |
| ├─ [strategy/](social/x/strategy/) | Positioning, posting plan, caption templates (CCTV, scam, formats, growth proposal). |
| ├─ [editorial/](social/x/editorial/) | Working state: calendar/, research/, batches/ (+ media previews), scripts/, published/. |
| └─ [clips/](social/x/clips/) | Prepared/published videos. Public raw URLs; never overwrite/move/rename files a Buffer post may still fetch. |
| [social/instagram/](social/instagram/) | Reserved for future expansion (stub with launch checklist). |
| [social/tiktok/](social/tiktok/) | Reserved. |
| [social/linkedin/](social/linkedin/) | Reserved. |
| [social/threads/](social/threads/) | Reserved. |
| [shared/brand/](shared/brand/) | Brand assets: avatar, X banner, [video watermark spec](shared/brand/video-branding.md) (centered PB logo + handle, 50% opacity), generation prompts, archive/ for rejected work. |
| [shared/media/](shared/media/) | Raw source material: source-reports/ (full news packages), news-images/. |
| [shared/operations/](shared/operations/) | Cross-platform ops: [buffer-publishing.md](shared/operations/buffer-publishing.md), [morning-automation.md](shared/operations/morning-automation.md). |
| [shared/skills/](shared/skills/) | Reusable skills, e.g. [Pulso Viral Scout](shared/skills/pulso-viral-scout/SKILL.md) (scan X for promising Brazilian stories; scouting never authorizes publication). |

## Hard rules

- **Approval before scheduling.** Nothing publishes or schedules without the user's explicit approval of the exact caption + media. Edits alone are not approval.
- **Stable media URLs.** Clips are consumed by Buffer at publish time via raw GitHub URLs. Never overwrite, move or rename a clip that any scheduled/published post references. New render = new unique filename.
- **Verify live state before mutations.** Saved docs do not prove Buffer/X state; check live before writing.
- **Inspect footage before recommending.** Sample frames with ffmpeg, vision-check, record what is shown + timestamps. Leads are leads until inspected.
- **Dates are documented.** Event date and publication date are recorded separately; every date on media has a documented meaning.
- **No credentials in the repo.** Ever.

## Naming

Descriptive lowercase kebab-case. Weekly plans: `social/<platform>/editorial/calendar/YYYY-MM-DD-to-YYYY-MM-DD.md`; batches: `social/<platform>/editorial/batches/YYYY-MM-DD.md`; publication logs: `social/<platform>/editorial/published/YYYY-MM.md`; clips: `YYYY-MM-DD-location-incident.mp4`.

Keep this README stable: it maps the repo, it does not log daily activity. Daily decisions and results go in the dated editorial files.
