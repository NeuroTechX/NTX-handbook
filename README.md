# NTX Handbook

The internal manual for NeuroTechX volunteers. It is published at
**https://neurotechx.org/handbook**: the website converts these pages every night. Chapters and
clubs have their own guide at https://neurotechx.org/guide.

Edit the `.rst` files here. Pages marked **Draft** describe a decision the Executive Director or
the board has not taken yet. To preview locally:

    python -m venv .venv && .venv/bin/pip install -r requirements.txt
    .venv/bin/sphinx-build -b html . _build/html

## French

French translations live in `fr/`: `fr/index.rst` (French section headings, same page list) and one
`fr/<page>.rst` per translated page, with the same file name as the English page. The site
(neurotechx.org) publishes them under /fr; a page without a French file is shown in English with a
notice. When you change an English page, update its French file too, or say in the pull request
that the French needs updating. Sphinx skips `fr/` (see `exclude_patterns` in conf.py).
