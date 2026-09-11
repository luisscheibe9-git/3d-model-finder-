# TARGET: today's build

This is the approved brief for the balanced STL and CAD model finder.

- **Thing:** A one-page 3D model finder that turns one search into links across a curated mix of major and independent STL and CAD-model websites.
- **Audience:** A hobbyist maker or engineering student who wants to find a printable model or an editable CAD file without searching many websites separately.
- **Requirements:** Provide one clear search field; let users toggle between **Printable STL** and **Editable CAD**; when CAD is selected, let users filter by compatible application; organize sources into general-printing and engineering/CAD groups; generate source-specific search links; honor the standing rule in `AGENTS.md`.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, scraping, or private data. Never claim that results are exhaustive, available, safe to print, or compatible with an application unless the original source provides that information. Label sample content clearly. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A search-first layout inspired by Apple's clarity, with generous whitespace, restrained typography, subtle depth, and one cool-blue accent. Place the STL/CAD toggle directly below the search field and reveal simple CAD-application filters only when needed.
- **Test:** I can search for "phone stand," switch between printable and editable models, select a CAD application, see appropriate source options, identify every option's original website, and open its provider search.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
