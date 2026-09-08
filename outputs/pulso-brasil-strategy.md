# Pulso Brasil — strategy and operating context

Last updated: September 8, 2026. This is the central handoff document for future sessions. Recheck live account state before taking actions; this file records strategy and historical verification, not current credentials or blanket publishing authorization.

## Account and positioning

- X: https://x.com/PulsoBrasil
- Audience: Brazilian Portuguese readers interested in crime, scams, public safety, and some politics.
- User prefers footage, concrete incidents, short commentary, and related humor over formal, lengthy news explainers.
- Video selection priority (explicit user direction, September 7): find footage of the crime actually happening, especially CCTV/security cameras, dashcams, or eyewitness recordings. Presenter-led TV reports and news recaps are not the desired video format. Newsrooms can supply verification or publish the original footage; select the incident footage itself.
- Brand promise: “O Brasil acontece. A gente contextualiza.”
- Voice: direct, informal Brazilian Portuguese; informed, skeptical, concise. Avoid manufactured outrage and unsupported claims.
- Working mix: 40% crime/public safety, 30% scams/fraud/consumer traps, 20% politics connected to security/spending/services, 10% related original humor. These are experimental proportions, not proven audience preferences.
- Repeatable formats: “Câmera flagrou”, “Golpe da vez”, “E depois?”, “Prometeu / entregou”, and short original commentary.
- The user explicitly liked the banner. Preserve its bold condensed lettering, off-white/navy palette, green/yellow accents and editorial character. Do not reopen the rejected criticism of the banner as if the user accepted it.

## Growth objective and review — September 8, 2026

- Explicit user goal: reach **1,000 total X followers by September 30, 2026, 23:59 Brasília time**. This is a target, not a guaranteed outcome. Current follower count has not been verified; do not treat it as zero.
- Establish a dated follower baseline, then track net followers daily. Required daily pace = (1000 − current followers) / remaining days. From a hypothetical zero baseline on September 8, approximately 44 net followers per day across September 8–30 would be needed.
- Review finding: the strategy has a clear content direction but the existing queue is heavy on evergreen text, while the desired flagship format is verified incident footage. Prioritize filling the open crime/CCTV slots with inspected footage before expanding the queue. Keep the working content mix experimental.
- Continue the existing two-to-three quality posts per day and post-publication engagement plan. Use follow-up reporting and scam utility to give viewers a reason to follow beyond a single clip.
- At weekly reviews on September 13, 20 and 27, compare net follower growth with the required pace, assess which formats generate follows where attribution is available, and shift effort toward the strongest observed formats. Record account-level growth separately when post-level attribution is unavailable; views alone do not demonstrate follower conversion.
- The current research automation ends September 13. The month-end goal does not silently extend the automation or authorize automatic publishing; plan the remaining weeks explicitly.

## Required CCTV post format

Use the user's exact structure, preserving blank lines:

```text
🚨 ALERTA: {description}

Fonte: {source}, {date}

{video}
```

- `{description}`: concise Brazilian Portuguese description of the visible incident, with verified location and attribution where necessary. Avoid implying an old clip is a current emergency.
- `{source}`: credited newsroom, official source or original footage provider. Retain the supporting URL in the research record.
- `{date}`: use DD/MM/YYYY with an explicit label when necessary. Default the source line to `publicado em DD/MM/YYYY`; put a separately verified event date in the description when it differs. Never pass publication date off as incident date.
- `{video}` means the actual native video attachment, not literal placeholder text or an article link. In Buffer, send caption text and `assets.video.url` separately. Keep the caption within the account's character limit.
- Apply this format to new CCTV drafts and approved future posts; do not retroactively edit published posts without authorization.

## Brand assets

- Banner: [pulso-brasil-banner.png](pulso-brasil-banner.png)
- Latest logo: [pulso-brasil-logo-v2.png](pulso-brasil-logo-v2.png), the PB lettermark matching the banner. Delivered; no explicit final approval recorded.
- Earlier pulse/speech-bubble avatar was criticized and superseded. Do not use pulso-brasil-logo.png as the preferred asset.
- Generation prompts are saved beside these assets.

## Posting plan

