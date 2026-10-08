# High Roller

A fantasy character roller. Six lines, no prose.

- Positive trait
- Positive trait, with a cost
- Negative trait
- One physical trait that should not describe anyone else
- One manner of speech: a fixed line, or a quirk of how they talk
- Two mundane interests that have nothing to do with the plot

Physical traits and manners of speech are remembered in this browser until the pile is empty, or until you hit Reset.

## Add a line

Open the matching file in `data/`, add one line, commit. Blank lines and lines starting with `#` are ignored. Do not use modern objects.

- `data/positive.txt`
- `data/positive-cost.txt`
- `data/negative.txt`
- `data/physical.txt`
- `data/phrase.txt`
- `data/unrelated.txt`

A tab after the text is reserved for tags. The page ignores anything after a tab.

## Site

GitHub Pages, from the `main` branch, root folder. The page fetches the text files, so it has to be opened on the site, not as a downloaded file.
