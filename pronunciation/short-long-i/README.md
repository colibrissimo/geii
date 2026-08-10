# Short & Long I Sounds — replica of the Genially lesson

Self-contained static deck. No account, no subscription, works offline if the
folder is copied to a USB stick. Open `index.html`.

Live: https://colibrissimo.github.io/geii/pronunciation/short-long-i/

## Navigation
- arrow keys / space / on-screen ‹ › to move between slides
- `Home` key or the ⌂ button returns to the index
- `#7` in the URL opens directly on slide 7 (useful for a Moodle link
  straight to the quiz: `.../short-long-i/#13`)

## Decisions taken 9 Aug 2026
- **`teen.mp3` moved from `audio/short/` to `audio/long/`.** "teen" is /tiːn/;
  it was misfiled in the original folder and would have marked correct quiz
  answers wrong.
- **The heavy GIFs became muted looping mp4s.** 12.7 MB of GIF → 349 KB, same
  animation. Source GIFs are untouched in `01_GEII/Resources/…/images/`.
- **The three videos are self-hosted, not embedded.** No YouTube, no Drive: the
  deck cannot be broken by a school filter or a dead link. The main
  ship-vs-sheep video was re-encoded 720p → 960×540 (29 MB → 13 MB).
- **The quiz is randomised over the whole recorded pool** (25 long + 19 short),
  ten questions per round, new round on demand — instead of the two fixed
  questions in the Genially.
- **`/i:/ is usually spelled 'i'` corrected to `/ɪ/`** on the short-vowel
  spelling slide.
- **The home button is dark blue with a white ring on every slide**, so it never
  disappears into a pink background.
- **Every word on the spelling slides is clickable and plays its recording.**
  The last four gaps (piece, complete, machine, magazine) were filled 10 Aug 2026
  with `say -v "Daniel (Enhanced)"` re-encoded to match the originals exactly
  (24 kHz mono, 48 kbps); Sarah verified all four by ear before install.
- `business / women / marriage / busy` promoted onto the NOTES slide as the
  "odd spellings" set, with audio.

## Added beyond the Genially
- **Slide 13, "Now forget everything"** — the four rule-breakers promoted out of
  the notes into their own slide, immediately before the quiz. Each word is
  clickable and marks the letter actually carrying the /ɪ/:
  w**o**men, b**u**sy, marri**a**ge, and bus**i**ness (where the *u* says
  nothing at all).

## Title slide, rebuilt 9 Aug 2026 (Sarah's composition)
Hands dropped. The leg enters top-left with the I-ball bobbing just off the toe
— keepie-uppie, kicking rightwards into the title — and the title plus START sit
in a right-hand column. The trainer is **not** mirrored: its toe already points
down-right, so `scaleX(-1)` put the ball behind the heel.

## Images still carrying someone else's branding
The deck reads whatever file sits at the path, so replacing a file is enough.
- ~~`yellow_tape.png`, `pink_tape.png` — "GENIALLY MIX Vol. 1 / 2"~~ **done by Sarah, labels now blank**
- ~~`assets/img/mixtape.gif` — "colorSTREET Mixtape"~~ **done 10 Aug 2026**: label
  painted blank across all 60 frames with a measured `drawbox`, re-encoded on a
  32-colour palette, 703 KB → 411 KB. All three cassettes now blank-label.

## Not carried over
- The "+ info" pop-ups on the two "Meet…" slides (they held no content that
  isn't already on the slide).
- Slide-entry animations. The deck cross-fades instead.
