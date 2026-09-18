# INSY 2299 - interactive slides

Web versions of the INSY 2299 lecture decks, served by GitHub Pages.
Each deck is one self-contained HTML file: no build step, no dependencies.

    index.html                        landing page, links to each session
    INSY2299 - Session-4/index.html   Session 4 deck

## This repository is public

GitHub Pages needs a public repository on a free account, so treat everything
committed here as published. Put **only** finished decks in it - no solution
workbooks, no assignments, no exam material, and no real Blackboard sign-in
code on the attendance slide (it ships as `0000`).

## Publishing an update

Rebuild the deck, copy it over `INSY2299 - Session-4/index.html`, then:

    git add -A && git commit -m "Session 4: update" && git push

Pages redeploys in a minute or two.
