# SAQR: Scroll Unveiling

By @abdomahrous.design on Instagram. Download all the files in this folder (index.html, hero-1.js, hero-2.js, orbit-1.js, orbit-2.js) into one folder and open `index.html` in your browser, then scroll (or drag the dial). Live demo: https://abdogfx92.github.io/nauta-liquid/saqr/

## The prompt

```
Build a scroll-driven unveiling page for a hand-built café racer called SAQR "Model 1". No libraries: one index.html with all CSS/JS inline, plus orbit.js holding the orbit frames (keep the two files side by side). Every image is inlined as base64 WebP so it opens offline by double-click.

FOOTAGE
- Hero: one AI video clip (Veo 3.1 in Google Flow), locked-off camera: a dust sheet flies off a black-and-tan café racer standing in a dark, dusty Cairo hall with light shafts. Export ~190 frames.
- Orbit: one continuous camera move around the same bike in the same hall, bike always facing right (never mirrored): headlamp → tank → engine → seat and silencer. Keyframe stills first (Nano Banana, earlier frames as references), then animate and chain the clips so the last frame of one is the first of the next. Export ~380 frames.

HERO (pinned, sticky, ~6 screens of scroll)
- A full-screen canvas draws the hero frame for the current scroll position, eased so it glides instead of stepping.
- Title "BUILT TO / be ridden" (wide grotesk + italic serif) with one line of copy fades out as you start.
- A thin arc with a knob, "Drag to reveal": dragging the knob along the arc scrubs the same timeline; the arc fills in brass.
- Bottom-left italic caption: The veil → The pull → Unveiled. Top-right film timecode "REEL 01 · 00:SS:FF" counts with progress.
- As soon as the sheet leaves the frame, the reveal text rises line by line: "SAQR MOTORCYCLES / MODEL 1 CAFÉ" top-left, a huge outline "1966" top-right, "BUILT slow / RIDDEN hard" bottom-right. A slow 3% push-in while it holds.

DESIGN (pinned, 4 stops)
- The next section is held by CSS sticky and fades in over the hero in about a third of a screen (no JS transforms, so nothing jitters). Its headline "NOTHING ON IT YOU DON'T NEED." is visible from the first frame, so MODEL 1 crossfades straight into it.
- A second canvas scrubs the orbit frames: ease-in-out camera moves between four stops, short holds on each detail. Only a window of frames around the camera is kept decoded.
- On each hold: a ring hotspot on the part, a hairline to a zoom card on the right, an outline number "01 / 04", title and two lines of copy (Chrome headlamp, Hand-painted tank, Air-cooled twin, Saddle & silencer). Four progress bars fill with scroll.

SPECIFICATION (pinned, 6 steps)
- An SVG tachometer (0–10 × 1000 rpm, red line from 8): glowing hot arc, ticks light up, the needle eases to a new reading for every spec row with a tiny idle jitter, and the big number counts up (650 cc, 52 hp, 4.9 s, 186 km/h, 168 kg, 48 bikes). The active row lights up in brass.

WORKSHOP + BOOKING
- A giant outline "HANDBUILT" drifting sideways with scroll, "Handbuilt, / not assembled.", two photo cards whose numbers count up (1,200 hours, 9 coats).
- A bone-coloured booking panel slides up with a wavy cloth edge: "The sheet comes off / once a month.", a simple form, and a giant "SAQR" wordmark.

TRANSITIONS
- Simple and smooth only: rise + fade, crossfades between sections, no slice/glitch effects, no camera cuts. Section progress is smoothed (lerp) so the scroll never feels steppy.

Palette: near-black #0d0c0b, bone #ece6dc, brass #c9a35c, redline #c8432b. Type: a wide grotesk for headlines, an italic serif for accents, a mono for labels. Mobile (<760px): the canvas shows the whole bike in the lower two thirds and the title sits on black above it; touch drag works on the dial. Add ?static=1 for still captures.
```

Concept site, illustrative figures. Footage made with Veo 3.1 (Google Flow) and Nano Banana keyframes.
