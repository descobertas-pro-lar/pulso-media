# Pulso Brasil

Strategy, editorial context and public media for [@PulsoBrasil](https://x.com/PulsoBrasil).

This repository is the canonical source for all Pulso tasks, as designated by the user on September 8, 2026. Keep decisions, drafts, assets and operational results here; use the latest repository context in every task.

## Start here

1. Read [AGENTS.md](AGENTS.md) and the [strategy and operating context](outputs/pulso-brasil-strategy.md).
2. Read the [September 7–13 editorial queue](outputs/pulso-brasil-week-2026-09-07.md).
3. Review [pending research](outputs/pending-research.md) and the [research automation](automation.md).

**Goal: 1,000 followers by September 30, 2026 (Brasília time).** See the strategy for tracking and the required `🚨 ALERTA` CCTV template.

## Editorial direction

Brazilian crime/public safety, scams, some politics and related humor. Prioritize CCTV, dashcam or eyewitness footage showing the incident itself, with short Brazilian Portuguese context. Visually inspect clips before recommending them. Presenter-led news packages are not the desired format.

## File guide

### Project instructions and operations

| File | Purpose |
|---|---|
| [README.md](README.md) | Repository overview, reading order, file guide and publishing workflow. Start here to find the right document. |
| [AGENTS.md](AGENTS.md) | Instructions for assistants working on Pulso: use this repository as the canonical source, preserve existing work, verify live state and respect approvals. |
| [automation.md](automation.md) | Saved morning automation schedule and full prompt. Documents the live job; editing this Markdown file alone does not update or install the automation. |
| [.gitignore](.gitignore) | Keeps macOS metadata, local environment files and Python cache files out of Git. Never commit credentials. |

### Strategy, planning and research

| File | Purpose |
|---|---|
| [outputs/pulso-brasil-strategy.md](outputs/pulso-brasil-strategy.md) | Main operating document: audience, goals, editorial rules, CCTV template, posting cadence, Buffer workflow, authorization scope and historical publication records. Separates the current operating mix from the proposed 10k experiment. Update when decisions or operational results change. |
| [outputs/pulso-brasil-week-2026-09-07.md](outputs/pulso-brasil-week-2026-09-07.md) | September 7–13 editorial queue: draft captions, sources, proposed slots, verification gaps and workflow-test results. A listed draft is not automatically approved or scheduled. |
| [outputs/pending-research.md](outputs/pending-research.md) | Unfinished footage leads and next verification steps. Also contains the later September 8 Cachambi publication record; distinguish its published section from the unverified leads. |

### Brand assets and generation prompts

| File | Purpose / status |
|---|---|
| [outputs/pulso-brasil-banner.png](outputs/pulso-brasil-banner.png) | User-approved X banner and visual reference for the brand. |
| [outputs/banner-prompt.txt](outputs/banner-prompt.txt) | Original generation instructions for the banner: layout, colors, lettering and tagline. |
| [outputs/pulso-brasil-logo-v2.png](outputs/pulso-brasil-logo-v2.png) | Latest PB lettermark designed to match the banner. Preferred logo candidate; explicit final approval is not recorded. |
| [outputs/logo-v2-prompt.txt](outputs/logo-v2-prompt.txt) | Generation instructions for the PB logo using the banner as reference. |
| [outputs/pulso-brasil-logo.png](outputs/pulso-brasil-logo.png) | Rejected/superseded pulse-and-speech-bubble logo. Historical reference only. |
| [outputs/logo-prompts.txt](outputs/logo-prompts.txt) | Initial and refinement prompts for the earlier rejected logo. |

### Video files

| File | Purpose / status |
|---|---|
| [outputs/pulso-brasil-assalto-caminhao.mp4](outputs/pulso-brasil-assalto-caminhao.mp4) | Downloaded truck-robbery news package from the first video workflow test. Historical media; presenter-led reports are not the preferred future CCTV format. The successful Buffer post used the source's direct MP4 URL. |
| [clips/tiroteio-cachambi-2026-09-04.mp4](clips/tiroteio-cachambi-2026-09-04.mp4) | 26-second Cachambi/Engenho de Dentro incident excerpt. Source, cut timestamps, caption, Buffer ID and September 8 publication link are recorded in pending-research.md. |

`outputs/` holds working documents, brand assets and historical workflow media. `clips/` holds prepared clips for posts. Neither folder automatically publishes its contents. Git tracks changes; its internal `.git/` directory is not project content and is not listed here.

## Keeping context current

Save new Pulso decisions and results in this repository and keep GitHub in sync. Update this guide when adding or renaming files. Record draft, approved, scheduled and published states explicitly, including post IDs and timestamps when available. Read dated updates together: a later publication record may supersede an older pending note. Verify current Buffer/X state before acting.

## Publishing workflow

Research starts at 06:30 Brasília, aiming for one whole-day approval batch around 07:00. Review 2–3 numbered posts with final captions, media previews and proposed 08:00 / 12:30 / 19:30 slots. Approve or edit in one reply; approved final posts are scheduled through Buffer without another confirmation. Verify scheduled status and native assets; record IDs and times.

Buffer MCP supports native X videos with `assets: [{video: {url: directMp4Url}}]`. A public direct MP4 is required by this tested workflow; a local path is not a remote upload. An HLS URL failed in the test. “Minimum requirements: text only” does not prohibit video. No X browser login was needed for the successful MCP publication.

Publishing approval applies to the specific approved post, not all future posts. The morning batch is not scheduled until explicitly approved. Connection details and publication IDs are in the strategy; always recheck live state. Never commit credentials.

## Verified publication history

- [Article-link test](https://x.com/PulsoBrasil/status/2097097528776724517)
- [Native-video test](https://x.com/PulsoBrasil/status/2097104802182275397)
- [Cachambi incident clip](https://x.com/PulsoBrasil/status/2097163462010929591)

The two workflow tests were published September 7, 2026; the Cachambi clip was recorded as published September 8. The user asked to retain the original link post. Saved context is historical evidence, not a fresh check of the account.
