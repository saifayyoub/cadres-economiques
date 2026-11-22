# Exam Hub â€” Vercel

Static site exposing two interactive Arabic exam tools.

## Structure

- / â€” hub page, lets the visitor choose an exam
- /cadres-economiques/ â€” interactive exam on decree 2.22.431 (100 questions)
- /comptabilite-publique/ â€” interactive exam on royal decree 330.66 (42 questions)

Both exam files are byte-identical copies of the original HTML files.

## Vercel

Framework Preset: Other
Build Command: (empty)
Output Directory: (empty / .)
Root Directory: .

No build step is required.

## Adding another exam

1. Create a folder such as /new-exam/ with an index.html.
2. Add a card for it in the root index.html.
