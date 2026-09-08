# Buffer publishing and approval workflow

Historical verification details are retained below. Recheck live state before mutations.

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
- At the initial 19:35 verification only read access had been tested. Publishing subsequently succeeded for both a link post and a native video; see the publication log in editorial/published/2026-09.md (repository-relative).
- The initial verification did not change the channel schedule. Later draft/publication activity is recorded in the publication log.

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
- The user wants as much automation as possible and connected Buffer. The user approved publication of the specific workflow-test posts in the publication log; that approval does not authorize unrelated future posts.
- User-approved workflow: one morning batch → user approves all, selected numbered posts, or edits → schedule approved final versions for the day through Buffer → verify scheduled status/assets and record IDs. Edits alone are not approval unless the user also instructs scheduling. Approval includes the displayed slots; missed slots must not be backdated or silently published immediately. Use remaining approved future slots and resolve replacement timing for missed items.

## Next operational steps

1. When asked to prepare or schedule posts, read this document and the weekly queue, then recheck Buffer account/channel and existing posts.
2. Separate ready sourced drafts from unverified video leads. Several weekly-queue entries need further checks; do not automatically promote them to ready.
3. Use available posting capacity and future Brasília-time slots when scheduling is authorized.
4. Update the research automation to write Buffer drafts or publish only if the user authorizes that expanded behavior.
5. Record created draft/scheduled/published IDs, exact captions, dates and source links so future sessions can reconcile work.


## Native video attachment

Use `assets: [{video: {url: directMp4Url}}]`. HLS (.m3u8) failed in the test; a direct MP4 worked. Text-only minimum requirements do not prohibit media. Verify the video asset before scheduling and sent status after publishing. See the [publication log](../editorial/published/2026-09.md) for post IDs and historical results.
