Criterion foyer export: popcorn-2026

START HERE:
  Open START-HERE.html directly from the extracted folder.
  It links to the self-contained review page at shows/popcorn-2026/foyer-pack/popcorn-foyer.html?preview=1.
  This is the file-share entry point for directors or publicity.

Live production engine:
  Do not open index.html directly with file://.
  The live engine uses JavaScript modules and requires a static host.
  From this folder run: python -m http.server 8000
  Then open: http://localhost:8000/?phase=preshow
  Theatre scene demo: http://localhost:8000/demo.html
  Hosted step-through review: http://localhost:8000/review.html

Share online:
  Upload this extracted folder to Netlify Drop or another static host.

Production engine routes:
  ?phase=preshow | interval | postshow
  ?scene=welcome | coming-soon | tonight

popcorn-foyer.html is a point-in-time review wrapper, separate from the live engine.
popcorn-foyer-preview.html is the retired preview and is not exported.
