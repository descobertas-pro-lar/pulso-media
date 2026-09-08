# Video branding — approved September 8, 2026

Every published @PulsoBrasil video gets a branded bottom bar APPENDED BELOW the footage. The video area is never covered.

## Spec

- Canvas: video height + 56px navy bar (`#0B1120`), same width (e.g. 960x540 → 960x596)
- Left: `@PulsoBrasil` in cream `#F2F0E6`, Arial Bold 26px, at x=26, vertically centered in bar
- Right: PB logo (`assets/brand/pb-avatar.png`) resized 44x44, 12px from right edge, 6px top margin in bar
- No other accent bars, no overlays on the footage itself

## ffmpeg (no drawtext in current build — pre-render text and logo as PNGs)

```bash
# one-time assets (regenerate if brand changes):
#   /tmp/pb_logo_44.png   — pb-avatar.png resized to 44x44
#   /tmp/handle_txt.png   — '@PulsoBrasil' Arial Bold 26 cream on transparent
ffmpeg -ss <start> -to <end> -i source.mp4 -i pb_logo_44.png -i handle_txt.png \
  -filter_complex "[0:v]pad=960:596:0:0:color=0x0B1120[bg]; [bg][1:v]overlay=904:546[b1]; [b1][2:v]overlay=26:549" \
  -c:v libx264 -preset fast -crf 20 -c:a aac -y out-branded.mp4
```

For non-960-wide sources, scale first and adjust overlay coordinates.

Brand palette: navy `#0B1120`, cream `#F2F0E6`, green `#2ECC71`, yellow `#F1C40F`.
