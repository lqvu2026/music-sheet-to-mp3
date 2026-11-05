# Music Sheet to MP3

Turn a simple PDF music sheet (one melody line) into an MP3. Runs entirely in the browser.

1. Choose the PDF.
2. Pick clef/voice, key signature, time signature and tempo.
3. Tap **Read the notes**, then check and fix them in the list (note name, length, delete, add a rest).
4. **Play** to listen, **Make MP3** to download.

Reads: note heads, half/whole notes, eighths, sixteenths, dotted notes, triplets (found from the bar total), top note of stacked chords.
Does not read: rests, accidentals written beside a note, ties, repeats/endings (plays straight through), scanned or photographed pages.

## Publishing (GitHub Pages)
Put `index.html` and `music-sheet-to-mp3-icon.png` (your 180x180 icon) in the repo and commit both.
The head already has the `apple-touch-icon` link. After committing, wait 1-2 minutes, delete any old shortcut, quit Safari, reload, Add to Home Screen.