- Timezone: America/Sao_Paulo (Brasília time).
- Target windows: 08:00, 12:30, 19:30. Test these; do not call them proven optimal times.
- Aim for two or three good posts daily. Skip weak/unverified stories rather than fill a quota.
- Schedule evergreen drafts ahead; select and verify current news near publication.
- Keep 10–15 evergreen drafts in reserve. Evergreen means independent of breaking news, not old incidents passed off as new.
- Spend 10–15 minutes engaging after posts; roughly five useful outside replies daily is a flexible starting point.
- Review typical impressions, reposts, meaningful replies and follower changes by format weekly. Do not infer growth from views alone.
- Current week is September 7–13, 2026, NOT September 14–20. See [weekly queue](pulso-brasil-week-2026-09-07.md).

## Sourcing and editorial checks

- Sources: local reporters/newsrooms, Band Brasil Urgente, Record Cidade Alerta, official Polícia Civil/SSP releases, Receita Federal, Procon, and primary legislative/government records.
- Search examples: “câmera de segurança” assalto; “câmeras flagraram” roubo; “roubo de celular” plus city; “golpe da maquininha”; “falso entregador” golpe.
- Treat forwarded/social clips as leads. Verify original source, incident date, location and context; distinguish publication date from event date.
- Distinguish personally inspected footage from a webpage merely reporting that footage exists. Attribute allegations and police accounts.
- Before recommending a crime video as ready, visually inspect it and record what incident is actually visible and the relevant timestamps. If a news package contains useful CCTV, identify that segment and preserve enough lead-in/aftermath to avoid misleading edits. If footage has not been inspected, label it an unverified lead. Prioritize direct footage with a short Portuguese caption, source credit, verified location and date; attach the actual video for approved publication.
- User prefers native video attachments for crime footage. Verify source/context and record reuse permission if known; a public newsroom page alone does not establish reuse permission.
- Protect victims; keep humor away from suffering. Avoid graphic injury as entertainment, celebrating violence, and unsupported identifications or accusations.
- Follow-ups are a differentiator: report what happened after the viral clip.

## Buffer MCP — verified connection

Verified by successful get_account, list_channels and get_channel calls on September 7, 2026 at approximately 19:35 Brasília time:

- MCP server: https://mcp.buffer.com/mcp
- Organization: “My organization”
- Organization ID: 6a9f3afef4d804a5e1ebf45e
- Channel name: PulsoBrasil
- Channel ID: 6a9f3b37cd8b9c702c26f164
- Service/type: twitter / profile
- Account link: https://twitter.com/PulsoBrasil
- Account and channel timezone: America/Sao_Paulo
- Channel was connected, unlocked; queue was not paused.
- Channel descriptor: X Free Profile; subscriptionType: None.
- Buffer account reported limits including scheduledPosts: 10. Verify exact current allowance and usage before loading a week of posts; do not assume space for all 21 slots.
- At the initial 19:35 verification only read access had been tested. Publishing subsequently succeeded for both a link post and a native video; see the publication history below.
- The initial verification did not change the channel schedule. Later draft/publication activity is recorded below.

Default queue schedule observed (not our editorial plan):

| Day | Buffer queue slots |
|---|---|
| Monday | 08:17, 09:01, 10:45, 11:00 |
| Tuesday | 08:13, 09:29, 10:16, 11:31 |
| Wednesday | 08:48, 09:04, 10:51, 11:07 |
| Thursday | 08:20, 09:04, 10:17, 11:02 |
| Friday | 08:45, 09:29, 10:42, 11:26 |
| Saturday | 08:09, 09:25, 10:18, 11:02 |
| Sunday | 07:42, 08:58, 09:16, 10:29 |

For an explicitly requested editorial time, use customScheduled and an ISO dueAt with the correct timezone offset, rather than addToQueue. Get current account time and verify the date is in the future. Rediscover organization/channel IDs using live tools before writes; these saved IDs are context, not a substitute for verification. Inspect existing posts to prevent duplication. Never store passwords or tokens in this document.

## Automation and authorization scope

