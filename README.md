# Exam Hub - Vercel

Static site exposing four interactive Arabic exam tools.

## Structure

- / - hub page, lets the visitor choose an exam
- /cadres-economiques/ - interactive exam on decree 2.22.431 (100 questions)
- /comptabilite-publique/ - interactive exam on royal decree 330.66 (42 questions)
- /loi-cadre-51-17/ - interactive exam on framework law 51.17 (105 questions, 10 chapters)
- /examen-global-120/ - combined 120-question exam built from the two PDF parts

The first three exam files are byte-identical copies of the original HTML files.
The examen-global-120 page uses the same template/UI as the original exams and was
generated from the two supplied PDFs (examen_qcm_cadres_economiques_part1.pdf and
examen_qcm_cadres_economiques_part2.pdf).

## Vercel

Framework Preset: Other
Build Command: (empty)
Output Directory: (empty / .)
Root Directory: .

No build step is required.

## Adding another exam

1. Create a folder such as /new-exam/ with an index.html.
2. Add a card for it in the root index.html.
