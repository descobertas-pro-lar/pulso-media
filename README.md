# Pulso Brasil

Strategy, editorial context and public media for [@PulsoBrasil](https://x.com/PulsoBrasil).

## Start here

1. Read [AGENTS.md](AGENTS.md) and the [strategy and operating context](outputs/pulso-brasil-strategy.md).
2. Read the [September 7–13 editorial queue](outputs/pulso-brasil-week-2026-09-07.md).
3. Review [pending research](outputs/pending-research.md) and the [research automation](automation.md).

## Editorial direction

Brazilian crime/public safety, scams, some politics and related humor. Prioritize CCTV, dashcam or eyewitness footage showing the incident itself, with short Brazilian Portuguese context. Visually inspect clips before recommending them. Presenter-led news packages are not the desired format.

## Assets and media

- [Approved banner](outputs/pulso-brasil-banner.png)
- [Latest logo matching the banner](outputs/pulso-brasil-logo-v2.png) — no explicit final approval recorded
- [Earlier rejected logo](outputs/pulso-brasil-logo.png) — historical reference only
- Generation prompts are saved in outputs/*prompt*.txt.
- [Truck robbery source video](outputs/pulso-brasil-assalto-caminhao.mp4) — historical workflow test, a news package rather than the preferred future format
- [Existing Cachambi clip](clips/tiroteio-cachambi-2026-09-04.mp4) — predates this import; provenance and publishing status require verification

## Publishing workflow

Research → inspect footage and verify context → present caption and clip for approval → publish through Buffer → verify sent status, native video asset and X link → record the result.

Buffer MCP supports native X videos with `assets: [{video: {url: directMp4Url}}]`. A public direct MP4 is required by this tested workflow; a local path is not a remote upload. An HLS URL failed in the test. “Minimum requirements: text only” does not prohibit video. No X browser login was needed for the successful MCP publication.

Publishing approval applies to the specific approved post, not all future posts. The research automation does not publish. Connection details and publication IDs are in the strategy; always recheck live state. Never commit credentials.

## Verified publication history

- [Article-link test](https://x.com/PulsoBrasil/status/2097097528776724517)
- [Native-video test](https://x.com/PulsoBrasil/status/2097104802182275397)

Both were published September 7, 2026. The user asked to retain the original link post. Saved context is historical evidence, not a fresh check of the account.
