---
name: pulso-viral-scout
description: Scan X/Twitter for Brazilian crime footage, scam evidence and related news with promising early traction for Pulso Brasil. Use when asked to scout viral candidates, find high-potential posts or rank content to cover; returns sourced recommendations, not automatic publication.
---

# Pulso Viral Scout

Find content that could perform well for @PulsoBrasil, with evidence for the recommendation. Virality is uncertain: distinguish observed traction, editorial appeal and verification confidence. Default to three strongest candidates and two backups, unless the user specifies another count. A short verified list beats filling a quota.

## Load current context

Canonical repository: https://github.com/descobertas-pro-lar/pulso-media . Known checkout: `/Users/user1/Documents/Codex/2026-09-07/y/pulso-media`; locate a current checkout if it moves. Read its AGENTS.md, README.md, strategy/editorial-strategy.md and strategy/post-formats.md, plus current batches, research and publication records. For final previews read the relevant CCTV/scam and branding guides. Current repository rules override defaults here. Preserve local work and reconcile remote updates before editing.

Pulso's audience is national, Brazilian Portuguese, interested in actual crime footage, concrete scams and connected politics. Prefer CCTV, dashcam and eyewitness footage of the incident over presenter-led reports. Do not force one item from every category. Honor requested geography/topic overrides without changing permanent strategy.

## Scan X with an honest coverage boundary

1. Check current Brasília time. Search the past 24 hours first, then expand to 72 hours if needed. State the actual window. Older incidents can qualify when a verified new development creates a reason to cover them, but label their original dates.
2. Discover a callable X search/read connector first. If unavailable, use an available browser and its documented UI APIs. Web search restricted to `site:x.com` or `site:twitter.com` is a discovery fallback, not evidence that X was scanned comprehensively. Open exact posts to verify text, timestamp, media and visible metrics. Never describe search snippets or inaccessible timelines as inspected posts. If login or access blocks inspection, report the gap and continue with accessible sources; no invented results.
3. Use several query families and vary cities/regions. Examples: `"câmera de segurança" assalto`, `"câmeras flagraram" roubo`, `"vídeo" "golpe"`, `"falso entregador"`, `"golpe da maquininha"`, `"dashcam" Brasil`. Use current date filters where supported. Sample both recent and popular results: popular results alone miss emerging stories. Follow leads from local newsrooms, reporters, original witnesses and official police/consumer-protection accounts. Resolve current handles; do not invent handles.
4. Aim to inspect 10–20 distinct leads when access permits, stopping when enough well-supported candidates exist. Treat this as a practical search budget, not a claim of coverage. Expand weak searches rather than repeatedly opening the same viral repost. Use related reporting for corroboration and locating earlier uploads.
5. Capture exact post URL, account, post timestamp/timezone, observation timestamp, visible views/likes/reposts/replies and quote count if exposed. Record unavailable values as unknown. Round displayed values honestly (`1.2K` is approximate). Separate post age from incident age. Preserve public source URLs, never credentials or session data.

## Identify early momentum

Compare posts of similar age and format. High totals on an old post or a huge account do not by themselves demonstrate breakout potential.

- With two existing snapshots of the same post, calculate changes per elapsed hour in views/reposts/likes. These are measured growth rates; one snapshot is insufficient to claim acceleration. Reuse prior research snapshots where available. Do not wait or install monitoring merely to collect a second sample unless requested.
- With one snapshot, total divided by post age is only an average since publication. Label it as such, avoid unstable rates from posts younger than 15 minutes, and do not call it current velocity.
- When practical, inspect 5–10 recent comparable posts by the same account. Compare at similar ages; if only lifetime counts are available, label the comparison rough. Exclude pinned posts, ads and unrelated formats. Report sample size and median, not a made-up account baseline. Follower count alone is a weak denominator.
- Read several accessible replies/quotes to see whether people are sharing the incident, asking for context or exposing a recycled/false claim. Controversy and reply volume are not automatically favorable signals. A repost cascade can be many copies of one source, not independent corroboration.
- Note saturation: widely recycled footage may already be exhausted. Prefer a credible early source, a new angle or a useful verified follow-up. Do not penalize a small account merely for having fewer absolute views.

