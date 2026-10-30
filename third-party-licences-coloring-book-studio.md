---
layout: default
title: "Third-Party Licences - Coloring Book Studio"
permalink: /third-party-licences-coloring-book-studio/
---

# Third-party licences — Coloring Book Studio

Last updated 29 October 2026

Coloring Book Studio includes and relies on the work of others. Each component
below keeps its own licence, which governs that component regardless of
anything in the Coloring Book Studio licence agreement. Nothing in our
agreement takes away a right these licences give you.

**This file ships with the application** — in the install folder and reachable
from the app. Including the licence text is a condition of distributing these
components, not a courtesy.

> **Before release:** download the full licence text for each entry into
> `legal/licences/` in the application repository and confirm the version
> numbers match what was bundled. `pip list` prints them.

---

## Python

The language the application is written in. Version bundled: **3.14**
<https://www.python.org/>

Released under the **Python Software Foundation License**, a permissive licence
compatible with commercial distribution.

---

## CustomTkinter

The user interface toolkit — every window, panel and control. Version bundled:
**6.0.0**
<https://github.com/TomSchimansky/CustomTkinter>

Released under the **MIT Licence**. Permissive: use, modify and distribute,
including commercially, provided the copyright notice and licence text are
included.

---

## Pillow

Image handling: reading generated artwork, resampling, thresholding to pure
black and white for print, and every rendered surface in the interface.
Version bundled: **13.0.0**
<https://python-pillow.github.io/>

Released under the **MIT-CMU licence** (historically the PIL Software
License). Permissive, with an attribution requirement.

---

## NumPy

Array arithmetic for the measurements — erosion curves, stroke-width
distributions, and the lighting maps used when a cover is composited into a
mockup. Version bundled: **2.5.4**
<https://numpy.org/>

Released under the **BSD 3-Clause Licence**. Permissive, with attribution and
a no-endorsement clause.

---

## pywebview

Hosts the printable channel sheets in a native window. Version bundled:
**6.2.1**
<https://pywebview.flowrl.com/>

Released under the **BSD 3-Clause Licence**.

---

## pypdfium2 / PDFium

PDF rendering — rasterising a cover PDF so the artwork can be cropped and
placed. Version bundled: **5.14.0**
<https://github.com/pypdfium2-team/pypdfium2>

The binding is released under **Apache-2.0 or BSD-3-Clause**, at your option.
PDFium itself — the PDF engine from the Chromium project — is released under a
**BSD-style licence**, and further open-source licences apply to libraries
bundled inside it. All of those licence texts ship with the application, as
their terms require.

> **Why not PyMuPDF.** An earlier build used PyMuPDF for this. PyMuPDF is
> dual-licensed AGPL v3 or commercial, and the AGPL does not permit
> distributing it inside a closed-source application. It was replaced rather
> than licensed, because it was doing one small job that a permissively
> licensed engine does just as well.

---

## PDF writing

PDFs are assembled by Pillow, listed above. No separate PDF library is
involved in writing them.

---

## What the application does not include

- No analytics, telemetry, advertising or tracking of any kind.
- No bundled third-party software beyond the components listed above.
- No image generation. Artwork is made in whatever tool you choose, under that
  tool's own terms, and imported.

---

Questions about any entry on this page: ali.risner14@gmail.com
