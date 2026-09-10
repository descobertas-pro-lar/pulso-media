# Pulso Brasil — task instructions

Canonical repository: https://github.com/descobertas-pro-lar/pulso-media. Use its current contents for all Pulso tasks. Reconcile remote changes without overwriting local work, and keep GitHub synced with decisions and results.

## Repository model: one folder per social platform

- `social/x/` is the ACTIVE channel (X/Twitter, @PulsoBrasil). All current operations live there.
- `social/instagram/`, `social/tiktok/`, `social/linkedin/`, `social/threads/` are reserved stubs for future expansion. Each contains a README describing what will live there. Do not create platform folders beyond these without user direction.
- `shared/` holds cross-platform material: brand assets, raw media, reusable operations docs, skills.
- Cross-cutting decisions that are not platform-specific (morning automation job, publishing tool workflow) live in `shared/operations/`.

Read README.md and social/x/strategy/editorial-strategy.md first. For original politics and culture commentary, also read social/x/strategy/tone.md. Read social/x/strategy/post-formats.md, social/x/strategy/cctv-post-template.md, social/x/strategy/scam-post-template.md, shared/operations/buffer-publishing.md, shared/operations/morning-automation.md, the relevant social/x/editorial/calendar/ weekly plan, and social/x/editorial/published/ records before posting work. social/x/strategy/growth-experiment-10k.md is a proposal, not adopted policy.

Save X research in social/x/editorial/research/, daily approvals in social/x/editorial/batches/YYYY-MM-DD.md, and publication results in social/x/editorial/published/YYYY-MM.md. Brand assets belong in shared/brand/; prepared videos in social/x/clips/; source reports in shared/media/source-reports/. Preserve public URLs of published media. README.md is a stable repo map for new agents — do NOT log daily activity in it; dated editorial files carry the day-to-day state.

When expanding to a new platform, copy the relevant strategy/format docs into that platform's folder, adapt formats to the platform (aspect ratios, caption limits, hashtag norms), and keep the same editorial discipline (inspection, approval before scheduling, publication log).

Verify live external state before mutations. Saved drafts and historical connection records do not prove current state or authorize publishing. Schedule only approved final posts; preserve the established morning approval workflow. Never save credentials.
