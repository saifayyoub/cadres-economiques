# Exam Hub - Vercel

Static site exposing eight interactive Arabic exam tools.

## Structure

- / - hub page, lets the visitor choose an exam
- /cadres-economiques/ - interactive exam on decree 2.22.431 (100 questions)
- /comptabilite-publique/ - interactive exam on royal decree 330.66 (42 questions)
- /loi-cadre-51-17/ - interactive exam on framework law 51.17 (105 questions, 10 chapters)
- /examen-global-120/ - combined 120-question exam built from the two PDF parts
- /projet-etablissement-integre/ - 100-question exam on the integrated school project (memo 014x24)
- /regime-cantine-scolaire/ - 112-question exam on the school canteen system guide (April 2022)
- /guide-gestion-financiere-materielle/ - 110-question exam on the financial and material management guide
- /loi-69-00-controle-financier/ - 100-question exam on law 69.00 on state financial control

The root page also has an About section with the author photo and introduction from
edumaroc.org, plus direct LinkedIn and Instagram contact links.

All eight exam files are byte-identical copies of their original HTML files.
The examen-global-120 page uses the same template/UI as the original exams and was
generated from the two supplied PDFs (examen_qcm_cadres_economiques_part1.pdf and
examen_qcm_cadres_economiques_part2.pdf).

## Vercel

Framework Preset: Other
Build Command: (empty)
Output Directory: (empty / .)
Root Directory: .

No build step is required.

The edumaroc favicon is served from the site root (/favicon.ico plus PNG variants),
matching the current icon used on edumaroc.org. Exam pages keep their original
byte-identical HTML and inherit the favicon via the automatic /favicon.ico request.

## Adding another exam

1. Create a folder such as /new-exam/ with an index.html.
2. Add a card for it in the root index.html.
