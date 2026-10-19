# INSY 2299 - interactive slides

Web versions of the INSY 2299 lecture decks, available via GitHub Pages.
Each deck is one self-contained HTML file.

    index.html                        landing page, links to each session
    INSY2299 - Session-1/index.html   Session 1 deck
    INSY2299 - Session-2/index.html   Session 2 deck
    INSY2299 - Session-3/index.html   Session 3 deck
    INSY2299 - Session-4/index.html   Session 4 deck
    INSY2299 - Session-5/index.html   Session 5 deck
    INSY2299 - Session-6/index.html   Session 6 deck
    INSY2299 - Session-7/index.html   Session 7 deck
    INSY2299 - Session-8/index.html   Session 8 deck

## Publishing an update

Rebuild the deck, copy it over `INSY2299 - Session-<N>/index.html`, then:

    git add -A && git commit -m "Session <N>: update" && git push

Pages redeploys in a minute or two.