- Automation name: “Pulso Brasil — pautas e posts”
- Automation ID: pulso-brasil-pautas-e-posts
- Type: heartbeat in the existing task.
- Task ID: 01a07ddd-4508-7932-b110-3f320f28ec14
- Updated September 8: one daily morning run starting 06:30 Brasília, aiming to deliver the whole-day batch around 07:00, through September 13 inclusive. This replaces the three daily research runs.
- Preparation produces a review batch. Scheduling requires explicit approval of the exact batch/posts; once approved, schedule through Buffer without another confirmation. No unapproved scheduling or publishing.
- Each run prepares 2–3 numbered ready-to-review posts for the whole day: final caption, actual media preview/playable clip, source/date and proposed 08:00, 12:30 or 19:30 slot. Resolve and inspect media before asking for approval; deduplicate against the task, repository and live Buffer queue.
- Notify for new useful drafts, substantive updates/corrections, failures or required user action; stay quiet when unchanged/non-actionable.
- Do not assume automation persists beyond this week or succeeded merely because it was configured. Inspect current status when relevant; update the existing automation rather than create a duplicate.
- The user wants as much automation as possible and connected Buffer. The user approved publication of the specific workflow-test draft below; that approval does not authorize unrelated future posts.
- Workflow test on September 7, 2026: created Buffer draft `6a9f41414c4e8f2911751f0c`, then published it after the user’s explicit approval. Published Buffer post ID: `6a9f41e3ff0db23b2209d61f`. Status verified `sent` at 19:59 Brasília time. The post links to Record’s original Cidade Alerta RJ page about a truck robbery on Avenida Brasil, Rio (page dated 09/04/2026). No native video file was uploaded because reuse rights/direct media URL were not established; the X post is link-based.
- Video workflow correction (September 7, 2026): the user specifically wants the actual clip attached to crime posts, rather than a news link alone. The Record page’s HLS stream was downloaded and remuxed to [pulso-brasil-assalto-caminhao.mp4](pulso-brasil-assalto-caminhao.mp4) for review. Correction: the earlier text-only claim was wrong. The MCP supports native video via `assets: [{video: {url: directMp4Url}}]`. “Minimum requirements: text only” means text alone suffices, not that media is prohibited. HLS (.m3u8) was rejected, but the original page exposes a direct MP4 in its VideoObject contentUrl/streams. Use that MP4 URL, verify the draft assets, and publish only within user authorization.
- Replacement attempt (September 7, 2026): the user authorized replacing the link post with the video post. Live Buffer state showed the sent post is not deletable through the MCP (`deletePost` absent from allowed actions), and the X browser session was logged out. That attempt completed neither action. The user subsequently withdrew deletion and authorized publishing the video as an additional post; leave the earlier link post intact.
- User-approved workflow: one morning batch → user approves all, selected numbered posts, or edits → schedule approved final versions for the day through Buffer → verify scheduled status/assets and record IDs. Edits alone are not approval unless the user also instructs scheduling. Approval includes the displayed slots; missed slots must not be backdated or silently published immediately. Use remaining approved future slots and resolve replacement timing for missed items.

## Next operational steps

1. When asked to prepare or schedule posts, read this document and the weekly queue, then recheck Buffer account/channel and existing posts.
2. Separate ready sourced drafts from unverified video leads. Several weekly-queue entries need further checks; do not automatically promote them to ready.
3. Use available posting capacity and future Brasília-time slots when scheduling is authorized.
4. Update the research automation to write Buffer drafts or publish only if the user authorizes that expanded behavior.
5. Record created draft/scheduled/published IDs, exact captions, dates and source links so future sessions can reconcile work.

## Native video publication — September 7, 2026

- User authorized publication via Buffer; prior link post is to remain intact.
- Video draft: `6a9f48825b3dd39bb39e9de7`; verified native video asset, 112879ms, 960×540, processing false.
- Publication submitted: `6a9f4897054b6beb81a86996`; verified `sent` at 20:28:42 Brasília, error null, assets contain `video`. X link: https://x.com/2096961756954259456/status/2097104802182275397
- Exact caption: VÍDEO | Assalto a caminhão na Avenida Brasil, na Zona Norte do Rio. Segundo o Cidade Alerta RJ, criminosos em motos invadiram a cabine e levaram a carga frigorífica para uma comunidade. Reportagem publicada em 09/04/2026.
- Documentation: https://support.buffer.com/en-us/articles/sharing-videos-through-buffer-LOe2p2rnAI

## Repository and handoff

- Repository: https://github.com/descobertas-pro-lar/pulso-media
- This repository holds the consolidated strategy, weekly queue, assets, prompts, media and workflow notes. Read README.md and AGENTS.md at the start of future sessions.
- See automation.md for the saved research automation prompt and schedule. This is documentation, not an automatically installed job.
- See outputs/pending-research.md for unfinished footage research.
- The pre-existing clips/tiroteio-cachambi-2026-09-04.mp4 was already in the repository when this context was imported. Its provenance, edits and publication status were not verified in this task.
