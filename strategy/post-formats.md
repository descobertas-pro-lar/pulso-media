# Pulso Brasil — post formats

Canonical guide to what each kind of post looks like. Updated September 8, 2026. Read alongside [editorial strategy](editorial-strategy.md). This guide preserves the user's exact CCTV/scam templates and standardizes the remaining layouts for day-to-day preparation. Formats do not change the content mix or authorize publication.

## Choose the format

| Kind | Opening | Body | Source placement | Required attachment |
|---|---|---|---|---|
| CCTV / actual crime footage | `🚨 ALERTA: {description}` | Description is the opening paragraph; what happened, where and relevant incident date | Separate `Fonte:` line after description, before attachment | Native video showing the incident |
| News / politics | Short factual headline | Brief explanation of the new development and essential context | Separate `Fonte:` line after body; separate photo credit if different | Relevant photograph or genuine supporting image |
| Scam alert | `🚨 CUIDADO COM O {scam_name}` | How the lure works, why it seems credible and where the trap is | Attribution within description when needed; full source/date in batch record | Video or picture depicting the scam |
| Follow-up / “E depois?” | `ATUALIZAÇÃO: {new development}` | Recall the original case briefly, then explain what changed | Separate `Fonte:` line after body | Relevant image, or actual new incident footage using the CCTV format |
| Standalone commentary / audience question | The point or question itself | Optional short supporting thought | No source needed for a purely original opinion/question; source any factual claim | None required |

The core daily selection is crime footage, scams and relevant news/politics. Follow-up is a news variant, not an extra daily quota. Commentary is optional; no standalone meme format is established here. “Evergreen” describes shelf life, not a separate visual format.

## 1. CCTV / crime video

```text
🚨 ALERTA: {description}

Fonte: {source}, {DD/MM/YYYY}

{native video attachment}
```

- The opening description is the headline and caption together. No second title is needed.
- State the visible incident, verified neighborhood/city and incident date when relevant. Attribute outcomes or allegations that cannot be established from the footage.
- The source line belongs below the description: `Fonte: {source}, {DD/MM/YYYY}`, without “publicado em”. Do not repeat the source or its publication date in the opening. Publication date is not incident date; specify the verified incident date in the description when relevant.
- Use actual CCTV, dashcam or eyewitness footage. A report can supply context, but isolate the incident sequence rather than attach presenter-led coverage.
- Native attachment is mandatory; an article link is not a substitute.
- Add a red circle only when the action is hard to spot. Do not add one by default.
- Apply the video-branding rule below and inspect the final rendered clip.

Exact user template and detailed rules: [CCTV template](cctv-post-template.md).

## 2. News / politics

Default layout established by this organization pass; the user explicitly requires native caption text plus a relevant image.

```text
{short factual headline}

{what changed + essential context or attribution}

Fonte: {outlet or institution}, publicado em {DD/MM/YYYY}
Foto: {photographer/agency} {— arquivo, if applicable}

{relevant image attachment}
```

- Lead with the new fact, not a vague topic. The headline and body are native X text, never a headline banner or quote card.
- A short story may combine headline and explanation into one paragraph to fit the account limit. Keep source attribution and material qualifications.
- Use `URGENTE:` only for a verified development genuinely unfolding now. A newly published article about yesterday's event is not automatically breaking news.
- Separate confirmed action, official explanation, allegations and a reporter's account of motives. Do not convert a reported suspicion into a proven fact.
- Put `Fonte:` after the body. `Foto:` follows it when a distinct photo credit is applicable; retain any required credit. Avoid duplicate credit if the same credit is already clearly supplied in the attachment.
- Use a real contextual photo or genuine supporting image. An archive portrait can illustrate a subject, but label it as archive; do not imply it documents the reported meeting or event.
- No decorative text cards, generic stock imagery pretending to be evidence, or AI-generated documentary photographs of actual events.

Layout example only (not a verified story):

```text
{Autoridade} adia reunião sobre {assunto}

O encontro previsto para {data} ficou sem nova data. Segundo {fonte}, {contexto verificado}.

Fonte: {veículo}, publicado em {data}
Foto: {autor/agência} — arquivo

{foto relevante}
```

## 3. Scam alert

Preserve the user's template:

```text
🚨 CUIDADO COM O {scam_name}

{description}

{video or picture depicting the scam}
```

- Name the scam plainly, e.g. `GOLPE DA ENCOMENDA`.
- Explain the sequence: what arrives → what makes it believable → what the scammer tries to obtain. Build alertness through concrete details, not a government-ad tone or a list of generic safety tips.
- The user did not include a standalone `Fonte:` line in this template. Put necessary attribution in the description; keep the complete source URL and dates in the approval record. Preserve or add media credit where applicable.
- The attachment must help viewers recognize the scam: a message screenshot, fake-page screenshot, or video showing the method. Never substitute a decorative text card.
- Clearly label reconstructions; AI video must visibly say `SIMULAÇÃO COM IA`. Never call a recreation actual footage or present invented message wording as a quotation from a real victim.
- Show the mechanism without exposing personal data or usable malicious links/payment credentials.
- Missing suitable media means the draft is incomplete, even if its caption is finished.

Detailed rules: [scam template](scam-post-template.md). Script example: [delivery scam simulation](../editorial/scripts/2026-09-08-delivery-scam-ai-video.md).

## 4. Follow-up / “E depois?”

```text
ATUALIZAÇÃO: {new verified development}

{brief identification of earlier case}. {what is now confirmed, with attribution}.

Fonte: {source}, {DD/MM/YYYY}
Foto: {credit, when applicable}

{relevant image attachment}
```

A follow-up must contain new information: arrest, recovery, official response or another verified outcome. Do not repost the same incident as if it were new. State the actual procedural status; an arrest is not a conviction. Link the original Pulso post when useful and record it in the batch. If the new post's main asset is genuine incident footage, use the CCTV layout instead.

## 5. Standalone commentary / audience question

```text
{original observation or substantive question}
```

Native text, no banner needed. Example: “Qual detalhe fez você perceber que uma mensagem era golpe?” No mandatory title, emoji or source for this original question. Do not disguise news as commentary to bypass the image/source rules. Replies on other accounts are separate from main posts: provide a verified target link and proposed reply for the user to send.

## Shared media and publishing rules

- All prose is native X text. The media placeholder in these templates is an actual attachment, never text pasted into the caption. Preserve blank lines between text blocks.
- Keep captions within the live account limit (currently a 280-character working constraint); check the complete caption including source/credit. Cut repetition before removing essential context. Do not silently split into a thread.
- Full source URL, publication date, incident date, media origin, reuse status and inspection notes belong in the repository record even when not all fit in the public caption.
- Actual media must be present in the approval preview. Approval is for the final caption, attachment and proposed time. Edits alone do not authorize scheduling or publishing.
- Video branding: centered, semi-transparent PB logo + @PulsoBrasil watermark over the footage, both at 50% opacity by default, following the [canonical specification](../assets/brand/video-branding.md). The latest user direction supersedes previous top/bottom bars. Preserve source marks, timestamps, frame dimensions and already published files/URLs.
- This guide supersedes generic earlier “all text posts are text-only” wording: news requires an image; scams require meaningful video/image; standalone commentary may be text-only.

## What the morning approval package shows

For each numbered post: **kind → proposed date/time (Brasília) → exact caption → actual attachment (if required) → source link/date/context notes → readiness/approval status**. Source notes are internal review material; the public caption follows its template above. Incomplete media/source checks must be marked clearly. Keep reply suggestions separate and never infer reply authorization from approval of main posts.
