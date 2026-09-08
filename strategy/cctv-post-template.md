# CCTV post template

See [Post formats](post-formats.md) for the complete format catalog and shared publishing rules.



## Required CCTV post format

Use the user's exact structure, preserving blank lines:

```text
🚨 ALERTA: {description}

Fonte: {source}, {date}

{video}
```

- `{description}`: concise Brazilian Portuguese description of the visible incident, with verified location and attribution where necessary. Avoid implying an old clip is a current emergency.
- `{source}`: credited newsroom, official source or original footage provider. Retain the supporting URL in the research record.
- `{date}`: source publication date in DD/MM/YYYY, without “publicado em”. Use exactly `Fonte: {source}, {DD/MM/YYYY}` on a separate line below the description. Put the verified incident date in the description when relevant; do not duplicate the newsroom attribution or source publication date there. Never pass publication date off as incident date. User explicitly clarified this on September 8, 2026.
- `{video}` means the actual native video attachment, not literal placeholder text or an article link. In Buffer, send caption text and `assets.video.url` separately. Keep the caption within the account's character limit.
- Apply this format to new CCTV drafts and approved future posts; do not retroactively edit published posts without authorization.


## Video annotation

Use a red circle only when the action is hard to spot, such as when it happens far in the background or amid visual clutter (user clarification, September 8). Leave clearly visible action unannotated; circles are a clarity aid, not a default decoration. Position/time it accurately, move it when needed, preserve source credits and key details, and inspect the rendered result. Show the annotated clip in the approval batch; retain the original.
