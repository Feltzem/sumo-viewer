# Self-hosted webfaces

Archivo (variable, 400–700 upright) and Source Serif 4 (italic 400) back the v2 workspace
chrome. They are vendored rather than linked because the workspace runs offline against a
local FastAPI backend: a `fonts.googleapis.com` request simply fails there, and the page
would silently fall back to the system stack with no indication that the design it was
built against is not the one on screen.

Both are subset to `latin` and `latin-ext`. `latin-ext` is not optional — te reo Māori
macrons (ā ē ī ō ū, U+0100–U+016B) live there, and the te reo line in the masthead and any
Māori place name in the data need them.

Fetched from Google Fonts (Archivo v25, Source Serif 4 v14) on 2026-09-04. Both are under
the SIL Open Font License 1.1. To refresh, re-request the `css2` URLs for
`Archivo:ital,wght@0,400..700` and `Source+Serif+4:ital,opsz,wght@1,8..60,400` with a
modern browser User-Agent and download the `latin` and `latin-ext` `src` URLs.
