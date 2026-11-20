# Music Sheet to MP3

Turn a PDF music sheet into a melody **MP3** and a **MIDI** file. Everything runs in your browser; the PDF is never uploaded.

## How to use

1. Choose a PDF music sheet.
2. Tap **Convert Now**. The app finds the staves, notes, rests, chords, ties, key and time signature by itself.
3. Play the result, then download the MP3 or the MIDI file.
4. Optional: open **Check and fix the notes**. Blue circles on the page show what was read. Fix a wrong note by typing its name (C4, F#3, Bb4, R for a rest; a chord is several names, like `C5 A4`), change its length, delete it, or add a rest, then tap **Update MP3 and MIDI**.

## What it reads

- Notes from whole to sixteenth, dotted notes, triplets
- Every note of a chord (notes stacked on one stem), played together
- Rests, ties, sharps, flats and naturals (they last to the end of the bar)
- Key signature and time signature (2/4, 3/4, 4/4 are found automatically)
- Bars that do not add up are repaired when there is one clear fix (for example a missed flag)

## Limits

- Best with computer-made PDFs (sheets from notation software). Scans and photos work less well.
- It plays one line of rhythm. When two voices on the same staff move at different speeds, they are read as one chord rhythm, so check those bars.
- Lyrics, chord letters, repeats, dynamics and grace notes are ignored.
- The sound is a simple piano-like tone, not a recording.

## Files

- `index.html` is the whole app (HTML, CSS and JavaScript in one file). It loads pdf.js and lamejs from cdnjs.
- `music-sheet-to-mp3-icon.png` is the Home Screen icon.

## Put it on GitHub Pages

1. Create a repository and upload `index.html` and `music-sheet-to-mp3-icon.png`.
2. Settings, Pages, Source: deploy from the `main` branch, root folder.
3. Open `https://<your-name>.github.io/<repository>/`.
