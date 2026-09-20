# Lily and Dino's Magical Tea Party

An interactive picture book for small children: a fairy called Lily, a friendly
dinosaur called Dino, and a tea party in a meadow.

The whole book is one file — [`index.html`](index.html). No build step, no
dependencies, no server needed. Open it in a browser and it runs.

## What's in it

- **A story to be read aloud.** The narrator uses the browser's own speech
  voices, casting a different one for Lily, Dino and the narrator, and
  highlights each word as it is spoken.
- **A picture that plays.** Tap Lily to make her sparkle, tap Dino to make him
  roar, shake the trees for fruit, pop the balloons, smell the flowers, and
  drag the food and teacups anywhere on the rug or the grass.
- **Play Time.** At the end (or from the title page) the story steps aside and
  the meadow is yours to potter about in.
- **Weather, time of day and holidays.** Rain, snow, morning, dusk and night,
  and six occasions — Christmas, Halloween, New Year, Easter, a birthday and
  Valentine's — each with its own sky, sounds, costumes and signboard.
- **Sound.** Everything is synthesised in the browser except three short
  clips — a roar, a slurp and a munch — which are embedded in the file itself.

## Running it

Open `index.html` in any modern browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000/>.

Speech needs Chrome, Edge or Safari; without it the book still reads on screen
and says so rather than failing silently.
