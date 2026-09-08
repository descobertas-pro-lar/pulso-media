# Video watermark — current direction, September 8, 2026

The user requests all future Pulso videos use a low-opacity watermark in the middle of the screen: the PB logo plus @PulsoBrasil. This supersedes the former top-bar and bottom-bar specifications across tasks.

## Specification

- Use the PB lettermark from `assets/brand/pb-avatar.png`, plus the exact handle `@PulsoBrasil`.
- Place logo and handle together as one compact, horizontally arranged group, centered horizontally and vertically over the actual footage.
- Use a transparent watermark background; no solid rectangular logo background or opaque backing panel.
- Low opacity applies to both logo and handle. Start at 20% opacity as an implementation default, adjusting slightly for footage contrast while keeping it subtle. The user requested low opacity, not a specific percentage.
- Start with the whole group around 25% of the frame width; keep the PB mark and handle legible and balanced. This size is an implementation default, not a fixed user requirement.
- Keep the original frame dimensions and source timestamps/credits. Do not append a top/bottom bar or side border.
- Inspect the actual rendered clip to ensure the watermark remains subtle and does not obscure key action, evidence or existing credits. Include the watermark in all future approval previews.
- Apply to future edits/publications. Do not change already published files or overwrite their stable public URLs.

## Rendering

Prepare a transparent RGBA PNG with the PB mark and handle, scale proportionally to the source, apply low alpha, then overlay at `(W-w)/2:(H-h)/2`. Preserve an unwatermarked source. Use a unique output filename for every final revision to prevent cached media reuse.
