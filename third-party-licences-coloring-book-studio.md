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

## PyMuPDF

PDF assembly and inspection — building the final interior files and reading
them back to verify page count, size and placement. Version bundled: **2.0**
(with `pymupdf4llm` and `pymupdf_layout`)
<https://pymupdf.readthedocs.io/>

**Dual-licensed: GNU AGPL v3, or a commercial licence from Artifex.**

> **This one is not like the others, and it is not resolved.**
>
> The AGPL is a strong copyleft licence. Distributing a closed-source
> application that includes PyMuPDF is only permitted under the AGPL if the
> application's own source is released under compatible terms. Coloring Book
> Studio is sold as a closed-source product, so one of the following has to be
> true before it is sold:
>
> 1. a commercial licence is obtained from Artifex, the commercial licensing
>    agent for MuPDF; or
> 2. PyMuPDF is replaced with a permissively licensed PDF library; or
> 3. the application's source is released under AGPL-compatible terms.
>
> Until one of those is done, this entry is a statement of the problem rather
> than a grant of rights. It is recorded here in full because the honest
> version of a licences page says what is unsettled.

---

## What the application does not include

- No analytics, telemetry, advertising or tracking of any kind.
- No bundled third-party software beyond the components listed above.
- No image generation. Artwork is made in whatever tool you choose, under that
  tool's own terms, and imported.

---

Questions about any entry on this page: ali.risner14@gmail.com