## Verify before promoting

Cluster duplicates by incident, visible footage and source chain, not only URL/text. Deduplicate against Pulso's repository and live Buffer/X posts when accessible. Keep the best source link; count one incident once. If live deduplication is blocked, mark it pending.

For each finalist, open the source and visually inspect the incident media. Record the visible sequence and timestamps, original/source account where traceable, location, incident date, upload date and corroborating report. Separate what is visible from claims made by witnesses, police or reporters. Inspect footage before drafting a confident description. A clip mentioned by an article but not watched remains a lead.

Check earlier uploads or credible reporting when date/location seems inconsistent. A new upload does not make an old crime current. Do not invent names, motives, arrests, weapon details or injuries. Rank unclear provenance lower and state the specific unresolved fact. Exclude graphic injury used as entertainment, victim humiliation and unsupported identifications. Preserve source credit; record reuse status as known or unknown, never infer permission from public availability.

## Rank transparently

Use this lightweight heuristic only after verification gates. Rate each dimension 0–4, with a one-line evidence reason:

| Dimension | Weight | What supports a high rating |
|---|---:|---|
| Observed traction | 30% | Measured growth or convincing comparison with similarly aged posts |
| Pulso audience fit | 25% | Strong fit with the current editorial strategy |
| Visual clarity and opening | 20% | Understandable action early, sufficient context, usable source media |
| Freshness and room to add value | 15% | Recent incident/development, limited saturation, missing useful context |
| Reason to share | 10% | Concrete warning, surprising visible turn, verified follow-up or useful context |

For known dimensions calculate `100 × sum(weight × rating / 4) / sum(known weights)`. Report evidence coverage as the sum of known weights; mark unknown dimensions N/A rather than assigning zero or guessing. Rank candidates with different evidence coverage cautiously; do not let a high provisional score outrank a well-supported candidate automatically. The score is an editorial prioritization heuristic, not a probability or a validated forecast. Keep source confidence separate: verified / partially verified / unverified. Only verified finalists may be called ready for review; traction can still be unavailable.

## Deliver a decision-ready shortlist

Lead with the strongest recommendation and why it has room to perform. For each finalist provide:

- Exact X post link and corroborating source; source account, incident date and post age.
- Observed metrics with capture time, baseline/growth evidence where available, score with evidence coverage and verification status.
- One sentence explaining the hook and one concrete caveat (e.g., saturation or missing incident date).
- Actual inspected media preview/playable source and relevant action timestamps; distinguish inspected source from a finished branded edit.
- A concise Portuguese caption in the repository's required format. Never use invented urgency or sensational claims to improve the score.

Offer a recommended order, not just highest view totals. Include a brief coverage note (window, leads inspected, access limits) and why backups lost. Put detailed metrics and sources in the research record so the chat stays concise.

If the user requested finished posts, complete branded media, native-caption limits and final previews under the repo's format rules before requesting approval. Scouting alone does not require editing/downloading every candidate. Missing required media means the post is incomplete. A link to an article is not a native video attachment.

Save a dated research record in `editorial/research/YYYY-MM-DD-viral-scout.md`, preserving earlier runs as timestamped sections. Record observations, not just scores, so future runs can compare. Save an approval batch only when preparing actual posts. Update the repository map and sync within existing authorization. If the repo is inaccessible, deliver findings inline and state what was not saved.

## Scope and feedback

Scouting is read-only on X: no likes, follows, replies, DMs, reposts or publishing. Scheduling requires approval of exact final captions/assets/times. Creating this skill does not create a recurring monitor or extend an existing automation; use scheduling tools only when requested.

When later asked to evaluate results, compare selected posts at consistent elapsed ages (e.g., 1h, 6h, 24h) with Pulso's own comparable posts. Track follows when attribution is available, alongside reposts/views and meaningful replies. Missing metrics are unknown. Preserve original predictions and record outcomes separately; revise the heuristic only with enough comparable observations, not a single viral hit. Never claim the score predicts virality statistically without actual validation.
